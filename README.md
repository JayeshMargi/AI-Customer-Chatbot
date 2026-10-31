# 🤖 Zenvora AI – AI Customer Support Chatbot

An AI-powered customer support platform that helps businesses automate customer interactions using intelligent AI chatbots. Zenvora AI enables businesses to provide instant responses to customer queries using their own business knowledge, improving customer experience and reducing manual support efforts.

🌐 **Live Demo:** https://ai-customer-chatbot-eta.vercel.app/

---

## ✨ Features

- 🤖 **AI-Powered Chatbot:** Provides intelligent, context-aware responses using Google Gemini AI.
- 💬 **Real-Time Customer Support:** Helps customers get instant answers to their questions.
- 🏢 **Business Knowledge Integration:** Allows businesses to control the information used by their AI chatbot.
- 🔌 **Easy Website Integration:** Add the chatbot to your website using a simple script integration.
- 🔐 **Authentication:** Secure authentication for managing the platform.
- ⚙️ **Admin Control:** Manage chatbot knowledge and business-related information.
- 📱 **Responsive UI:** Modern interface designed for different screen sizes.
- ⚡ **Fast Performance:** Built using Next.js for an optimized web experience.
- 🌐 **24/7 Availability:** Provides automated customer assistance anytime.

## 🛠️ Tech Stack

### Frontend
- Next.js 16
- React 19
- TypeScript
- Tailwind CSS 4

### Backend
- Next.js
- Node.js

### Database
- MongoDB
- Mongoose

### AI Integration
- Google Gemini AI (`@google/genai`)

### Authentication
- Scalekit

### Deployment
- Vercel

---

## 📸 Application Preview

**Live Application:**  
https://ai-customer-chatbot-eta.vercel.app/

Visit the live application to explore the interface and chatbot experience.

---

## ⚙️ Installation & Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/JayeshMargi/AI-Customer-Chatbot.git
```

### 2. Navigate to the Project Directory

```bash
cd AI-Customer-Chatbot/zenvora-ai
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env.local` file in the project root directory.

Add the required environment variables for:

- Google Gemini API
- MongoDB connection
- Scalekit authentication

Use the variable names expected by the application source code.

**Important:** Never expose API keys, database credentials, or authentication secrets publicly.

### 5. Run the Development Server

```bash
npm run dev
```

### 6. Open in Browser

Visit:

```text
http://localhost:3000
```

---

## 📂 Project Structure

```text
AI-Customer-Chatbot/
│
├── zenvora-ai/
│   ├── app/              # Next.js application and routes
│   ├── components/       # Reusable UI components
│   ├── public/           # Static assets
│   ├── package.json      # Project dependencies
│   ├── package-lock.json
│   ├── next.config.ts    # Next.js configuration
│   ├── tsconfig.json     # TypeScript configuration
│   └── ...
│
└── README.md
```

*Note: This is a high-level overview of the project structure.*

---

## 🚀 Available Scripts

| Command | Description |
|---|---|
| `npm install` | Install dependencies |
| `npm run dev` | Start development server |
| `npm run build` | Build production application |
| `npm start` | Start production server |
| `npm run lint` | Run ESLint |

---

## 🔄 How It Works

1. Customers visit a business website.
2. They interact with the integrated AI chatbot.
3. Customers submit their questions through the chat interface.
4. The application processes the query using its AI integration and available business knowledge.
5. Google Gemini AI generates an appropriate response.
6. The chatbot displays the response to the customer.

---

## 🎯 Project Goals

- Automate customer support using Artificial Intelligence.
- Reduce repetitive customer service tasks.
- Provide instant and helpful customer responses.
- Give businesses control over their chatbot knowledge.
- Make AI-powered customer support accessible through simple website integration.

---

## 🔮 Future Improvements

- Support for multiple AI models.
- Advanced chatbot analytics and reporting.
- Multilingual customer support.
- Conversation history management.
- Customizable chatbot appearance.
- Human support agent integration.
- Improved knowledge-base management.

---

## 👨‍💻 Author

**Jayesh Margi**

- GitHub: [@JayeshMargi](https://github.com/JayeshMargi)

---

## ⭐ Support

If you find this project useful or interesting, consider giving it a ⭐ on GitHub!

**Built with ❤️ by Jayesh Margi**
