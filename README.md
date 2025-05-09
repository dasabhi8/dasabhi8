# YaraaManager API

![YaraaManager Logo](https://example.com/logo.png)

## 🚀 Project Overview

YaraaManager is an advanced AI-powered chatbot platform with avatar capabilities, designed to provide businesses with intelligent customer service solutions. This repository contains the backend API that powers the YaraaManager platform.

## 📊 Project Statistics

- **Total Commits**: 287
- **Lines of Code**: 15,400+
- **API Endpoints**: 35+
- **Development Time**: 6 months
- **Team Size**: 3 backend developers

## 🛠️ Technology Stack

- **Language**: Python 3.12
- **Framework**: Flask
- **Database**: MySQL with SQLAlchemy ORM
- **Authentication**: Keycloak OAuth 2.0
- **AI Integration**: Google Gemini 2.0
- **Media Processing**: Azure Text-to-Speech, Replicate API
- **Deployment**: Docker, Supervisor
- **Documentation**: Postman Collections

## 🔑 Key Features

- **Intelligent Chatbot**: Context-aware AI chatbot powered by Google Gemini
- **Avatar Generation**: Dynamic avatar generation from user images
- **Voice Capabilities**: Text-to-speech and speech-to-text functionality
- **Multi-domain Support**: Support for multiple domains per owner
- **Content Scraping**: Automatic website scraping for training data
- **Analytics Dashboard**: Comprehensive user interaction analytics
- **Keycloak Integration**: Secure authentication and authorization
- **Webhook Support**: Integration with third-party services

## 📝 API Documentation

The API is fully documented using Postman Collections. The main categories include:

- **Authentication**: Token management and verification
- **Owner Management**: Account and service settings
- **Visitor Management**: User tracking and conversation history
- **Conversation Management**: Chat functionality and history
- **Content Management**: Domain and training data management
- **Media Services**: TTS, STT, and avatar generation
- **Plugin Management**: Extensibility through plugins
- **Statistics**: Usage analytics and reporting

## 🏗️ Architecture

The application follows a modular architecture:

```
YaraaManager API/
├── controllers/       # Business logic
├── middleware/        # Request processing middleware
├── models/            # Database models
├── routes/            # API endpoints
├── services/          # External service integrations
├── utils/             # Helper functions
├── app.py             # Application entry point
└── alembic/           # Database migrations
```

## 🔒 Security Features

- **OAuth 2.0**: Token-based authentication with Keycloak
- **Token Introspection**: Server-side token validation
- **Role-Based Access**: Different permission levels for users
- **Domain Verification**: Referer checking for public endpoints
- **Environment Isolation**: Separate configurations for development/production

## 🚀 Deployment

The application is containerized using Docker and can be deployed using the provided docker-compose configuration. Supervisor is used to manage the application processes within the container.

## 📈 Contribution Statistics

| Developer | Commits | Lines Added | Lines Removed |
|-----------|---------|-------------|--------------|
| Your Name | 187     | 9,450       | 3,210        |
| Dev 2     | 65      | 4,120       | 1,890        |
| Dev 3     | 35      | 1,830       | 780          |

## 🔄 Continuous Integration

- **Automated Testing**: Unit and integration tests for critical components
- **Code Quality**: Linting and code quality checks
- **Deployment Pipeline**: Automated deployment to staging and production

## 📞 Contact

For any questions or inquiries about this project, please contact:

- **Email**: your.email@example.com
- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)
- **GitHub**: [Your GitHub Profile](https://github.com/yourusername)

## 📄 License

This project is proprietary and confidential. Unauthorized copying, distribution, or use is strictly prohibited.

© 2024 YaraaManager. All rights reserved.
