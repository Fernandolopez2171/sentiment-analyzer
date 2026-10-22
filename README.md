# Sentiment Analyzer

**English** | [Español](README.es.md)

## Project Description

This project is a social media sentiment analysis system built with artificial intelligence (AI). It collects social media data, analyzes text to determine whether the sentiment is positive, negative, or neutral, and provides statistics and visualizations about users' opinions on specific topics or current trends.

## Project Structure

### Frontend
- **Framework:** Next.js
- **Styles:** Tailwind CSS

### Backend
- **API framework:** Next.js
- **AI:** Python

## Main Features
1. **Social Media Data Collection**
   - API for collecting comments from YouTube.

2. **Sentiment Analysis**
   - Natural language processing (NLP) algorithms to analyze publication text and determine sentiment.
   - A pre-trained AI model to identify positive, negative, and neutral sentiment.

3. **Statistics and Visualizations**
   - Statistics about overall user sentiment on specific topics.
   - Bar charts and heat maps to display sentiment distribution.

4. **User Interface**
   - An intuitive interface for exploring sentiment analysis results.
   - Search for specific topics, compare trends, and segment data.

## Installation

### Prerequisites
- Node.js
- Python 3.x
- pip

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/Fernandolopez2171/sentiment-analyzer.git
   cd sentiment-analyzer
   ```

2. Install frontend dependencies:
   ```sh
   cd Frontend
   npm install
   ```

3. Install backend dependencies:
   ```sh
   cd ..\Backend
   pip install -r requirements.txt
   ```

## Usage

### Frontend
1. Start the development server:
   ```sh
   cd Frontend
   npm run dev
   ```
2. Open `http://localhost:3000` in your browser.

### Backend
1. Start the AI backend:
   ```sh
   cd ..\Backend\BertModel
   python app.py
   ```

## Review
![Home](./Project_Review/Inicio.png)

![YouTube API](./Project_Review/ApiYoutube.png)

![Chart](./Project_Review/Grafica.png)

## Contributing

Contributions are welcome. Please fork the project, create a feature branch, commit your changes, push the branch, and open a pull request.
