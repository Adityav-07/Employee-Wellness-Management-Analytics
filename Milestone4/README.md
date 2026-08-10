# Employee Wellness Management Analytics

## MoodMentor – AI-Powered Employee Wellness Management System

MoodMentor is an AI-powered Employee Wellness Management Analytics application developed as part of the Employee Wellness Management Analytics project.

The system analyzes employee feedback using Natural Language Processing (NLP), sentiment analysis, and emotion detection. Based on the detected emotional state and sentiment, the system provides personalized wellness recommendations and allows employees to interact with the MoodMentor wellness chatbot.

The application also provides historical wellness analytics, emotion and sentiment trends, filtering, and report generation.

---

## Project Objectives

- Analyze employee wellness feedback using AI and NLP.
- Detect emotions and sentiment from employee feedback.
- Support both direct text input and file-based input.
- Provide personalized wellness recommendations.
- Provide an AI-powered wellness chatbot.
- Store employee wellness history securely.
- Display historical emotional trends and analytics.
- Generate downloadable wellness reports.

---

## Key Features

### 1. Authentication
- Employee registration and login
- JWT-based authentication
- OTP-based verification
- Password management

### 2. Employee Wellness Analysis
- Direct text input
- CSV/TXT file upload
- Multilingual text processing
- Language detection
- Text preprocessing
- Sentiment analysis
- Emotion detection

### 3. Recommendation System
- Emotion-based wellness recommendations
- Sentiment-aware recommendations
- Confidence-based recommendation levels

### 4. MoodMentor Chatbot
- Conversational wellness support
- Context-aware conversation
- Supportive wellness suggestions
- Crisis-language detection

### 5. Wellness Dashboard
- Historical mood records
- Emotion distribution
- Sentiment trends
- Date-range filtering
- Emotion filtering
- Search functionality
- Wellness statistics

### 6. Reporting
- PDF wellness report generation
- CSV data export
- Historical analysis

---

## AI/ML Pipeline

The complete analysis workflow is:

Text Input
↓
Text Preprocessing
↓
Language Detection
↓
Tokenization & Stopword Filtering
↓
Translation
↓
Lemmatization
↓
Sentiment Analysis
↓
Emotion Detection
↓
Recommendation
↓
Database Storage
↓
Dashboard & Report

---

## Technology Stack

### Frontend
- Python
- Streamlit
- HTML/CSS
- JavaScript/CSS-based UI components

### Backend
- FastAPI
- Python
- REST APIs

### Database
- PostgreSQL

### AI/ML
- Transformers
- BERT-based emotion classification
- VADER Sentiment Analysis
- spaCy
- LangDetect
- Deep Translator

### Chatbot
- Qwen2.5-0.5B-Instruct

### Other Technologies
- JWT
- bcrypt
- ReportLab
- Pandas
- Matplotlib
- OpenCV
- Git & GitHub
- Google Colaboratory

---

## System Architecture

The application consists of the following major layers:

### Frontend
The Streamlit frontend provides the user interface for authentication, journal entries, wellness analysis, chatbot interaction, relaxation activities, and analytics.

### Backend
The FastAPI backend provides API endpoints for authentication, file upload, text analysis, file analysis, and chatbot interaction.

### AI/ML Layer
The NLP pipeline processes employee feedback and performs language detection, preprocessing, sentiment analysis, and emotion classification.

### Recommendation Layer
The recommendation engine generates wellness recommendations based on the detected emotional state and sentiment.

### Database Layer
PostgreSQL stores user information, authentication data, mood logs, and historical wellness information.

---

## Milestone 4

Milestone 4 focuses on:

- Complete system integration
- Frontend and backend integration
- Machine learning pipeline integration
- Recommendation system validation
- PostgreSQL database integration
- End-to-end functional testing
- Dashboard enhancement
- Historical analytics
- PDF and CSV reporting
- Error handling
- Final application testing and enhancement

---

