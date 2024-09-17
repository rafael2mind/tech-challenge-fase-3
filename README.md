# Tech Challenge - FIAP: IA para Devs (Fase 3)

### Grupo 38
- Pedro Vianna Silveira
- Rafael Silva Souza
- Rodrigo de Freitas Ornellas


---

### 🔗 Código Github



https://github.com/rafael2mind/tech-challenge-fase-3


### 🔗 Vídeo de apresentação
https://youtu.be/

---

### 1. Introdução

#### Contexto e Motivação

Nesta fase do Tech Challenge, o foco está em realizar o fine-tuning de um foundation model (como BERT, Llama, Mistral, etc.) utilizando o dataset AmazonTitles-1.3MM. O objetivo é treinar o modelo para responder perguntas dos usuários com base nas descrições de produtos fornecidas no dataset.

O dataset AmazonTitles-1.3MM contém consultas textuais reais de usuários sobre produtos da Amazon, associadas a títulos de produtos e suas respectivas descrições. Com o aumento das interações em plataformas de e-commerce, há uma crescente necessidade de sistemas que consigam entender perguntas dos usuários e gerar respostas relevantes, utilizando descrições detalhadas dos produtos.

Este projeto propõe a construção de um sistema onde, a partir de uma pergunta do usuário sobre um título de produto, o modelo será capaz de gerar uma resposta adequada, utilizando o conhecimento adquirido no processo de fine-tuning com o dataset.


#### Objetivos do Projeto

O principal objetivo deste projeto é realizar o fine-tuning de um modelo de linguagem com o dataset AmazonTitles-1.3MM para permitir que o modelo:

1. Gere respostas baseadas nas descrições dos produtos: A partir de uma pergunta feita pelo usuário sobre o título de um produto, o modelo deverá gerar uma resposta utilizando as descrições presentes no dataset.
2. Melhore a precisão e relevância das respostas: O fine-tuning do modelo deve permitir uma compreensão mais profunda das relações entre o título e a descrição de um produto, resultando em respostas mais informativas e úteis para o usuário.
3. Documente o processo de ajuste fino: Descrever detalhadamente as etapas de pré-processamento de dados, ajuste de hiperparâmetros e qualquer modificação feita ao modelo durante o treinamento.


#### Estrutura do Projeto

O projeto será desenvolvido em várias etapas, conforme detalhado a seguir:

1. **Introdução**:
   - Contextualização do problema.
   - Objetivos do projeto: foco no fine-tuning de um foundation model (como BERT, Llama, Mistral) utilizando o dataset AmazonTitles-1.3MM para gerar respostas baseadas em descrições de produtos.

2. **Descrição do Problema**:
   - Definição do problema: necessidade de sistemas de NLP capazes de gerar respostas baseadas nas descrições de produtos.
   - Importância do problema no contexto de plataformas de e-commerce.
   - Abordagem para a resolução do problema.

3. **Fundamentação Teórica**:
   - Modelos de linguagem (foundation models) como BERT, Llama, Mistral.
   - Fine-tuning: técnica de ajuste fino do modelo para tarefas específicas.
   - Pré-processamento de dados textuais: tokenização, normalização, remoção de stop words.
   - Geração de respostas em NLP.

4. **Metodologia**:
   - **Preparação dos Dados**: Carregamento do dataset AmazonTitles-1.3MM e pré-processamento, incluindo limpeza e criação de prompts.
   - **Seleção e Configuração do Modelo**: Escolha de um modelo adequado (BERT, Llama, etc.) e tokenização dos dados.
   - **Execução do Fine-Tuning**: Configuração de hiperparâmetros, treinamento do modelo e ajustes ao longo do processo.
   - **Avaliação e Validação**: Teste do modelo treinado e comparação com o modelo pré-treinado.

5. **Implementação**:
   - Descrição do ambiente de desenvolvimento: ferramentas como Google Colab, bibliotecas como Transformers, Pandas, NumPy, Matplotlib, TensorFlow ou PyTorch.
   - **Carregamento e Preparação do Dataset**: Código de carregamento, limpeza e tokenização dos dados.
   - **Fine-tuning do Modelo Escolhido**: Execução do ajuste fino e salvamento do modelo treinado.
   - **Geração de Respostas e Testes**: Função para gerar respostas a partir de perguntas, avaliação de métricas como acurácia e F1-score.

6. **Resultados**:
   - Análise comparativa do modelo pré-treinado e fine-tunado.
   - Métricas de avaliação e discussão dos resultados obtidos.
   - Análise qualitativa das respostas geradas pelo modelo.

7. **Conclusão**:
   - Revisão dos objetivos e resultados.
   - Limitações do projeto e sugestões de melhorias para trabalhos futuros.
