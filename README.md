# 🎯 Ecossistema de Trilha de Revisão Adaptativa

> **Projeto Prático Aplicado desenvolvido como trabalho principal de Especialização.**  
> Uma solução EdTech baseada em Inteligência Artificial Generativa que integra microlearning, repetição espaçada e avaliação automatizada por competências.

---

## 💻 Sobre o Projeto

O **Ecossistema de Trilha de Revisão Adaptativa** é uma ferramenta projetada para potencializar a retenção de conhecimento de estudantes. O sistema conecta-se diretamente à API local do **Anki** para extrair metadados e flashcards do usuário e, por meio de engenharia de prompt avançada utilizando o **Google Gemini**, gera dinamicamente **10 questões inéditas e personalizadas** focadas na revisão, fixação de conteúdo e diagnóstico de lacunas de aprendizagem.

### 🚀 Principais Funcionalidades

1. **Extração Inteligente de Dados:** Integração com o ecossistema do Anki via plugin para leitura direta e segura de baralhos, sem a necessidade de downloads manuais de arquivos.
2. **Geração Automatizada com IA (Gemini):** Consumo dos metadados e conteúdos das cartas para estruturação de simulados dinâmicos e adaptativos de 10 questões através do Google AI Studio.
3. **Engenharia Pedagógica Aplicada:** Questões calibradas utilizando conceitos da **Taxonomia de Bloom** para validar diferentes níveis de aquisição e profundidade de novas habilidades.

---

## 📸 Demonstração da Interface (UI/UX)

O fluxo do sistema foi desenhado prezando pela simplicidade e usabilidade da jornada do estudante (LX/UX), dividido em etapas lógicas e intuitivas:

### Passo 1: Integração e Extração de Dados do Anki
O sistema realiza a leitura local dos baralhos ativos de forma automatizada por meio do ecossistema do AnkiConnect.

![Passo 1 - Extração de Dados do Anki](image_0oAsFq.png)

### Passo 2: Conexão com o Gemini e Geração da Trilha Adaptativa
O usuário insere sua chave de API com segurança para acionar os prompts estruturados e gerar o bloco de 10 questões inéditas baseadas no conteúdo selecionado.

![Passo 2 - Conexão com o Gemini](image_-MmdT5.png)

---

## 🛠️ Competências Técnicas e Pedagógicas Demonstradas

Este projeto simula o escopo completo de desenvolvimento de produtos digitais educacionais em grande escala, englobando as seguintes entregas essenciais:

* **Desenho Educacional Digital & IA:** Transformação de materiais base fragmentados (flashcards) em objetos de aprendizagem interativos e complexos utilizando IA Generativa (GenAI).
* **Engenharia de Prompt Avançada:** Modelagem e refinamento de instruções para guiar o comportamento do modelo Gemini, mitigando alucinações e garantindo o rigor conceitual das avaliações.
* **Avaliação por Competências:** Aplicação prática de metodologias ativas e taxonomias educacionais para estruturar feedbacks e perguntas diagnósticas personalizadas.
* **Garantia de Qualidade (QA):** Arquitetura focada no tratamento e consistência de dados gerados por modelos de linguagem (LLMs) voltados à educação.
* **UX/LX e Storyboarding:** Planejamento detalhado da esteira de passos da aplicação para entregar uma interface fluida, enxuta e focada na autonomia do estudante.

---

## ⚙️ Como Executar o Projeto Localmente

### Pré-requisitos
* Ter o **Anki** instalado e aberto no computador.
* Ter o add-on **AnkiConnect** configurado no seu perfil do Anki.
* Uma chave de API (API Key) obtida gratuitamente no [Google AI Studio](https://google.com).

### Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com
   ```
2. Instale as dependências necessárias *(Ajustar conforme as tecnologias do seu projeto, ex: Python, Node.js, Streamlit, etc.)*:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute a aplicação:
   ```bash
   streamlit run app.py
   ```


