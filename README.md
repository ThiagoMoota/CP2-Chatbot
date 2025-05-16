# CP2-Chatbot
# Assistente Interativo no Telegram com Watson Assistant e Node-RED

## 🎯 Objetivo

Criar um chatbot para atendimento digital via Telegram, utilizando IBM Watson Assistant com respostas interativas (tipo `option`). A comunicação é intermediada pelo Node-RED, que interpreta as respostas e transforma as opções do Watson em botões clicáveis do Telegram.

---

## 🔧 Tecnologias Usadas

- **Telegram Bot API**
- **Node-RED**
- **IBM Watson Assistant**
- **Node-RED Contrib Telegrambot**
- **Watson Assistant V2 API**

---

## ⚙️ Estrutura do Fluxo

1. **Usuário envia mensagem no Telegram**.
2. **Node-RED** recebe a mensagem e encaminha ao **Watson Assistant**.
3. **Watson responde com opção (buttons)**.
4. Node-RED converte as opções em **botões do Telegram**.
5. Quando o usuário clica, a escolha é enviada de volta ao Watson, mantendo o contexto.

---

## 💬 Exemplo de Interação

### Usuário:
