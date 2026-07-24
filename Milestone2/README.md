# Intelligent Freight Quote AI

## Milestone 2 - AI Agents, ML Pricing & Advanced Security

# Project Description

Intelligent Freight Quote AI is an AI-powered freight management system that generates intelligent freight quotes using Machine Learning, LLMs, and AI agents.
The system provides dynamic freight pricing, AI-based assistance, route optimization recommendations, and logistics insights. It also includes an Admin Panel for monitoring ML model performance, managing users, and maintaining application security.

# Features Implemented

## 1. AI Copilot
- Interactive AI assistant for freight and logistics queries.
- Accepts user prompts and generates intelligent responses.
- Provides freight-related recommendations.

## 2. ML Pricing Calculator
- Predicts freight cost using Machine Learning models.
- Accepts freight input details.
- Generates estimated pricing output.

## 3. AI Agent System

### Agent 1 – Dynamic Pricing Agent
- Predicts optimized freight cost.
- Uses ML model results for pricing decisions.

### Agent 2 – Route Optimization Agent
- Suggests efficient transportation routes.
- Helps reduce travel distance and cost.

### Agent 3 – Logistics Recommendation Agent
- Provides logistics suggestions and recommendations.

## 4. Admin Panel

### User Management
Admin can:
- Add users
- Delete users
- Unlock locked accounts

### ML Model Card
Displays:
- Model information
- R² Score
- RMSE
- Agent performance metrics

## 5. Security Enhancements
- Failed login attempt tracking.
- Account lockout after multiple failed attempts.
- 15-minute temporary account lock.
- OTP resend cooldown timer.


# Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Backend development |
| Streamlit | User interface |
| Machine Learning | Freight cost prediction |
| LLM | AI Copilot |
| Hugging Face Models | Natural Language Processing |
| Kaggle Dataset | ML training data |
| SQLite | Database management |
| JWT | Authentication security |
| Google Colab | Development environment |
| Ngrok | Public URL deployment |
| GitHub | Version control |


# Project Structure

Milestone2/
├── README.md
├── FreightQuote_AI_Milestone2.ipynb
└── screenshots/
    ├── home_page.png
    ├── ai_copilot.png
    ├── ml_pricing_calculator.png
    ├── admin_ml_model_card.png
    ├── admin_user_management.png
    ├── lockout_message.png
    └── otp_cooldown_message.png

# Google Colab Secrets Used

The following secrets are stored securely in Google Colab Secrets:

| Secret Name | Purpose |
|------------|---------|
| JWT_SECRET | Used for secure JWT token generation |
| NGROK_AUTHTOKEN | Used to create public Streamlit URL |
| EMAIL_ADDRESS | Used for sending OTP emails |
| EMAIL_PASSWORD | Gmail App Password for OTP authentication |
| ADMIN_EMAIL | Admin account email for dashboard access |
| ADMIN_PASSWORD | Admin account password (stored securely) |
| HUGGINGFACE_TOKEN | Access Hugging Face models |
| KAGGLE_USERNAME | Kaggle API username |
| KAGGLE_KEY | Kaggle API key |

