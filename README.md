# Aguazul WhatsApp Chatbot (n8n)

A powerful WhatsApp chatbot built with n8n for Aguazul, a Brazilian water distribution company. This chatbot handles customer service, orders, and FAQs efficiently using modern AI and automation technologies.

## 🚀 Features

- 🤖 **AI-Powered Responses**: Leverages LangChain and OpenAI for intelligent conversation handling
- 💾 **Session Management**: Redis-based session and memory management
- 📊 **Data Integration**: Seamless integration with Google Sheets for customer and pricing data
- 🔄 **Automated Workflows**: Streamlined order processing and customer service
- 📱 **WhatsApp Integration**: Full support for media and message automation via HTTP requests

## 🛠️ Tech Stack

- [n8n](https://n8n.io/) - Workflow automation platform
- [Redis](https://redis.io/) - Session and memory management
- [LangChain](https://www.langchain.com/) - AI/LLM framework
- [OpenAI](https://openai.com/) - Language model provider
- [Google Sheets API](https://developers.google.com/sheets/api) - Data management

## 📋 Prerequisites

- n8n instance
- Redis server
- OpenAI API key
- Google Sheets API credentials
- WhatsApp Business API access

## 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/debugger-engineer/aguazul-wa-chatbot-n8n.git
```

2. Import the workflow:
   - Open your n8n instance
   - Import the `Aguazul-n8n.json` file
   - Configure your credentials in the workflow

3. Set up environment variables:
```bash
OPENAI_API_KEY=your_api_key
REDIS_URL=your_redis_url
GOOGLE_SHEETS_CREDENTIALS=your_credentials
```

## 📖 Usage

1. Start the n8n workflow
2. Connect your WhatsApp Business API
3. The chatbot will automatically handle:
   - Customer greetings
   - FAQ responses
   - Order processing
   - Customer service inquiries

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Debugger Engineer Team

## 🙏 Acknowledgments

- Aguazul team for their support and requirements
- n8n community for their excellent platform
- All contributors who help improve this project
