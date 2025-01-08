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

    **R:** A engenharia de prompts é a técnica mais econômica, pois não requer infraestrutura adicional     e ajusta a entrada para melhorar as respostas.

    **Referência:** [AWS - Engenharia de prompts](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/what-is-prompt-engineering.html)

14. **Uma empresa quer treinar um modelo de IA que minimiza alucinações com base em sua própria documentação. Qual solução atende a esses requisitos?**

    **R:** RAG (Recuperação Aumentada) reduz alucinações ao enriquecer os prompts com informações   específicas e confiáveis da empresa.

    **Referência:** [AWS - RAG](https://docs.aws.amazon.com/pt_br/sagemaker/latest/dg/jumpstart-foundation-models-customize-rag.html)

15. **Qual é o objetivo principal de um modelo de prompt na engenharia de prompts?**

    **R:** Os modelos de prompt padronizam entradas e saídas de IA, garantindo consistência e   melhorando o desempenho do modelo.

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