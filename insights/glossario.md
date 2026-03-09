# 📖 Glossário — GenAI & Finanças
### Termos essenciais para entender IA Generativa aplicada ao setor financeiro

> Referência rápida dos conceitos que aparecem nas fontes do notebook e nas discussões do mercado.
> Organizado do mais básico ao mais avançado.

---

## 🔤 A

**Agente de IA (AI Agent)**
Sistema baseado em LLM capaz de perceber o ambiente, tomar decisões e executar ações de forma autônoma — sem intervenção humana a cada passo. Em finanças, agentes podem executar pesquisas, analisar dados e gerar relatórios de forma end-to-end. Diferente de um chatbot, que apenas responde; um agente *age*.

**Análise de Sentimento**
Técnica de processamento de linguagem natural (NLP) que identifica o tom emocional de um texto — positivo, negativo ou neutro. Em finanças, é usada para analisar earnings calls, notícias e relatórios de analistas em tempo real, identificando sinais de confiança ou preocupação na fala de executivos.

**AutoML**
Machine Learning automatizado — ferramentas que automatizam etapas do pipeline de ciência de dados como seleção de features, escolha de algoritmo e ajuste de hiperparâmetros. Reduz o tempo de desenvolvimento de modelos preditivos, mas ainda requer profissional para interpretar e validar os resultados.

---

## 🔤 B

**Benchmark**
Teste padronizado usado para comparar o desempenho de modelos de IA em tarefas específicas. O paper do FinGPT usa benchmarks para demonstrar que o modelo especializado supera o GPT-4 em tarefas financeiras como previsão de sentimento de ações.

**Bias (Viés)**
Distorção sistemática nos outputs de um modelo de IA causada por desequilíbrios nos dados de treinamento. Em crédito, um modelo com bias pode sistematicamente negar crédito a grupos populacionais específicos — mesmo sem regra explícita para isso. A LGPD e a Resolução BCB 4.557 exigem que bancos monitorem e mitiguem bias em modelos de decisão.

---

## 🔤 C

**Credit Scoring Alternativo**
Modelos de análise de crédito que utilizam dados não tradicionais — comportamento de pagamento de contas de luz e água, histórico de transações PIX, padrões de uso de aplicativos — para avaliar o risco de inadimplência de pessoas sem histórico bancário formal.

**Circuit Breaker**
Mecanismo automático que interrompe negociações em bolsa quando os preços caem ou sobem além de um limite predefinido. O FMI alerta que com IA mais sofisticada no trading, os circuit breakers existentes podem precisar ser recalibrados para reagir à velocidade dos modelos.

---

## 🔤 D

**Deepfake**
Conteúdo sintético (vídeo, áudio, imagem) gerado por IA que imita de forma convincente uma pessoa real. Em finanças, deepfakes são usados em golpes: o caso mais documentado envolveu um funcionário que transferiu US$ 25 milhões após videochamada com um "CFO" gerado por IA. Houve aumento de 223% no uso de ferramentas de deepfake para fraude financeira no primeiro semestre de 2024 (Accenture/WEF).

**Dados Alternativos**
Informações não convencionais usadas para análise financeira — dados de satélite, tráfego de lojas, posts em redes sociais, dados de geolocalização, histórico de pagamentos de contas de serviços. Em crédito, permitem avaliar tomadores sem histórico bancário. O Open Finance brasileiro é um habilitador de dados alternativos.

---

## 🔤 E

**Earnings Call**
Reunião trimestral onde a diretoria de uma empresa pública apresenta resultados financeiros e responde perguntas de analistas e investidores. O tom e o conteúdo dessas chamadas contêm informação valiosa além dos números — e LLMs conseguem extrair sinais semânticos que humanos podem perder.

**Embedding**
Representação numérica (vetor) de texto, imagem ou dado que captura seu significado semântico em um espaço matemático. Documentos financeiros similares ficam próximos no espaço de embeddings. É a tecnologia base para busca semântica e RAG.

**Explainability (Explicabilidade)**
Capacidade de um modelo de IA de justificar suas decisões em linguagem compreensível por humanos. No setor financeiro, é requisito regulatório — a Resolução BCB 4.557 exige que bancos consigam explicar e auditar decisões de crédito tomadas por modelos.

---

## 🔤 F

**Fine-tuning**
Processo de ajustar um LLM pré-treinado para um domínio específico, treinando-o com dados especializados. O FinGPT foi criado via fine-tuning de modelos base com dados financeiros — notícias de mercado, earnings reports, dados de preço. Mais eficiente que treinar do zero.

