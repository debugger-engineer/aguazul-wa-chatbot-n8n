# Aguazul WhatsApp Chatbot (n8n)

A powerful WhatsApp chatbot built with n8n for Aguazul, a Brazilian water distribution company. This chatbot handles customer service, orders, and FAQs efficiently using modern AI and automation technologies.

## 🚀 Features

- 🤖 **AI-Powered Responses**: Leverages LangChain and OpenAI for intelligent conversation handling
- 💾 **Session Management**: Redis-based session and memory management for conversation context
- 📊 **Data Integration**: Seamless integration with Google Sheets for:
  - Customer address management
  - Product pricing and inventory
  - Business information storage
- 🔄 **Automated Workflows**: Streamlined order processing and customer service
- 📱 **WhatsApp Integration**: Full support for media and message automation via Evolution API
- 👤 **Personalized Experience**: Addresses users by name and maintains conversation context
- 💬 **Multi-Flow Support**: Handles different types of interactions:
  - Greetings and introductions
  - Product inquiries and pricing
  - Order processing
  - Customer service
  - Appointment scheduling

## 🛠️ Tech Stack

- [n8n](https://n8n.io/) - Workflow automation platform
- [Redis](https://redis.io/) - Session and memory management
- [LangChain](https://www.langchain.com/) - AI/LLM framework
- [OpenAI](https://openai.com/) - Language model provider
- [Google Sheets API](https://developers.google.com/sheets/api) - Data management
- [Evolution API](https://evolution-api.com/) - WhatsApp integration
- [Calendly](https://calendly.com/) - Appointment scheduling

## 📋 Prerequisites

- n8n instance
- Redis server
- OpenAI API key
- Google Sheets API credentials
- Evolution API access
- WhatsApp Business API access

## 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/debugger-engineer/aguazul-wa-chatbot-n8n.git
```

2. Import the workflow:
   - Open your n8n instance
   - Import the `Aguazul-n8n.json` file
   - Configure your credentials in the workflow:
     - Redis credentials
     - OpenAI API credentials
     - Google Sheets API credentials
     - Evolution API key

3. Set up environment variables:
```bash
OPENAI_API_KEY=your_api_key
REDIS_URL=your_redis_url
GOOGLE_SHEETS_CREDENTIALS=your_credentials
EVOLUTION_API_KEY=your_evolution_api_key
```

## 📖 Usage

1. Start the n8n workflow
2. Connect your WhatsApp Business API through Evolution API
3. The chatbot will automatically handle:
   - Customer greetings with personalized responses
   - Product inquiries and pricing information
   - Order processing with address verification
   - Customer service inquiries
   - Appointment scheduling via Calendly
   - FAQ responses about water products and services

## 🔒 Security

- All sensitive credentials are stored securely in n8n
- API keys and credentials are not exposed in the workflow file
- Customer data is managed through secure Google Sheets integration

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
