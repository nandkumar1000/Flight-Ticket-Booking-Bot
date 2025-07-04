

## ✈️ Flight Booking Bot with CLU (JavaScript)

A conversational bot built using **Microsoft Bot Framework v4** and integrated with **Conversational Language Understanding (CLU)** to demonstrate intelligent flight booking interactions using natural language.

---

### 📦 Project Name

`Flight Booking Bot`

---

### 🧠 Features

* ✨ Natural language understanding with **Azure CLU**
* 🧳 Book flights by extracting origin, destination, and date
* 🤖 Built on **Bot Framework SDK v4**
* 🔄 Reusable dialogs for booking, date resolution, and help
* 🛠️ Structured code for scalability and modularity

---

### 🚀 Getting Started

#### 1. Clone the Repository

```bash
git clone https://github.com/nandkumar1000/Flight-Ticket-Booking-Bot.git
cd Flight-Ticket-Booking-Bot
```

#### 2. Install Dependencies

```bash
npm install
```

#### 3. Configure Environment

Create a `.env` file in the root directory and add the following:

```env
CluAPIKey=your_clu_api_key
CluAPIHostName=your_clu_endpoint_url
```

> You can create a CLU resource via [Azure Language Studio](https://language.azure.com/).

#### 4. Run the Bot

```bash
npm start
```

The bot will be hosted at:

```
http://localhost:3978/api/messages
```

---

### 💬 Testing the Bot

Use the [Bot Framework Emulator](https://aka.ms/botframework-emulator):

1. Open Emulator
2. Click **Open Bot**
3. Enter:

   ```
   http://localhost:3978/api/messages
   ```
4. Leave App ID and Password empty (unless configured)

---

### 🧩 Technologies Used

* **Node.js**
* **Microsoft Bot Framework v4**
* **Azure CLU (Conversational Language Understanding)**
* **Restify**
* **dotenv**
* **ESLint**, **Mocha**, **Nodemon**

---

### 🧪 Scripts

| Command         | Description                   |
| --------------- | ----------------------------- |
| `npm start`     | Start the bot                 |
| `npm run watch` | Start with nodemon (dev mode) |
| `npm run lint`  | Run ESLint checks             |

---

### 📁 Project Structure (Simplified)

```
.
├── bots/
├── clu/
├── cognitiveModels/
├── deploymentTemplates/
├── dialogs/
├── recognizer/
├── resources/
├── index.js
├── .env
└── package.json
```

---

### 📄 License

This project is licensed under the [MIT License](LICENSE).

---

### 🙌 Acknowledgements

Built using the [Microsoft Bot Builder Yeoman Generator v4.17.0](https://github.com/microsoft/botframework-sdk), with integration for Azure's **Conversational Language Understanding (CLU)**.

