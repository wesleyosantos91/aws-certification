# 📘 AWS Certified Solutions Architect - Domínio 2: Design de Arquiteturas Resilientes

Este guia cobre os principais tópicos e boas práticas relacionados ao design de arquiteturas resilientes na AWS, com foco nos conceitos exigidos em exames de certificação.

---

## ✅ 1. Escolha de Armazenamento Confiável/Resiliente

### 🧹 Disco Efêmero (Ephemeral Volume)
- Armazenamento temporário criado e destruído junto com a instância, pod ou tarefa.
- Dados são perdidos após reinicialização ou término da instância/container.
- Exemplos: `emptyDir` no Kubernetes, EC2 `instance store`.

### 💾 Amazon EBS (Elastic Block Store)
- Armazenamento em blocos persistente para instâncias EC2.
- Alta disponibilidade dentro de uma única AZ.
- Replicação entre zonas via **snapshots** no Amazon S3.
- Tipos: `gp3`, `io2`, `st1`, `sc1`.

### 🗃️ Amazon S3 e Amazon Glacier
- Armazenamento de objetos com alta durabilidade.
- **S3**: ideal para dados frequentemente acessados.
- **Glacier**: otimizado para arquivamento de longo prazo.
- Suporte a políticas de ciclo de vida e objetos de até 5TB.

### 🗂️ Amazon EFS (Elastic File System)
- File system compatível com NFS, escalável e de alta disponibilidade (Multi-AZ).
- Acesso simultâneo por múltiplas EC2s.
- Ideal para workloads com acesso concorrente a arquivos.

---

## ⚖️ 2. Load Balancers

### 🌐 Network Load Balancer (NLB)
- Opera na **Camada 4** (Transporte).
- Baixa latência e milhões de conexões por segundo.
- Suporte a TCP/UDP e IPs elásticos.

### 🧠 Application Load Balancer (ALB)
- Opera na **Camada 7** (Aplicação).
- Balanceamento baseado em path, headers, host.
- Ideal para microsserviços e aplicações web.
- Suporta WebSocket e autenticação.

---

## 🔧 3. CloudFormation

- Infraestrutura como código com YAML ou JSON.
- Automatiza criação, alteração e remoção de recursos.
- Suporte a:
  - StackSets
  - Mappings: chave-valor por região, ambiente, AMI, VPC, etc.

---

## ⚙️ 4. AWS Lambda

- Serviço serverless de execução sob demanda.
- Suporta diversas linguagens: Python, Node.js, Java, Go, .NET, etc.
- Tempo máximo por execução: 15 minutos.
- Tamanho do pacote: até 50 MB (zip) ou 10 GB (imagem container).
- Cobrança por invocação e duração.

---

## 🌪️ 5. Estratégias de Disaster Recovery (DR)

### 📍 Conceitos Fundamentais

#### RPO (Recovery Point Objective)
- Quanto de dados pode ser perdido.
- Ex: RPO de 1h → perda máxima aceitável de 1 hora de dados.

#### RTO (Recovery Time Objective)
- Quanto tempo o sistema pode ficar indisponível.
- Ex: RTO de 4h → sistema deve ser restaurado em até 4 horas.

### 📋 Estratégias de DR

| Estratégia                     | RPO     | RTO     | Custo      | Características                                                                  |
|-------------------------------|---------|---------|------------|----------------------------------------------------------------------------------|
| Backup & Restore              | Horas   | Horas   | Baixo      | Backup em S3/Glacier, restauração manual.                                       |
| Pilot Light                   | Minutos | Horas   | Moderado   | Infra mínima ativa, escala sob demanda.                                         |
| Warm Standby                  | Minutos | Minutos | Alto       | Ambiente secundário parcialmente ativo.                                         |
| Multi-site (Active-Active)    | Segundos| Segundos| Muito alto | Total redundância, tráfego ativo nas duas regiões.                             |

### 🔁 Tipos de Failover

- **Manual**: backup & restore.
- **Automatizado com scripts**: pilot light, warm standby.
- **Automático**: active-active, RDS Multi-AZ, Route 53 failover.

---

## 🧠 Dicas Importantes

- ❌ **Evite Single AZ**: Soluções resilientes devem ser Multi-AZ por padrão.
- ✅ **Prefira serviços gerenciados da AWS**: Menos responsabilidade operacional.
  - Ex: RDS, S3, DynamoDB.
- ❗ **Alta disponibilidade ≠ Tolerância a falhas**:
  - Alta disponibilidade = sistema acessível mesmo com falhas.
  - Tolerância a falhas = sistema continua funcional mesmo com falhas totais de componentes.
- 🔄 **Tudo vai falhar eventualmente**:
  - Projete pensando em falhas.
  - Implemente retries, failover, replicações, backups e monitoramento.

---

## 📚 Referências oficiais

- [AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html)
- [AWS Disaster Recovery Strategies](https://docs.aws.amazon.com/whitepapers/latest/disaster-recovery-workloads-on-aws/disaster-recovery-workloads-on-aws.html)
- [AWS Storage Services Overview](https://aws.amazon.com/products/storage/)

---

> ✨ Este conteúdo é parte de um guia maior de preparação para certificações AWS. Para sugestões de melhoria ou colaboração, fique à vontade para abrir um issue ou PR!

