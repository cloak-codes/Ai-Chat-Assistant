# AI Chat Assistant

A modern, responsive AI chatbot built with Next.js and powered by Groq's LLaMA model. Features real-time streaming responses, chat history persistence, and a clean, intuitive interface.

## Features

- 🤖 **AI-Powered Chat**: Powered by Groq's LLaMA 3.3 70B model
- ⚡ **Real-time Streaming**: See responses as they're generated
- 💾 **Chat History**: Conversations are saved locally in your browser
- 🎨 **Modern UI**: Clean, responsive design with dark theme
- 🚀 **Fast Deployment**: Optimized for Vercel deployment

## Tech Stack

- **Frontend**: Next.js 16, React 19
- **Styling**: CSS Modules
- **AI**: Groq API (LLaMA 3.3 70B)
- **Deployment**: Vercel

## Getting Started

### Prerequisites

- Node.js 18+
- A Groq API key (get one at [groq.com](https://groq.com))

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/ai-chat-assistant.git
cd ai-chat-assistant
```

2. Install dependencies:

```bash
npm install
```

3. Create a `.env.local` file in the root directory:

```bash
GROQ_API_KEY=your_groq_api_key_here
```

4. Run the development server:

```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

- Type your message in the input field
- Press Enter or click Send to chat with the AI
- Click "New Chat" to start a fresh conversation
- Chat history is automatically saved in your browser

## Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to [Vercel](https://vercel.com)
3. Add your `GROQ_API_KEY` in Vercel's environment variables
4. Deploy!

### Other Platforms

The app can also be deployed to Netlify, Railway, or any platform that supports Next.js.

## Environment Variables

- `GROQ_API_KEY`: Your Groq API key (required)

## API Routes

- `POST /api/chat`: Handles chat requests to Groq API

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- [Groq](https://groq.com) for the fast AI inference
- [Next.js](https://nextjs.org) for the amazing framework
- [Vercel](https://vercel.com) for hosting
