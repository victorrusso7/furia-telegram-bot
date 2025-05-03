# FURIAHELPER\_BOT 🐾🔥

**Chatbot oficial da torcida FURIA no Telegram**, criado com **n8n** + **Gemini AI** para entregar uma experiência interativa, personalizada e cheia de emoção Black & Bold!

Desenvolvido por [Victor Russo](https://www.linkedin.com/in/victorrusso7) para o **Desafio Técnico #1 da FURIA Tech**.

---

## 🎯 Sobre o projeto

O **FURIAHELPER\_BOT** foi pensado para criar um canal de comunicação entre o torcedor e a equipe, com informações atualizadas, bom humor e estilo. Com ele, os fãs podem:

* Ver o calendário atualizado de **todas as modalidades**
* Conferir **resultados dos últimos jogos**
* Consultar o **elenco atual por time**
* Acessar **produtos oficiais** e redes sociais da FURIA
* Jogar um **quiz interativo**
* Tudo isso com **respostas carismáticas e identidade da torcida**

---

## ▶ Demonstração

![Menu do Bot](docs/menu.png.jpeg)

📽️ **Veja o FURIAHELPER\_BOT em ação:**

[![Assista ao vídeo](https://img.youtube.com/vi/P5IteVHWZgA/hqdefault.jpg)](https://www.youtube.com/watch?v=P5IteVHWZgA)

---

## 🧠 Tecnologias utilizadas

* [n8n](https://n8n.io) — automação e criação de fluxos low-code
* [Gemini Pro](https://ai.google.dev) — IA da Google para geração de respostas
* [Telegram Bot API](https://core.telegram.org/bots/api)
* HTTP Request (para dados de jogos da Draft5)
* Simple Memory (armazenamento de contexto)

---

## 📁 Estrutura do projeto

```
furia-telegram-bot/
├── workflows/
│   └── furiabot-n8n-workflow.json  # Fluxo n8n
├── docs/
│   ├── menu.png.jpeg                # Tela inicial do bot
├── .gitignore
└── README.md
```

---

## ⚙️ Como usar

### 1. Clone o repositório

```bash
git clone https://github.com/victorrusso7/furia-telegram-bot.git
cd furia-telegram-bot
```

### 2. Importe no n8n

* Crie um novo Workflow
* Clique nos 3 pontinhos > Import from file
* Selecione: `workflows/furiabot-n8n-workflow.json`

### 3. Configure os acessos

* **Token do Telegram** ([crie no BotFather](https://t.me/BotFather))
* **API Key do Gemini** (via Google AI Studio)

### 4. Ative o Workflow

* Clique em **Activate**
* Converse com o bot: [@FURIAHELPER\_BOT](https://t.me/FURIAHELPER_BOT)

---

## 🧩 Funcionalidades

* Interação com linguagem divertida e estilo da torcida 🖤

* Menu com 7 opções:

  ```
  1️⃣ Próximos Jogos
  2️⃣ Últimos Jogos
  3️⃣ Elenco
  4️⃣ Produtos Oficiais
  5️⃣ Redes Sociais
  6️⃣ Modalidades
  7️⃣ Quiz da FURIA
  ```

* Memória do usuário (nome, quiz, preferências)

* Quiz com pontuação

* Suporte a múltiplos idiomas (PT/EN/ES)

---

## 📌 Observações

* As opções são enviadas por **número digitado**, não botões (limitação do Telegram + n8n).
* Notícias e botões podem ser adicionados futuramente.
* O vídeo de demonstração está no YouTube e vinculado acima.

---

## 👤 Desenvolvido por

**Victor Russo**
🔗 [LinkedIn](https://www.linkedin.com/in/victorrusso7)
🚀 Criado com ❤️ para o **Desafio Técnico da FURIA Tech**

---

**#GoFURIA** 🖤
**#BlackAndBold**
**#FuriaTechChallenge**