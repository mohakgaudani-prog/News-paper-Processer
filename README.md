# Daily Newspaper Processor

A sophisticated web application for processing daily newspapers, extracting business and investing news, and generating comprehensive PDF reports with AI-powered analysis.

## 🌟 Features

### Core Functionality
- **Multi-format File Support**: Upload PDF, TXT, DOC, DOCX files via drag-and-drop or file browser
- **AI-Powered Article Analysis**: Automatic extraction and analysis of business/investing news
- **Smart Categorization**: Articles automatically categorized into Business, Investing, Technology, Health, or Important
- **Sentiment Analysis**: AI-powered sentiment detection (positive/negative/neutral) with confidence scores
- **Investment Potential Scoring**: Analysis of investment opportunities mentioned in articles

### Advanced Analytics
- **Interactive Charts**: Category distribution (doughnut chart) and daily article trends (line chart)
- **Business Metrics Dashboard**: Real-time statistics on total articles, business relevance, investment focus
- **Article-Specific Analysis**: Radar charts showing importance scores, sentiment analysis charts
- **Search & Filter**: Advanced filtering by category and keyword search functionality

### PDF Export
- **Comprehensive Reports**: Generate professional PDF reports with full article content
- **Color-Coded Visuals**: Charts and graphs embedded in PDF exports
- **Executive Summaries**: Automated summary generation with key metrics and highlights
- **Custom Formatting**: Professional layout with headers, sections, and visual elements

## 🚀 Live Demo

Access the application: [Live Demo](https://your-username.github.io/newspaper-processor)

## 📋 How to Use

### 1. Upload Files
- Drag and drop newspaper files into the upload zone
- Or click "Browse Files" to select files manually
- Supported formats: PDF, TXT, DOC, DOCX

### 2. Process Articles
- Click "Process Articles" to analyze uploaded files
- AI will extract and categorize articles automatically
- Business and investing news will be highlighted

### 3. View Results
- Browse processed articles in the main dashboard
- Use filters to find specific categories
- Click on articles to view detailed analysis

### 4. Generate Reports
- Click "Export PDF" to create comprehensive reports
- PDFs include full article content, charts, and analysis
- Reports are saved as "newspaper-report.pdf"

## 🛠️ Technical Stack

- **Frontend**: HTML5, Tailwind CSS, vanilla JavaScript
- **Charts**: Chart.js for interactive visualizations
- **PDF Generation**: jsPDF library for report generation
- **Data Storage**: RESTful Table API for article persistence
- **Styling**: Modern gradient design with responsive layout

## 📊 Data Model

### Articles Table Schema
- `id`: Unique identifier
- `title`: Article headline
- `content`: Full article text
- `summary`: AI-generated summary
- `key_points`: Extracted key points
- `category`: Article category (business/investing/technology/health/important)
- `importance_score`: AI-calculated importance (0-100%)
- `business_relevance`: Business relevance score (0-100%)
- `investing_focus`: Investment focus score (0-100%)
- `sentiment`: Sentiment analysis (positive/negative/neutral)
- `sentiment_score`: Sentiment confidence score
- `investment_potential`: Investment potential rating (high/medium/low)
- `confidence`: AI confidence level (0-1)
- `processed_at`: Processing timestamp
- `file_name`: Source file name

## 🎯 Key Features Implemented

### ✅ Completed Features
1. **Enhanced PDF Processing**: Full article extraction with formatting preservation
2. **AI-Powered Analysis**: Business/investing relevance scoring and sentiment analysis
3. **Interactive Charts**: Category distribution, daily trends, and sentiment visualization
4. **Professional PDF Export**: Color-coded reports with embedded charts and executive summaries
5. **Modern UI/UX**: Responsive design with gradients and modern styling

### 📈 Analytics Capabilities
- **Business Intelligence**: Automated scoring of business relevance (0-100%)
- **Investment Analysis**: Focus scoring for investment opportunities
- **Sentiment Tracking**: Positive/negative/neutral sentiment with confidence levels
- **Trend Analysis**: Daily article processing trends and category distribution
- **Performance Metrics**: Real-time dashboard with key performance indicators

## 🔧 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/newspaper-processor.git
cd newspaper-processor
