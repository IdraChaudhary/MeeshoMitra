# Contributing to Meesho Mitra

We love your input! We want to make contributing to Meesho Mitra as easy and transparent as possible.

## Development Process

1. Fork the repo and create your branch from `main`
2. If you've added code that should be tested, add tests
3. If you've changed APIs, update the documentation
4. Ensure the test suite passes
5. Make sure your code lints
6. Issue that pull request!

## Pull Request Process

1. Update the README.md with details of changes if applicable
2. Update the documentation with details of any new features
3. The PR will be merged once you have the sign-off of at least one maintainer

## Code Style

### JavaScript/React
- Use 2 spaces for indentation
- Use semicolons
- Use single quotes for strings
- Follow the Airbnb JavaScript Style Guide

### Python
- Use 4 spaces for indentation
- Follow PEP 8 guidelines
- Use type hints where possible
- Use Google-style docstrings

### Git Commit Messages
- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

## Setting Up Development Environment

### Prerequisites
- Node.js 18+
- Python 3.8+
- Git

### Steps
1. Fork the repository
2. Clone your fork locally
3. Install dependencies:
   ```bash
   npm install
   cd backend && pip install -r requirements.txt
Set up environment variables (see .env.example)

Run the development server:

bash

Copy

Download
npm run dev
Project Structure
text

Copy

Download
meesho-mitra/
├── src/                 # Frontend source code
│   ├── components/      # React components
│   ├── hooks/          # Custom React hooks
│   ├── services/       # API services
│   └── styles/         # CSS files
├── backend/            # Backend source code
│   ├── app/           # FastAPI application
│   ├── models/        # Data models
│   └── services/      # Business logic
├── docs/              # Documentation
└── tests/             # Test files
Adding New Features
Create a new branch: git checkout -b feature/amazing-feature

Make your changes

Add tests for new functionality

Update documentation

Run tests: npm test and pytest

Push to branch: git push origin feature/amazing-feature

Submit a pull request

Reporting Bugs
We use GitHub issues to track public bugs. Report a bug by opening a new issue.

Write Bug Reports With Detail, Background, and Sample Code
Great Bug Reports tend to have:

A quick summary and/or background

Steps to reproduce

Be specific!

Give sample code if you can

What you expected would happen

What actually happens

Notes (possibly including why you think this might be happening, or stuff you tried that didn't work)

License
By contributing, you agree that your contributions will be licensed under its MIT License.

Questions?
Feel free to contact the maintainers:

Idra Chaudhary: idrachaudhary@email.com

Thank you for contributing to Meesho Mitra! 🚀
