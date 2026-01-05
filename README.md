# Inteligência Artificial Generativa (IA Generativa)

## Conceito
A **Inteligência Artificial Generativa** é um tipo de IA que **cria conteúdo novo a partir de dados existentes**, como textos, imagens, áudios ou códigos, aprendendo padrões e estruturas desses dados.

---

## LLM (Large Language Models)
- Modelos de linguagem treinados com **grandes volumes de texto**.
- Aprendem **probabilidades de palavras e frases** para gerar conteúdo coerente.
- Exemplos: **GPT, LLaMA, Claude**.

---

## Transformers e Tokenização
- **Transformers**: arquitetura de rede neural que entende **contexto global** do texto usando **atenção**.
- **Tokenização**: quebra o texto em **tokens** (palavras, subpalavras ou caracteres) para processamento.
- **Inserção (Embedding)**: cada token é convertido em **vetor numérico** que representa seu significado semântico.

---

## Técnica de Atenção (Attention)
- Permite que o modelo **foco em partes importantes do texto** ao gerar respostas.
- Fundamental para **entender contexto longo e relações entre palavras**.

---

## Copilotos
- Aplicações práticas de IA generativa que **assistem o usuário**.
- Exemplos:
  - **GitHub Copilot**: ajuda a escrever código.
  - **Copilot no Microsoft 365**: ajuda a escrever documentos e e-mails.

---

## Engenharia de Prompts (Prompt Engineering)
- Técnica de **criar instruções ou exemplos claros** para guiar o modelo generativo.
- Bons prompts resultam em **respostas mais precisas e úteis**.
- Exemplo:  
  - `"Resuma este texto em 3 frases principais"`  
  - `"Crie código Python que calcule médias"`  

---

# Guia de Inteligência Artificial e Azure

## 1. Cargas de Trabalho de IA no Azure

### **1.1 Machine Learning (ML)**
- **Definição:** ML é uma subárea da IA que permite que sistemas aprendam padrões a partir de dados para fazer previsões ou decisões sem programação explícita.  
- **Diferença para IA:**  
  - **IA:** campo amplo, engloba qualquer sistema que simula inteligência humana.  
  - **ML:** usa **dados e algoritmos** para aprender e melhorar automaticamente.  
- **Exemplo:** prever preços de casas, recomendação de produtos.  

### **1.2 Visão Computacional**
- Permite que sistemas **interpretem imagens e vídeos**.  
- **Exemplos:** reconhecimento facial, detecção de objetos, análise de imagens médicas.  

### **1.3 Processamento de Linguagem Natural (PLN/NLP)**
- Permite que computadores **entendam, interpretem e gerem linguagem humana**.  
- **Exemplos:** chatbots, análise de sentimentos, tradução automática.  

### **1.4 Inteligência e Documentos**
- Extração de dados e informações de **documentos não estruturados**.  
- **Exemplos:** formulários, PDFs, faturas, contratos.  

### **1.5 Mineração e Conhecimento**
- Transformação de **dados brutos em insights acionáveis**.  
- **Exemplo:** identificar padrões de compra, clusters de clientes.

---

## 2. IA Generativa – Princípios Éticos

1. **Imparcialidade:** evitar vieses nos dados e resultados.  
2. **Confiabilidade e Segurança:** gerar saídas corretas e evitar usos maliciosos.  
3. **Privacidade:** proteger dados sensíveis durante treinamento e inferência.  
4. **Inclusão:** IA acessível para diferentes grupos e habilidades.  
5. **Transparência:** explicar decisões e funcionamento do modelo.  
6. **Responsabilidade:** garantir que humanos possam supervisionar e corrigir a IA.

---

## 3. Fundamentos de Aprendizado de Máquina (ML)

### **3.1 Conceito**
- ML é **ensinar máquinas a aprender padrões de dados** para prever ou classificar novos dados.

### **3.2 Processo**
1. **Treinamento:** o modelo aprende com dados rotulados ou não rotulados.  
2. **Inferência:** o modelo usa o que aprendeu para **prever ou gerar resultados** em novos dados.

### **3.3 Tipos de Aprendizado de Máquina**
- **Supervisionado:** aprende com dados rotulados (ex.: regressão, classificação).  
- **Não supervisionado:** encontra padrões sem rótulos (ex.: clustering).  
- **Reforço:** aprende por **tentativa e erro** com recompensas.  

### **3.4 Treinamento e Avaliação**
- Ajuste de parâmetros do modelo usando dados de treinamento.  
- Avaliação usando dados de teste para medir **precisão, recall, F1-score**.

### **3.5 Aprendizado Profundo (Deep Learning)**
- Baseado em **redes neurais profundas**.  
- Funciona convertendo entradas em **vetores numéricos** e aplicando **cálculos de pesos e ativação**.  
- **Exemplo:** Transformers, CNNs, RNNs.

---

## 4. Azure Machine Learning (Azure ML)

### **4.1 O que é**
- Serviço do Azure que permite **criar, treinar, implantar e monitorar modelos de ML e IA generativa**.  

### **4.2 Como aplicar**
- Criar **workspace** → carregar **datasets** → criar **pipeline** → treinar e avaliar → **implantar modelo** em produção.  
- Suporta **treinamento automatizado (AutoML)** e **ML pipelines**.  

---

## 5. Diferenciação e Exemplos

| Termo                          | O que é / Função                                          | Exemplo                                           |
|--------------------------------|-----------------------------------------------------------|--------------------------------------------------|
| **Aprendizado de Máquina Azure** | Criar e treinar modelos usando Azure ML                  | Previsão de vendas, detecção de fraude           |
| **Serviços de IA do Azure**      | APIs prontas de IA para visão, linguagem, fala e decisão | Azure AI Speech, Language, Vision                |
| **Pesquisa Cognitiva do Azure**  | Pesquisa avançada e mineração de conhecimento            | Azure Cognitive Search: busca inteligente em sites ou documentos |

---



