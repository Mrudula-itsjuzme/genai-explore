# Mudi - AI-Powered Mental Health Companion

Mudi is a comprehensive mental health companion application that combines journaling, AI-powered chat support, mood tracking, playlist generation, and generative art creation to support emotional well-being.

## Core Features

1. **Journaling**: Securely write and manage entries with associated mood tags.
2. **AI Chatbot**: A RAG-grounded companion that provides support based on recent journal entries.
3. **Mood Calendar**: Visual analytics for daily mood tracking over time.
4. **Playlist Generation**: Personalized music recommendations based on the user's current mood.
5. **Generative Art**: Creation of anonymous art pieces derived from journal content.

## Tech Stack

- **Frontend**: React (Vite) with Tailwind CSS and Recharts for data visualization.
- **Backend**: FastAPI for a robust Python-based API.
- **Storage**: SQLite for relational data and Chroma for vector embeddings.
- **AI/ML**: Sentence Transformers for embeddings, with LLM support from OpenAI or Gemini.
- **Art Generation**: Stable Diffusion (Diffusers) for unique visual creations.
- **Infrastructure**: Containerized using Docker and Docker Compose.

## Installation and Setup

1. **Clone the repository**:
   Navigate to your local project directory.
2. **Build and Run**:
   ```bash
   docker-compose up --build
   ```
3. **Access the Application**:
   - Web Interface: [http://localhost:3000](http://localhost:3000)
   - API Documentation: [http://localhost:8000/docs](http://localhost:8000/docs)

## Privacy and Data Security

- Entries remain private unless explicitly shared.
- Sharing of generative art is anonymized by default.
- Mood inference is based solely on text input.
- Designed with content moderation and data export options.

## Disclaimer

Mudi is built for mental health awareness and support. It is not a substitute for professional medical advice, diagnosis, or treatment.