**FinGPT**
LLM open-source desenvolvido pela Columbia University especializado no domínio financeiro. Disponível no GitHub e HuggingFace. Supera GPT-4 em benchmarks financeiros específicos, com custo de operação significativamente menor. Referência: arXiv 2306.06031.

**Foundation Model**
Modelo de IA de grande porte treinado em volumes massivos de dados que pode ser adaptado para múltiplas tarefas. GPT-4, Claude, Gemini e LLaMA são foundation models. O FinGPT é um foundation model adaptado (fine-tuned) para finanças.

---

## 🔤 G

**GenAI (IA Generativa)**
Categoria de IA capaz de gerar conteúdo novo — texto, imagem, código, áudio — a partir de padrões aprendidos em dados. Diferente da IA discriminativa (que classifica ou prevê), a GenAI cria. Em finanças, gera relatórios, resume documentos, redige contratos e personaliza comunicações.

**Governança de IA**
Conjunto de políticas, processos e controles que garantem que sistemas de IA sejam usados de forma ética, auditável e em conformidade regulatória. Inclui monitoramento de bias, rastreabilidade de decisões e gestão de riscos de modelo. Componente crescente de exigência regulatória global.

---

## 🔤 H

**Hallucination**
Fenômeno em que um LLM gera informações factualmente incorretas com aparente confiança. O modelo "inventa" dados, cita fontes inexistentes ou mistura contextos diferentes. Em finanças, uma hallucination pode resultar em relatório com dados falsos de mercado ou análise de risco baseada em informação fabricada — com consequências graves.

**Hiperparâmetro**
Configuração de um modelo de IA definida antes do treinamento — como número de camadas de uma rede neural, taxa de aprendizado ou tamanho do batch. O ajuste de hiperparâmetros (hyperparameter tuning) impacta diretamente o desempenho do modelo.

---

## 🔤 K

**KYC (Know Your Customer)**
Processo regulatório de identificação e verificação de identidade de clientes. GenAI está automatizando grande parte do KYC — análise de documentos, detecção de inconsistências, verificação de identidade via biometria — reduzindo de horas para segundos o processo de onboarding bancário.

---

## 🔤 L

**LGPD (Lei Geral de Proteção de Dados)**
Legislação brasileira (Lei 13.709/2018) que regula o tratamento de dados pessoais. Para uso de GenAI em finanças, a LGPD exige base legal para processamento de dados, consentimento explícito quando necessário e direitos do titular (acesso, correção, exclusão).

**LLM (Large Language Model)**
Modelo de linguagem de grande escala treinado em volumes massivos de texto. A arquitetura transformer é a base da maioria dos LLMs modernos. GPT-4, Claude, Gemini e LLaMA são exemplos. Em finanças, LLMs processam documentos não estruturados que antes exigiam horas de trabalho humano.

---

## 🔤 M

**MLOps**
Conjunto de práticas para colocar modelos de machine learning em produção e mantê-los operando com qualidade ao longo do tempo. Inclui versionamento de modelos, monitoramento de drift, testes automatizados e pipelines de retreinamento. Essencial para qualquer iniciativa de IA em produção no setor financeiro.

**Model Risk Management (MRM)**
Disciplina de gestão de riscos focada em identificar, mensurar e mitigar riscos associados ao uso de modelos quantitativos em decisões financeiras. A Resolução BCB 4.557 define o framework de MRM para bancos brasileiros — e GenAI está expandindo o escopo do que precisa ser gerenciado.

---

## 🔤 N

**NLP (Natural Language Processing)**
Campo da IA focado em fazer computadores compreenderem e gerarem linguagem humana. É a base técnica dos LLMs. Em finanças, NLP é usado para análise de sentimento, extração de informação de contratos, classificação de chamados e geração de relatórios.

---

## 🔤 O

**Open Finance**
Iniciativa regulatória do Banco Central do Brasil que permite o compartilhamento padronizado de dados financeiros entre instituições, com consentimento do cliente. Abre camadas de dados alternativos para análise de crédito e personalização de produtos — e é um dos principais habilitadores de GenAI no mercado financeiro brasileiro.

---

## 🔤 P

**Prompt Engineering**
Arte e ciência de formular instruções (prompts) para LLMs de forma a obter outputs mais precisos, relevantes e confiáveis. Em contextos financeiros, um prompt bem construído pode fazer a diferença entre uma análise de risco útil e uma cheia de hallucinations.

