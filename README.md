# 🐙 Nexus OmniCore - The Business Growth Engine

**The AI-Powered Business Operating System that transforms your business into an automated growth machine.**

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/webscarpper/nexus-omnicore.git
cd nexus-omnicore
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Configure Environment
```bash
cp .env.example .env
# Edit .env with your API keys
```

### 4. Start the Server
```bash
npm start
```

### 5. Test Your System
- **Dashboard**: http://localhost:3000
- **Health Check**: http://localhost:3000/api/omnicore/health
- **API Status**: http://localhost:3000/api/omnicore/status

## 🤖 The "Octopus" Architecture

OmniCore operates with 6 specialized AI agents:

- **🕷️ ScraperAgent**: Web scraping & competitor monitoring
- **📱 SocialAgent**: Social media automation  
- **✍️ ContentAgent**: AI content generation
- **👥 CRMAgent**: Customer relationship management
- **🌐 WebAgent**: Website & content management
- **⚡ WorkflowAgent**: Automation workflows

## 🧪 Test the Agents

### Web Scraping Test
```bash
curl -X POST http://localhost:3000/api/agents/scraper/fetch_url_content \
  -H "Content-Type: application/json" \
  -d '{"params": {"url": "https://example.com"}}'
```

### AI Chat Test
```bash
curl -X POST http://localhost:3000/api/omnicore/chat \
  -H "Content-Type: application/json" \
  -d '{"message": "Hello! What can you help me automate?", "userId": "test"}'
```

### CRM Contact Creation
```bash
curl -X POST http://localhost:3000/api/agents/crm/create_contact \
  -H "Content-Type: application/json" \
  -d '{"params": {"data": {"firstName": "John", "lastName": "Doe", "email": "john@test.com"}}}'
```

## 🔑 API Keys Setup

To unlock full AI capabilities, add these to your `.env` file:

```bash
# OpenAI for content generation
OPENAI_API_KEY=your-actual-openai-key

# Twitter for social media
TWITTER_API_KEY=your-twitter-key
TWITTER_API_SECRET=your-twitter-secret

# Email for automation
SMTP_HOST=smtp.gmail.com
SMTP_USER=your-email@gmail.com
SMTP_PASS=your-app-password
```

## 🐳 Docker Deployment

```bash
docker-compose up -d
```

## 🎯 What You Can Automate

- ✅ **Web Scraping**: Monitor competitors automatically
- ✅ **Social Media**: Post content across all platforms
- ✅ **Content Creation**: Generate blogs, emails, ads with AI
- ✅ **Lead Management**: Capture and nurture prospects
- ✅ **Email Automation**: Send personalized sequences
- ✅ **Workflow Creation**: Build complex automations
- ✅ **Analytics**: Track performance in real-time

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/webscarpper/nexus-omnicore/issues)
- **Documentation**: Check the `/server` and `/client` folders for code

---

**🐙 Built with ❤️ - Ready to automate your business!**