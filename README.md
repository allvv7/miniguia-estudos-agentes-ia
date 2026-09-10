# Meu Primeiro Estudo sobre Agentes de IA 🤖

Olá! Este repositório foi criado para registrar o meu aprendizado no desafio prático da **DIO (Digital Innovation One)**, onde explorei o **NotebookLM** da Google para entender o que são e como funcionam os **Agentes de IA**.

---

## 🎯 O que eu quis estudar?

Sempre ouço falar de Inteligência Artificial, mas queria entender a diferença entre um chatbot comum (como o ChatGPT) e os chamados **Agentes de IA**.

**Meus objetivos foram:**
* Entender, de forma simples, o que é um Agente de IA.
* Descobrir o que ele precisa para funcionar (como se fosse a "anatomia" dele).
* Aprender a usar o NotebookLM para me ajudar a resumir conteúdos da internet.

---

## 📚 Fontes que utilizei no estudo

Para alimentar o NotebookLM com boas explicações, usei estes 3 links de artigos e guias sobre o assunto:

1. [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/) - Um artigo clássico que explica as partes de um agente de IA.
2. [Building Effective Agents](https://www.anthropic.com/research/building-effective-agents) - Um guia da Anthropic explicando como criar agentes úteis no dia a dia.
3. [AI Agents Course](https://huggingface.co/learn/agents-course/unit0/introduction) - Um curso gratuito da Hugging Face explicando o básico sobre o tema.

---

## 💡 Minhas perguntas para a IA e o que aprendi (Engenharia de Prompts)

Quando comecei a fazer perguntas no NotebookLM, percebi que o jeito que a gente pergunta muda tudo!

* **Pergunta simples (tentativa 1):** *"O que é um agente de IA?"*
  * *O que aconteceu:* A IA deu uma resposta muito grande e cheia de palavras difíceis que não entendi muito bem.
* **Pergunta melhorada (tentativa 2):** *"Explique de forma bem simples o que é um agente de IA e dê um exemplo do dia a dia."*
  * *O que aconteceu:* A resposta ficou muito mais fácil! A IA comparou um agente a um assistente virtual que consegue tomar decisões sozinho.

---

## 📖 O que eu aprendi (Miniguia Amigável)

### 1. Afinal, o que é um Agente de IA?
Enquanto uma IA comum só responde quando você pergunta algo, um **Agente de IA** é como um "estagiário virtual": você dá um objetivo para ele e ele consegue pensar nos passos, usar ferramentas (como calculadora, busca na web) e tentar resolver o problema sozinho.

ele é dividido em 4 partes principais:
* **Perfil:** O "papel" que ele finge ser (ex: assistente de viagens, ajudante de código).
* **Memória:** A capacidade de lembrar do que já foi falado na conversa.
* **Planejamento:** Conseguir quebrar um problema grande em passos menores.
* **Ferramentas:** Conseguir usar a internet, calculadoras ou outros programas para cumprir a tarefa.

---

### 2. Dicionário de termos simples (Glossário)

* **Agente:** Uma IA que consegue agir e fazer coisas sozinha.
* **Prompt:** O texto ou pergunta que a gente digita para conversar com a IA.
* **LLM:** É o "cérebro" de texto da IA (como o ChatGPT ou Gemini).
* **RAG:** Um jeito de dar arquivos/documentos para a IA ler antes de responder.

---

### 3. Perguntas que você pode copiar e testar (Prompts)

Se você quiser usar uma IA para te ajudar a estudar qualquer assunto, pode usar estas perguntas:

```text
Explique o conceito de [COLOCAR O TEMA AQUI] como se eu tivesse 10 anos de idade e me dê 2 exemplos práticos do dia a dia.