**PIX**
Sistema de pagamentos instantâneos do Banco Central do Brasil, lançado em 2020. Com mais de 42 bilhões de transações em 2023, gera um volume massivo de dados de comportamento financeiro que pode ser usado em modelos de análise de crédito alternativo e detecção de fraude — com consentimento do usuário via Open Finance.

---

## 🔤 R

**RAG (Retrieval-Augmented Generation)**
Arquitetura que combina um LLM com uma base de dados externa. Antes de responder, o modelo busca informações relevantes na base (retrieve), usa essas informações como contexto e então gera a resposta (generate). Reduz drasticamente o risco de hallucination e permite que o modelo responda com dados atualizados. Em finanças, é a solução para conectar LLMs a bases de dados proprietárias e regulatórias.

**Resolução BCB 4.557**
Norma do Banco Central do Brasil que regula o gerenciamento de riscos de modelos em instituições financeiras. Exige que bancos documentem, testem e auditem modelos usados em decisões de crédito e risco. Com a adoção de GenAI, o escopo dessa resolução se amplia significativamente.

**RegTech**
Tecnologia aplicada a processos de compliance e regulação financeira. GenAI está transformando o RegTech ao automatizar monitoramento de conformidade, geração de relatórios regulatórios e análise de mudanças em normas — tarefas que antes exigiam grandes equipes de advogados e compliance officers.

---

## 🔤 S

**Score de Crédito**
Pontuação numérica que representa a probabilidade de um tomador pagar suas dívidas. Modelos tradicionais (Serasa, SPC) usam dados históricos estruturados. Modelos alternativos com GenAI incorporam dados comportamentais, padrões de pagamento e informações do Open Finance para avaliar perfis sem histórico formal.

**SLM (Small Language Model)**
Versão menor e mais especializada de um LLM, treinada para tarefas específicas. Mais eficiente computacionalmente, mais barata de operar e mais fácil de auditar. O WEF (2025) aponta SLMs como tendência crescente em bancos que precisam de modelos auditáveis para uso regulado.

---

## 🔤 T

**Transformer**
Arquitetura de rede neural introduzida em 2017 ("Attention is All You Need") que é a base de praticamente todos os LLMs modernos. O mecanismo de "atenção" permite que o modelo entenda relações contextuais entre palavras em documentos longos — crucial para análise de contratos e relatórios financeiros extensos.

**Token**
Unidade básica de texto processada por um LLM — pode ser uma palavra, parte de uma palavra ou um caractere. O custo de uso de APIs de LLM é calculado por tokens. Em documentos financeiros extensos, o gerenciamento eficiente de tokens é importante para controle de custos.

---

## 🔤 V

**Vetor (Vector)**
Representação matemática de dados em um espaço multidimensional. Embeddings são vetores. Bancos de dados vetoriais (como Pinecone, Weaviate, pgvector) armazenam e permitem busca eficiente por similaridade semântica — componente essencial de arquiteturas RAG para finanças.

---

## 🔤 Z

**Zero-shot Learning**
Capacidade de um LLM de executar uma tarefa para a qual não foi explicitamente treinado, apenas com base na instrução em linguagem natural. Em finanças, permite adaptar um modelo para novas tarefas sem retreinamento — como analisar um novo tipo de documento regulatório com apenas um prompt bem estruturado.

---

## 📌 Siglas de Referência Rápida

| Sigla | Significado |
|-------|-------------|
| AI | Artificial Intelligence (Inteligência Artificial) |
| BCB | Banco Central do Brasil |
| ETL | Extract, Transform, Load |
| FMI | Fundo Monetário Internacional |
| GenAI | Generative AI (IA Generativa) |
| KYC | Know Your Customer |
| LGPD | Lei Geral de Proteção de Dados |
| LLM | Large Language Model |
| MEI | Microempreendedor Individual |
| MLOps | Machine Learning Operations |
| MRM | Model Risk Management |
| NLP | Natural Language Processing |
| RAG | Retrieval-Augmented Generation |
| RegTech | Regulatory Technology |
| SLM | Small Language Model |
| WEF | World Economic Forum |

---

*Glossário desenvolvido como parte do portfólio do Bootcamp de GenAI e Dados — Bradesco 2025*
*Baseado nas fontes: IBM · arXiv FinGPT · Deloitte · FMI · WEF*
