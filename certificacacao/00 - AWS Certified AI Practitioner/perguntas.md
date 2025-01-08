# Domínio 1: Fundamentos de IA e ML

1. **Qual é o objetivo principal da IA generativa?**

    **R:** A IA generativa é um tipo de IA que visa criar conteúdo, como imagens, textos, músicas ou conversas.  
    **Referência:** [AWS - IA generativa](https://aws.amazon.com/what-is/generative-ai/)

2. **Qual estágio do pipeline de desenvolvimento de modelos concentra-se na avaliação do desempenho do modelo?**

    **R:** Na avaliação do modelo, é necessário determinar quão bem um modelo atinge os respectivos objetivos testando o desempenho, o viés e as explicações antes da implantação.  
    **Referência:** [AWS Well-Architected Framework](https://docs.aws.amazon.com/pt_br/wellarchitected/latest/machine-learning-lens/model-evaluation.html)

3. **Quais fatores podem afetar a latência da invocação de um grande modelo de linguagem (LLM)? (Selecione DUAS.)**

    **R:**
    - O número de tokens no prompt de entrada afeta a latência da invocação do LLM.
    - O número de tokens na resposta afeta a latência da invocação do LLM.  
    **Referência:** [AWS - Latência em LLMs](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/inference.html)

4. **Um especialista em IA está treinando um modelo de ML de regressão e observando o viés e a variância durante o treinamento. Qual padrão de viés e variância resultará no sobreajuste do modelo?**

    **R:** O baixo viés indica que o modelo não está fazendo suposições errôneas sobre os dados de  treinamento. A alta variância indica que o modelo está prestando atenção ao ruído nos dados de   treinamento e está se sobreajustando.  
    **Referência:** [AWS - Overfitting](https://aws.amazon.com/what-is/overfitting/)

5. **Quais são as desvantagens ou limitações de trabalhar com a IA generativa? (Selecione DUAS.)**

    **R:** A alucinação ocorre quando um grande modelo de linguagem (LLM) gera informações falsas.
    Os LLMs são pré-treinados em conjuntos de dados estáticos, resultando em uma limitação de dados.  
    **Referência:**
    - AWS - [Alucinações na IA generativa](https://docs.aws.amazon.com/pt_br/amazonq/latest/qbusiness-ug/concepts-terms.html)
    - AWS - [RAG e limitação de dados](https://aws.amazon.com/what-is/retrieval-augmented-generation/)

6. **Qual métrica pode avaliar o desempenho do modelo de base (FM) no contexto de resumo de texto?**

    **R:** ROUGE-N é uma métrica que pode avaliar a qualidade dos resumos de texto comparando sobreposições de n-gramas entre o resumo gerado e os resumos de referência.  
    **Referência:** [AWS - Métricas de resumo](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/clarify-foundation-model-evaluate-overview.html)

7. **Qual técnica melhorará de maneira mais confiável o desempenho do FM para resolver problemas matemáticos passo a passo?**

    **R:** A técnica de "cadeia de pensamento" (Chain of Thought) divide uma questão complexa em partes menores, permitindo ao modelo raciocinar e fornecer explicações claras.  
    **Referência:** [AWS - Cadeia de pensamento](https://aws.amazon.com/what-is/prompt-engineering/)

8. **Um desenvolvedor precisa de uma solução para criar um assistente virtual baseado em linguagem natural. Qual serviço da AWS atenderá a esses requisitos?**

    **R:** O Amazon Lex é um serviço gerenciado que pode ser usado para criar bots usando IA conversacional.  
    **Referência:** [AWS - Amazon Lex](https://docs.aws.amazon.com/pt_br/lexv2/latest/dg/what-is.html)

9. **Qual técnica ajuda a mitigar alucinações em grandes modelos de linguagem (LLM)? (Selecione DUAS.)**

    **R:**
    - Usar soluções de RAG (Recuperação Aumentada) para enriquecer o prompt com informações confiáveis.  
    - Criar prompts claros com instruções precisas.
    **Referência:**
    - [AWS - RAG](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/jumpstart-foundation-models-customize-rag.html)
    - [AWS - Engenharia de prompts](https://aws.amazon.com/what-is/prompt-engineering/)

10. **Qual é o propósito de usar incorporações em um modelo de geração de texto?**

    **R:** As incorporações são representações vetoriais que capturam relações semânticas, permitindo   ao modelo entender e gerar textos coerentes.  
    **Referência:** [AWS - Incorporações em IA](https://aws.amazon.com/what-is/transformers-in-artificial-intelligence/)

11. **Qual métrica a empresa deve usar para avaliar um modelo de chatbot baseado em semelhança com especialistas humanos?**

    **R:** BERTScore mede a similaridade semântica entre respostas geradas e respostas de referência.
    **Referência:** [AWS - Métricas de avaliação](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/clarify-foundation-model-evaluate-overview.html)

12. **Quais estratégias fazem parte do design centrado no ser humano para IA usando RLHF? (Selecione DUAS.)**

    **R:**
    - Ajuste fino supervisionado de modelos de linguagem.
    - Uso de modelos de recompensas baseados em feedback humano.  
    **Referência:** [AWS - RLHF](https://aws.amazon.com/what-is/reinforcement-learning-from-human-feedback/)

13. **Um engenheiro de ML quer aprimorar o desempenho de um LLM com o menor custo. Qual técnica deve ser priorizada?**

    **R:** A engenharia de prompts é a técnica mais econômica, pois não requer infraestrutura adicional e ajusta a entrada para melhorar as respostas.  
    **Referência:** [AWS - Engenharia de prompts](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/what-is-prompt-engineering.html)

14. **Uma empresa quer treinar um modelo de IA que minimiza alucinações com base em sua própria documentação. Qual solução atende a esses requisitos?**

    **R:** RAG (Recuperação Aumentada) reduz alucinações ao enriquecer os prompts com informações específicas e confiáveis da empresa.  
    **Referência:** [AWS - RAG](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/jumpstart-foundation-models-customize-rag.html)

15. **Qual é o objetivo principal de um modelo de prompt na engenharia de prompts?**

    **R:** Os modelos de prompt padronizam entradas e saídas de IA, garantindo consistência e melhorando o desempenho do modelo.  
    **Referência:** [AWS - Modelos de prompt](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/prompt-templates-and-examples.html)

# Domínio 2: Fundamentos de IA generativa

1. **Qual é o objetivo principal da IA generativa?**  
   **R:** A IA generativa é um tipo de IA que visa criar conteúdo, como imagens, textos, músicas ou conversas.  
   ****Referência:**** [AWS - Generative AI](https://aws.amazon.com/what-is/generative-ai/)

2. **Quais são as desvantagens ou limitações de trabalhar com a IA generativa? (Selecione DUAS.)**  
   **R1:** A alucinação ocorre quando um grande modelo de linguagem (LLM) gera informações falsas. A resposta normalmente parece correta, então o usuário pode ser enganado.  
   **R2:** Os grandes modelos de linguagem (LLMs) são pré-treinados em conjuntos de dados estáticos, onde os dados têm um limite. Portanto, o conhecimento aprendido tem uma limitação de dados.  
   **Referências:**  
   - [Amazon Q Business UG - Concepts and Terms](https://docs.aws.amazon.com/pt_br/amazonq/latest/qbusiness-ug/concepts-terms.html)  
   - [AWS - Retrieval Augmented Generation](https://aws.amazon.com/what-is/retrieval-augmented-generation/)

3. **Uma escola quer usar um modelo de base (FM) para criar uma aplicação para ajudar os alunos a resolver problemas matemáticos em simulados. Para ajudar os alunos, a aplicação deve fornecer o raciocínio e a explicação passo a passo do motivo pelo qual uma resposta no simulado está certa ou errada. Qual técnica melhorará de maneira mais confiável o desempenho do FM?**  
   **R:** A cadeia de pensamento é uma técnica de engenharia de prompts que divide uma questão complexa em partes menores. É recomendada quando há tarefas aritméticas e lógicas que exigem raciocínio.  
   **Referência:** [AWS - Prompt Engineering](https://aws.amazon.com/what-is/prompt-engineering/)

4. **Qual é o objetivo principal do uso de modelos de prompt na engenharia de prompts?**  
   **R:** Os modelos de prompt são formatos predefinidos que podem ser usados para padronizar entradas e saídas de modelos de IA. Eles garantem consistência e aumentam o desempenho do modelo.  
   **Referência:** [AWS - Prompt Templates and Examples](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/prompt-templates-and-examples.html)

5. **Qual solução melhorará a qualidade da saída de resumos gerados por um FM?**  
   **R:** Técnicas eficazes de engenharia de prompts incluem prompts single shot ou few shot, que contêm um ou mais exemplos que demonstram a qualidade de saída desejada.  
   **Referência:** [AWS - Customize Prompt Engineering](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/jumpstart-foundation-models-customize-prompt-engineering.html)

6. **Quais estratégias ajudam a mitigar alucinações nas respostas geradas por um grande modelo de linguagem (LLM)? (Selecione DUAS.)**  
   **R1:** Soluções de RAG podem reduzir as alucinações ao enriquecer o prompt com informações contextuais de uma fonte de dados confiável.  
   **R2:** Instruções claras orientam a fase de geração com comportamentos esperados em situações de incerteza.  
   **Referências:**  
   - [AWS - Customize RAG](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/jumpstart-foundation-models-customize-rag.html)  
   - [AWS - Prompt Engineering](https://aws.amazon.com/what-is/prompt-engineering/)

7. **Quais fatores podem afetar a latência da invocação de um grande modelo de linguagem (LLM)? (Selecione DUAS.)**  
   **R1:** O número de tokens no prompt de entrada, pois maior quantidade exige mais processamento.  
   **R2:** O número de tokens na resposta, já que cada token é gerado individualmente.  
   **Referência:** [AWS - Bedrock Inference](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/inference.html)

8. **Qual técnica de ML ajudará uma empresa a usar dados não rotulados para treinar um modelo e aprender linguagem específica de domínio?**  
   **R:** O pré-treinamento contínuo melhora o desempenho ao permitir que o modelo aprenda conhecimentos específicos de um domínio.  
   **Referência:** [AWS - Custom Models](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/custom-models.html)

9. **Uma empresa quer criar um chatbot que interaja com clientes usando linguagem natural. Qual serviço da AWS atende a esses requisitos?**  
   **R:** O Amazon Lex é um serviço gerenciado que cria bots de IA conversacional sem exigir codificação personalizada.  
   **Referência:** [AWS - What is Amazon Lex](https://docs.aws.amazon.com/pt_br/lexv2/latest/dg/what-is.html)

10. **Uma empresa precisa melhorar o formato das respostas de um FM. Qual técnica atende a esses requisitos de forma mais econômica?**  
    **R:** A engenharia de prompts ajuda a melhorar o formato das respostas sem necessidade de recursos adicionais.  
    **Referência:** [AWS - What is Prompt Engineering](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/what-is-prompt-engineering.html)

11. **Uma empresa quer uma solução de IA generativa para escrever rascunhos de documentos. Qual é o PRIMEIRO passo?**  
    **R:** Selecionar o FM mais adequado para o caso de uso.  
    **Referência:** [AWS - Key Definitions](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/key-definitions.html)

12. **Quais são os casos de uso para modelos de IA generativa? (Selecione QUATRO.)**  
    **R1:** Criar traduções com processamento de imagem.  
    **R2:** Prever a taxa de rotatividade de clientes.  
    **R3:** Criar imagens para campanhas de marketing.  
    **R4:** Análise de sentimentos em textos.  
    **Referência:** [AWS - Generative AI](https://aws.amazon.com/what-is/generative-ai/)

13. **Uma empresa está desenvolvendo um sistema para analisar documentos PDF e fornecer pesquisa semântica. Quais serviços AWS atenderão a esses requisitos? (Selecione DUAS.)**  
    **R1:** Amazon Textract para extrair texto de PDFs.  
    **R2:** Amazon Rekognition para análise de imagens.  
    **Referências:**  
    - [AWS - What is Textract](https://docs.aws.amazon.com/pt_br/textract/latest/dg/what-is.html)  
    - [AWS - What is Rekognition](https://docs.aws.amazon.com/pt_br/rekognition/latest/dg/what-is.html)

14. **Quais são as etapas do Amazon SageMaker Pipelines? (Selecione QUATRO.)**  
    **R1:** ClarifyCheck - Identificar vieses no modelo.  
    **R2:** Processamento - Aplicar engenharia de recursos.  
    **R3:** Treinamento - Desenvolver um modelo.  
    **R4:** Ajuste - Otimizar hiperparâmetros.  
    **Referências:**  
    - [AWS - SageMaker Pipelines](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/pipelines.html)  
    - [AWS - Build and Manage Steps](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/build-and-manage-steps.html)

15. **Qual métrica pode avaliar o desempenho de um FM no contexto de resumo de texto?**  
    **R:** ROUGE-N avalia a qualidade dos resumos ao comparar sobreposições de n-gramas entre o resumo gerado e os resumos de referência.  
    **Referência:** [AWS - Evaluate Foundation Models](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/clarify-foundation-model-evaluate-overview.html)

 # Domínio 3: Aplicações de modelos de base

### Perguntas e Respostas - Domínio 3

1. **Qual é o objetivo principal da IA generativa?**  
   **R:** Criar conteúdo, como imagens, textos, músicas ou conversas.  
   **Referência:** [AWS Generative AI](https://aws.amazon.com/what-is/generative-ai/)

2. **Uma empresa quer usar um LLM para aprender a linguagem específica de seu domínio. Qual solução atende a esses requisitos pelo menor custo operacional indireto?**  
   **R:** Pré-treinamento contínuo melhora o desempenho do modelo ao fornecer dados não rotulados para aprendizado de um domínio específico.  
   **Referência:** [AWS Bedrock Custom Models](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/custom-models.html)

3. **Qual técnica de ML pode ajudar uma empresa a incorporar terminologia específica do setor?**  
   **R:** Pré-treinamento contínuo de FMs usando grandes conjuntos de dados não rotulados do setor.  
   **Referência:** [AWS Bedrock Custom Models](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/custom-models.html)

4. **Qual é o propósito de usar incorporações nesse contexto?**  
   **R:** Representações vetoriais capturam relações semânticas, permitindo que o modelo entenda e gere textos coerentes e significativos.  
   **Referência:** [Transformers na AI](https://aws.amazon.com/what-is/transformers-in-artificial-intelligence/)

5. **Qual é a saída de um modelo de incorporação invocado com uma frase?**  
   **R:** Uma matriz de valores numéricos.  
   **Referência:**  
   - [Titan MultiEmb Models](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/titan-multiemb-models.html)  
   - [Embeddings em ML](https://aws.amazon.com/what-is/embeddings-in-machine-learning/)

6. **Qual métrica pode avaliar o desempenho do modelo de base (FM) no contexto de resumo de texto?**  
   **R:** ROUGE-N, que avalia a qualidade do texto comparando n-gramas do resumo gerado com o de referência.  
   **Referência:** [AWS SageMaker Evaluate Overview](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/clarify-foundation-model-evaluate-overview.html)

7. **Qual métrica deve ser usada para avaliar respostas de um chatbot em relação a especialistas?**  
   **R:** BERTScore, que mede a similaridade semântica entre textos.  
   **Referência:** [AWS SageMaker Evaluate Overview](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/clarify-foundation-model-evaluate-overview.html)

8. **Quais fatores podem afetar a latência da invocação de um grande modelo de linguagem (LLM)?**  
   **R:**  
   - O número de tokens no prompt de entrada.  
   - O número de tokens gerados na saída.  
   **Referência:** [AWS Bedrock Inference](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/inference.html)

9. **Qual técnica melhorará o desempenho de um FM em problemas matemáticos com explicações passo a passo?**  
   **R:** A técnica de cadeia de pensamento (chain of thought), que divide questões complexas em partes menores.  
   **Referência:** [Prompt Engineering](https://aws.amazon.com/what-is/prompt-engineering/)

10. **Qual solução fornece o maior benefício de segurança contra ataques de injeção de prompts?**  
    **R:** Adicionar instruções ao modelo de prompt relacionadas à injeção de prompts.  
    **Referência:** [LLM Prompt Engineering Best Practices](https://docs.aws.amazon.com/pt_br/prescriptive-guidance/latest/llm-prompt-engineering-best-practices/common-attacks.html)

11. **Qual é o objetivo principal do uso de modelos de prompt na engenharia de prompts?**  
    **R:** Garantir consistência e aumentar o desempenho por meio de formatos predefinidos.  
    **Referência:** [Prompt Templates](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/prompt-templates-and-examples.html)

12. **Qual técnica aprimorará o formato das respostas de FM da forma mais econômica?**  
    **R:** Engenharia de prompts, que não exige recursos adicionais.  
    **Referência:** [Prompt Engineering](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/what-is-prompt-engineering.html)

13. **Quais estratégias ajudam a mitigar alucinações nas respostas de LLMs?**  
    **R:**  
    - Uso de RAG (Geração Aumentada por Recuperação).  
    - Criação de prompts claros e assertivos.  
    **Referência:**  
    - [SageMaker RAG](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/jumpstart-foundation-models-customize-rag.html)  
    - [Prompt Engineering](https://aws.amazon.com/what-is/prompt-engineering/)

14. **Qual técnica pode melhorar a qualidade de saídas inconsistentes de um modelo de base?**  
    **R:** Prompts "single-shot" ou "few-shot", que contêm exemplos curados de alta qualidade.  
    **Referência:** [Prompt Engineering](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/jumpstart-foundation-models-customize-prompt-engineering.html)

15. **Qual serviço AWS pode ser usado para criar uma aplicação que resuma documentos PDF sem exigir codificação?**  
    **R:** SageMaker Canvas.  
    **Referência:**  
    - [SageMaker Ready-to-Use Models](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/canvas-ready-to-use-models.html)  
    - [SageMaker FM Chat](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/canvas-fm-chat.html)

16. **Qual é a primeira etapa ao usar o Amazon Bedrock para criar rascunhos de documentos?**  
    **R:** Selecionar o modelo de base (FM) mais adequado para a geração de texto.  
    **Referência:** [Bedrock Key Definitions](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/key-definitions.html)

17. **Qual técnica classifica as melhorias no FM do mais ao menos econômico?**  
    **R:**  
    1. Engenharia de prompts.  
    2. Geração aumentada via recuperação (RAG).  
    3. Ajuste fino baseado em instruções.  
    4. Ajuste fino de adaptação de domínios.  
    **Referência:**  
    - [Prompt Engineering](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/what-is-prompt-engineering.html)  
    - [SageMaker RAG](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/jumpstart-foundation-models-customize-rag.html)

18. **Qual serviço AWS é mais indicado para criar um chatbot multiturno?**  
    **R:** Ajuste fino baseado em instruções no SageMaker JumpStart.  
    **Referência:** [SageMaker JumpStart](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/jumpstart-foundation-models-fine-tuning-instruction-based.html)

# Domínio 4: Diretrizes de IA responsável


**1. Uma empresa de serviços financeiros está desenvolvendo um modelo de ML que prevê a elegibilidade de empréstimo aos clientes. Ela quer uma solução capaz de identificar vieses nos dados de treinamento e nas previsões do modelo.**  
**Resposta:** O SageMaker Clarify é um serviço que pode detectar vieses nos dados de treinamento e modelar previsões. Você pode usar o SageMaker Clarify para fornecer informações sobre as decisões do modelo. Portanto, o SageMaker Clarify é uma solução adequada para desenvolver sistemas de IA responsáveis e imparciais.  
**Referência:** [AWS SageMaker Clarify](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/clarify-configure-processing-jobs.html)

**2. Uma empresa de serviços financeiros passou por uma expansão global recentemente e agora quer criar uma aplicação de chat assistida por IA para escalar a capacidade de atendimento ao cliente. A empresa está sujeita a vários regulamentos e frameworks de conformidade. Ela precisa incorporar princípios de IA responsável na solução. Quais abordagens se alinham aos princípios de IA responsável?**  
**Resposta 1:** A privacidade e a segurança dos dados são um componente da IA responsável. A edição de PII por meio da remoção ou ofuscação evita o risco de que as previsões do modelo vazem informações sobre os clientes no conjunto de dados de treinamento.  
**Referência:** [AWS Comprehend](https://docs.aws.amazon.com/pt_br/comprehend/latest/dg/pii.html)  

**Resposta 2:** A imparcialidade é um componente da IA responsável. No ML, os vieses incluem desequilíbrios nos dados baseados em grupos ou diferenças no desempenho do modelo entre os grupos.  
**Referência:**  
- [AWS SageMaker Clarify](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/clarify-model-monitor-bias-drift.html)  
- [AWS Responsible AI](https://aws.amazon.com/pt/ai/responsible-ai/)

**3. Qual é o objetivo principal do uso de modelos de prompt na engenharia de prompts?**  
**Resposta:** Os modelos de prompt são formatos predefinidos que podem ser usados para padronizar entradas e saídas de modelos de IA. Eles garantem consistência e aumentam o desempenho do modelo.  
**Referência:** [AWS Bedrock Prompt Templates](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/prompt-templates-and-examples.html)

**4. Uma empresa aplica um design centrado no ser humano em sua aplicação de IA usando o aprendizado por reforço com feedback humano (RLHF). Para melhorar um grande modelo de linguagem (LLM) que ela está desenvolvendo, a empresa quer criar um conjunto de dados de treinamento confiável incorporando feedback humano. Qual solução atende a esses requisitos?**  
**Resposta:** O SageMaker Ground Truth usa feedback humano para criar conjuntos de dados rotulados. Ao incorporar rótulos verificados por humanos e supervisão humana, o SageMaker Ground Truth ajuda a alinhar mais estreitamente o processo de tomada de decisão da IA aos contextos do mundo real.  
**Referência:**  
- [AWS SageMaker Ground Truth](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/sms.html)  
- [AWS RLHF](https://aws.amazon.com/what-is/reinforcement-learning-from-human-feedback/)

**5. Quais estratégias ajudam a mitigar alucinações nas respostas geradas por um grande modelo de linguagem (LLM)?**  
**Resposta 1:** As soluções de RAG podem reduzir as alucinações ao enriquecer o prompt com informações contextuais que são recuperadas de uma fonte de dados confiável.  
**Referência:** [AWS SageMaker RAG](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/jumpstart-foundation-models-customize-rag.html)  

**Resposta 2:** Instruções claras são importantes quando você elabora um prompt. É possível ajudar a reduzir as alucinações orientando a fase de geração com instruções assertivas.  
**Referência:** [AWS Prompt Engineering](https://aws.amazon.com/what-is/prompt-engineering/)

**6. Uma empresa quer criar um chatbot que possa interagir com os clientes usando linguagem natural. Ela quer implementar uma solução gerenciada. Qual serviço da AWS atende a esses requisitos?**  
**Resposta:** O Amazon Lex é um serviço gerenciado que pode ser usado para criar bots usando IA conversacional. Ele não exige nenhuma codificação personalizada e está pronto para uso.  
**Referência:** [Amazon Lex](https://docs.aws.amazon.com/pt_br/lexv2/latest/dg/what-is.html)

**7. Uma empresa quer desenvolver uma solução interna que resuma vários e-mails e extensas notas de reunião. Ela quer usar modelos de base (FMs) no Amazon Bedrock para a solução. Qual propriedade do modelo deve ser considerada PRIMEIRO ao escolher um modelo?**  
**Resposta:** A janela de contexto é uma propriedade do modelo que descreve o número de tokens que ele pode aceitar no contexto.  
**Referência:**  
- [AWS Bedrock Models](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/models-supported.html)  
- [Inference Parameters](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/inference-parameters.html)

**8. Quais são as desvantagens ou limitações de trabalhar com a IA generativa?**  
**Resposta 1:** A alucinação ocorre quando um grande modelo de linguagem (LLM) gera informações falsas.  
**Referência:** [AWS Q Business Concepts](https://docs.aws.amazon.com/pt_br/amazonq/latest/qbusiness-ug/concepts-terms.html)  

**Resposta 2:** Os grandes modelos de linguagem (LLMs) são pré-treinados em conjuntos de dados estáticos em que os dados têm um limite.  
**Referência:** [AWS RAG](https://aws.amazon.com/what-is/retrieval-augmented-generation/)

**9. Uma empresa quer desenvolver uma aplicação que forneça explicações passo a passo para resolver problemas. Qual técnica melhorará de maneira mais confiável o desempenho do FM?**  
**Resposta:** A cadeia de pensamento é uma técnica de engenharia de prompts que divide uma questão complexa em partes menores.  
**Referência:** [AWS Prompt Engineering](https://aws.amazon.com/what-is/prompt-engineering/)

# Domínio 5: Segurança, conformidade e governança para soluções de IA

1. **Uma empresa de serviços financeiros está desenvolvendo um modelo de ML que prevê a elegibilidade de empréstimo aos clientes. Ela quer uma solução capaz de identificar vieses nos dados de treinamento e nas previsões do modelo.**  
   **R:** O SageMaker Clarify é um serviço que pode detectar vieses nos dados de treinamento e modelar previsões. Ele fornece informações sobre as decisões do modelo, ajudando a desenvolver sistemas de IA responsáveis e imparciais.  
   **Referência:** [AWS SageMaker Clarify](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/clarify-configure-processing-jobs.html)

2. **Uma empresa de comércio eletrônico pretende implantar um sistema de recomendação de IA que usa dados de clientes. Os dados são armazenados no Amazon S3. A empresa deseja cumprir os regulamentos de governança e privacidade de dados para identificar e proteger informações de identificação pessoal (PII).**  
   **R:** O Amazon Macie usa ML para descobrir, monitorar e proteger dados sigilosos no Amazon S3, permitindo identificar e proteger PII, além de cumprir regulamentos de privacidade.  
   **Referência:** [AWS Macie](https://docs.aws.amazon.com/pt_br/macie/latest/user/what-is-macie.html)

3. **Uma empresa de saúde deve cumprir uma política de conformidade. A política estabelece que os dados armazenados no Amazon S3 não devem atravessar a internet ao serem transferidos a uma instância de ML do Amazon EC2 para fins de treinamento de modelos.**  
   **R:** Um endpoint de gateway do Amazon S3 fornece conectividade segura entre uma VPC e o Amazon S3, garantindo que os dados não atravessem a internet.  
   **Referência:** [AWS VPC Gateway Endpoint](https://docs.aws.amazon.com/pt_br/vpc/latest/privatelink/vpc-endpoints-s3.html)

4. **Uma empresa precisa fornecer informações sobre seus modelos de ML personalizados para fins de auditoria. As informações precisam incluir detalhes sobre o treinamento e o desempenho do modelo.**  
   **R:** Os SageMaker Model Cards documentam informações como detalhes de treinamento, métricas de avaliação e desempenho dos modelos, atendendo aos requisitos de auditoria.  
   **Referência:** [AWS SageMaker Model Cards](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/model-cards.html)

5. **Uma empresa hospeda vários aplicativos web em instâncias do Amazon EC2. Os aplicativos web precisam fazer chamadas para modelos de base (FMs) no Amazon Bedrock. Para fins de auditoria, a empresa quer usar um mecanismo que registre automaticamente todas as chamadas feitas pelos aplicativos web para o Amazon Bedrock. O mecanismo deve capturar o usuário e o perfil para cada chamada de API e os timestamps das chamadas de inferência.**  
   **R:** O AWS CloudTrail fornece auditoria de risco ao capturar chamadas de API, incluindo quem realizou as chamadas e os timestamps relevantes.  
   **Referência:**  
   - [AWS CloudTrail](https://docs.aws.amazon.com/pt_br/awscloudtrail/latest/userguide/cloudtrail-user-guide.html)  
   - [AWS Bedrock Logging](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/logging-using-cloudtrail.html)

6. **Uma empresa precisa de documentos sobre segurança e conformidade na AWS.**  
   **R:** O AWS Artifact concede acesso sob demanda à documentação de segurança e conformidade da AWS.  
   **Referência:** [AWS Artifact](https://docs.aws.amazon.com/pt_br/artifact/latest/ug/what-is-aws-artifact.html)

7. **Uma empresa de serviços financeiros passou por uma expansão global recentemente e agora quer criar uma aplicação de chat assistida por IA para escalar a capacidade de atendimento ao cliente. A empresa está sujeita a vários regulamentos e frameworks de conformidade. Ela precisa incorporar princípios de IA responsável na solução.**  
   **R:**  
   - A **privacidade e segurança dos dados** são cruciais. Políticas de ofuscação de PII evitam vazamento de informações em respostas de modelos.  
   - A **imparcialidade** garante que os modelos sejam consistentes em diferentes grupos demográficos, evitando vieses nos dados de treinamento ou previsões.  
   **Referência:**  
   - [AWS Comprehend PII](https://docs.aws.amazon.com/pt_br/comprehend/latest/dg/pii.html)  
   - [AWS Responsible AI](https://aws.amazon.com/pt/ai/responsible-ai/)

8. **Uma empresa quer criar um assistente virtual para funcionários internos. O assistente virtual deve responder a perguntas técnicas com base apenas na documentação de engenharia proprietária da empresa. A empresa quer minimizar as alucinações dos modelos.**  
   **R:** A geração aumentada de recuperação (RAG) reduz alucinações ao usar informações contextuais de fontes confiáveis, com menores custos operacionais que ajustes de modelos.  
   **Referência:** [AWS SageMaker RAG](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/jumpstart-foundation-models-customize-rag.html)