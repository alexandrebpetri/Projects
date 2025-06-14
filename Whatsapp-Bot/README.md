# Simple Bot for WhatsApp (Node.js + TypeScript)

This is a simple bot for WhatsApp that I created using the **TypeScript** language.

I used the **whatsapp-web.js** and **qrcode-terminal** libraries.

I based it on this video on YouTube: [COMO CRIAR UM BOT PARA WHATSAPP USANDO Node.JS e Typescript | TUTORIAL PASSO A PASSO DAILY CODE #23](https://www.youtube.com/watch?v=H1nxKWg9i1c).

---

## 📌 Features

- Generation of **QR Code** in the terminal for authentication
- Persistent session using **LocalAuth** (no need to scan the QR code every time)
- Reading of received messages
- Automatic response to the `!hi` command with a default message
- Project structured in **TypeScript**

---

## 🛠️ Technologies Used

- Node.js
- TypeScript
- [whatsapp-web.js](https://github.com/pedroslopez/whatsapp-web.js)
- qrcode-terminal
- Puppeteer
- dotenv
- tsx (for development with hot-reload in TypeScript)

---

## 📥 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/alexandrebpetri/Whatsapp-Bot.git
cd Whatsapp-Bot
```

2. **Install the dependencies:**

```bash
npm install
```

3. **(Optional) Compile TypeScript to JavaScript (production mode):**

```bash
npm run build
```

---

## ▶️ How to Run the Bot

### ✅ Development Mode (with TypeScript in real time):

```bash
npm run start:dev
```

---

### ✅ Production Mode (running the compiled JavaScript):

```bash
npm run start:prod
```

---

## ✅ How it Works

- When starting, the bot will generate a **QR Code** in your terminal. - Open WhatsApp on your phone, go to **Connected devices**, and scan the QR Code.
- When the connection is successful, the terminal will show:

```
Client is ready!
```

- Now, send the following message to the bot (from any WhatsApp conversation):

```
!hi
```

- The bot will automatically respond with:

```
Hello, world! 
```

---

## 📂 Project Structure

```
Whatsapp-Bot/
├── dist/ # JavaScript code generated after build
├── node_modules/
├── src/ # Source code in TypeScript
│ └── index.ts
├── package-lock.json
├── package.json
├── tsconfig.json
└── README.md
```

---

## ✨ Credits

Project inspired by the library [whatsapp-web.js](https://github.com/pedroslopez/whatsapp-web.js)
and the video tutorial: [https://www.youtube.com/watch?v=H1nxKWg9i1c](https://www.youtube.com/watch?v=H1nxKWg9i1c).

---

## 💬 Questions or Suggestions?

Feel free to open an **issue** or create a **pull request** with suggestions and improvements! 😉

---


# (🌍 PT-BR) Bot Simples para WhatsApp (Node.js + TypeScript)

Este é um bot simples para WhatsApp que eu criei utilizando a linguagem **TypeScript**.  
Utilizei as bibliotecas **whatsapp-web.js** e **qrcode-terminal**.  
Me baseei neste vídeo no YouTube: [COMO CRIAR UM BOT PARA WHATSAPP USANDO Node.JS e Typescript | TUTORIAL PASSO A PASSO DAILY CODE #23](https://www.youtube.com/watch?v=H1nxKWg9i1c).

---

## 📌 Funcionalidades

- Geração de **QR Code** no terminal para autenticação
- Sessão persistente usando **LocalAuth** (não precisa escanear o QR a cada execução)
- Leitura de mensagens recebidas
- Resposta automática ao comando `!hi` com uma mensagem padrão
- Projeto estruturado em **TypeScript**

---

## 🛠️ Tecnologias Utilizadas

- Node.js
- TypeScript
- [whatsapp-web.js](https://github.com/pedroslopez/whatsapp-web.js)
- qrcode-terminal
- Puppeteer
- dotenv
- tsx (para desenvolvimento com hot-reload em TypeScript)

---

## 📥 Instalação

1. **Clone o repositório:**

```bash
git clone https://github.com/alexandrebpetri/Whatsapp-Bot.git
cd Whatsapp-Bot
```

2. **Instale as dependências:**

```bash
npm install
```

3. **(Opcional) Compile o TypeScript para JavaScript (modo produção):**

```bash
npm run build
```

---

## ▶️ Como Executar o Bot

### ✅ Modo Desenvolvimento (com TypeScript em tempo real):

```bash
npm run start:dev
```

---

### ✅ Modo Produção (executando o JavaScript compilado):

```bash
npm run start:prod
```

---

## ✅ Como Funciona

- Ao iniciar, o bot vai gerar um **QR Code** no seu terminal.
- Abra o WhatsApp no celular, vá em **Aparelhos conectados**, e escaneie o QR Code.
- Quando a conexão for bem-sucedida, o terminal mostrará:

```
Client is ready!
```

- Agora, envie para o bot (de qualquer conversa no WhatsApp) a seguinte mensagem:

```
!hi
```

- O bot responderá automaticamente com:

```
Hello, world!
```

---

## 📂 Estrutura do Projeto

```
Whatsapp-Bot/
├── dist/           # Código JavaScript gerado após o build
├── node_modules/  
├── src/            # Código-fonte em TypeScript
│   └── index.ts
├── package-lock.json
├── package.json
├── tsconfig.json
└── README.md
```

---

## ✨ Créditos

Projeto inspirado na biblioteca [whatsapp-web.js](https://github.com/pedroslopez/whatsapp-web.js)  
e no vídeo tutorial: [https://www.youtube.com/watch?v=H1nxKWg9i1c](https://www.youtube.com/watch?v=H1nxKWg9i1c).

---

## 💬 Dúvidas ou Sugestões?

Sinta-se à vontade para abrir uma **issue** ou criar um **pull request** com sugestões e melhorias! 😉