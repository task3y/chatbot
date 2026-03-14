# AI Chatbot - Gemini-Powered Conversational Interface

A responsive AI chatbot application built with React.js that leverages Google's Gemini AI to provide intelligent, dynamic responses to user queries. This chatbot features a clean, modern UI and works seamlessly across desktop and mobile devices.

## 🌟 Features

* **Real-time AI Responses** - Powered by Google Gemini AI for intelligent conversation
* **Responsive Design** - Optimized for both desktop and mobile devices
* **Clean UI/UX** - Built with React.js and custom CSS for an intuitive user experience
* **Instant Answers** - Get immediate responses to your questions
* **Dynamic Conversations** - Context-aware responses that adapt to your inquiries
* **Mobile-Friendly** - Use the chatbot seamlessly on your smartphone

## 🛠️ Tech Stack

**Frontend:**
* React.js
* CSS3
* JavaScript (ES6+)

**AI Integration:**
* Google Gemini AI API

## 📋 Prerequisites

Before running this project, make sure you have:

* Node.js (v14 or higher)
* npm or yarn package manager
* Google Gemini API Key 

## 🚀 Getting Started

### Installation

1. **Clone the repository**
```bash
   git clone https://github.com/task3y/chatbot.git
   cd chatbot
```

2. **Install dependencies**
```bash
   npm install
```

3. **Set up environment variables**
   
   Create a `.env` file in the root directory and add your Gemini API key:
```env
   REACT_APP_GEMINI_API_KEY=your_gemini_api_key_here
```

4. **Run the application**
```bash
   npm start
```

5. **Open your browser**
   
   Navigate to `http://localhost:3000` to see the chatbot in action!

## 📱 Usage

1. Type your question in the input field
2. Press Enter or click the Send button
3. Receive instant AI-generated responses
4. Continue the conversation naturally

## 📂 Project Structure
```
ai-chatbot-gemini/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── Chatbot.js
│   │   ├── Message.js
│   │   └── InputBox.js
│   ├── styles/
│   │   └── Chatbot.css
│   ├── services/
│   │   └── geminiAPI.js
│   ├── App.js
│   └── index.js
├── .env
├── package.json
└── README.md
```

## 🔑 Getting Your Gemini API Key

1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Sign in with your Google account
3. Click "Get API Key"
4. Copy your API key and add it to your `.env` file

## 🙏 Acknowledgments

* Google Gemini AI for providing the powerful AI capabilities
* React.js community for excellent documentation and support
* All contributors who help improve this project

## 🔮 Future Enhancements

- [ ] Add conversation history storage
- [ ] Implement multi-language support
- [ ] Add voice input/output capabilities
- [ ] Dark mode toggle
- [ ] Export chat conversations
- [ ] User authentication

---

**⭐ If you find this project helpful, please give it a star!**
