# Setup and Installation Guide

## Quick Start

### Live Demo Access
The easiest way to experience Meesho Mitra is through our live demo:
**Demo URL**: [https://idrachaudhary.github.io/MeeshoMitra/](https://idrachaudhary.github.io/MeeshoMitra/)

### Local Development Setup

## Prerequisites

- Node.js 14.0 or higher
- Python 3.8 or higher
- Git

## Frontend Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/MeeshoMitra.git
   cd MeeshoMitra
   Install dependencies

bash

Copy

Download
npm install
Run development server

bash

Copy

Download
npm start
The application will open at http://localhost:3000

Backend Setup (Optional for Full Functionality)
Navigate to backend directory

bash

Copy

Download
cd backend
Create virtual environment

bash

Copy

Download
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Python dependencies

bash

Copy

Download
pip install -r requirements.txt
Set up environment variables

bash

Copy

Download
cp .env.example .env
# Edit .env with your API keys
Start backend server

bash

Copy

Download
python main.py
Environment Variables
Create a .env file in the backend directory with:

env

Copy

Download
OPENAI_API_KEY=your_openai_api_key
WHISPER_API_KEY=your_whisper_api_key
TWILIO_ACCOUNT_SID=your_twilio_sid
TWILIO_AUTH_TOKEN=your_twilio_token
FIREBASE_CONFIG=your_firebase_config
API Keys Required
For full functionality, you need:

OpenAI API key (for GPT-4)

Whisper API key (for voice processing)

Twilio account (for WhatsApp integration)

Firebase project (for data storage)

Deployment
Frontend Deployment (Vercel)
bash

Copy

Download
npm run build
vercel --prod
Backend Deployment (AWS/Heroku)
bash

Copy

Download
# For AWS Elastic Beanstalk
eb init
eb create meesho-mitra-prod
eb deploy
Troubleshooting
Common Issues
CORS Errors

Ensure backend CORS settings include your frontend domain

Check if APIs are properly configured

API Key Errors

Verify all environment variables are set

Check API key permissions and quotas

Build Failures

Clear node_modules and reinstall: rm -rf node_modules && npm install

Check Node.js version compatibility

Support
For technical support or questions:

Create an issue on GitHub

Check existing issues for solutions

Contact: idrachaudhary@email.com

This setup guide covers the basic installation. For advanced configuration, refer to our detailed documentation.

text

Copy

Download

## 🚀 Next Steps:

1. **Create `docs` folder** in your GitHub repo
2. **Create each file** with the exact content above
3. **Commit and push** to make them live
4. **Update your README.md** to link to these documentation files

Your GitHub structure will look professional and comprehensive for the hackathon judges!
