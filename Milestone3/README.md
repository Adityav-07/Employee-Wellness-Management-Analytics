# Employee Wellness Management Analytics
## Milestone 3 – Emotion Detection & Journal Analytics

### Project Objective
Develop an AI-powered journal module that analyzes employee journal entries using multilingual NLP, emotion detection, and sentiment analysis, then stores the results in a PostgreSQL database.

### Model Used
- Hugging Face Transformer Model (Emotion Detection)
- VADER Sentiment Analyzer
- PyTorch

### Emotion Detection Pipeline
Journal Entry → NLP Preprocessing → Language Detection → Emotion Detection → Confidence Score → Sentiment Analysis → Database Storage → Frontend Display

### Confidence Score
The confidence score is the highest prediction probability returned by the transformer model for the detected emotion.

### Sentiment Analysis
VADER computes:
- Positive Score
- Negative Score
- Neutral Score
- Compound Score

### Database Schema
Each journal record stores:
- User ID
- Journal Text
- Detected Language
- Predicted Emotion
- Confidence Score
- Compound Sentiment Score
- Timestamp

### API Endpoints
- `POST /emotion/predict`
- `POST /sentiment/analyze`
- `POST /journal/add`
- `GET /journal/history`

### Sample Input & Output

**Input**
```
Today I completed all my work and feel motivated.
```

**Output**
- Language: English
- Emotion: Joy
- Confidence: 94%
- Compound Sentiment: 0.91

### Observations
- Successfully integrated multilingual NLP with transformer-based emotion detection.
- VADER sentiment analysis complements emotion prediction.
- Results are stored in PostgreSQL and displayed through the frontend.


