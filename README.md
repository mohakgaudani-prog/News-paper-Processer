# 📰 NewsAnalyzer AI

> **Transform newspaper PDFs into comprehensive business intelligence reports powered by Claude AI**

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18-61dafb.svg)
![Claude](https://img.shields.io/badge/Claude-Sonnet%204-purple.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

## 🌟 Live Demo

**[Try it now →](https://yourusername.github.io/newsanalyzer-ai)**

---

## 📋 Overview

NewsAnalyzer AI is a powerful web application that analyzes newspaper PDFs and generates detailed business, investor, and market analysis reports. Built with React and powered by Anthropic's Claude AI, it provides comprehensive insights without summarization.

### ✨ Key Features

- 📄 **PDF Upload & Analysis** - Direct newspaper PDF processing
- 🤖 **AI-Powered Insights** - Leverages Claude Sonnet 4 for deep analysis
- 💼 **Business Focus** - Specialized in business, investment, and market trends
- 📊 **Chart Recommendations** - Suggests relevant visualizations
- 🖼️ **Visual Content Ideas** - Recommends supporting images
- 💡 **Key Insights** - Extracts actionable takeaways
- ⬇️ **Downloadable Reports** - Export analysis as text files
- 🔒 **Privacy First** - No data stored on servers
- 📱 **Fully Responsive** - Works on desktop, tablet, and mobile

---

## 🚀 Quick Start

### 1. Get an API Key

Before using the application, you need an Anthropic API key:

1. Visit [console.anthropic.com](https://console.anthropic.com)
2. Sign up for a free account
3. Navigate to "API Keys" section
4. Create a new API key
5. Copy your key (starts with `sk-ant-...`)

**Free Tier:** New accounts receive $5 in free credits!

### 2. Use the Application

1. Visit the [live demo](https://yourusername.github.io/newsanalyzer-ai)
2. Enter your Anthropic API key
3. Upload a newspaper PDF
4. Click "Start Deep Analysis"
5. View and download your comprehensive report

---

## 💻 Local Development

### Prerequisites

- Modern web browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- Text editor (VS Code, Sublime, etc.)
- Git (optional)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/newsanalyzer-ai.git
   cd newsanalyzer-ai
   ```

2. **Open the file**
   ```bash
   # Simply open index.html in your browser
   open index.html  # macOS
   start index.html # Windows
   xdg-open index.html # Linux
   ```

That's it! No build process, no npm install, no dependencies to manage.

---

## 🌐 Deployment

### GitHub Pages (Recommended)

1. **Create a GitHub repository**
   ```bash
   git init
   git add index.html
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/newsanalyzer-ai.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to "Pages" section
   - Select "main" branch as source
   - Click "Save"
   - Your site will be live at: `https://yourusername.github.io/newsanalyzer-ai`

### Alternative Hosting Options

**Netlify**
- Drag and drop `index.html` to [netlify.com/drop](https://app.netlify.com/drop)
- Instant deployment!

**Vercel**
- Install Vercel CLI: `npm i -g vercel`
- Run: `vercel` in project directory
- Follow prompts

**Any Web Server**
- Upload `index.html` to any web hosting service
- Works with Apache, Nginx, or any static file server

---

## 📖 Usage Guide

### Step 1: API Key Setup

On your first visit, you'll see the API key entry screen:

![API Key Screen](https://via.placeholder.com/800x500?text=API+Key+Entry+Screen)

Enter your Anthropic API key and click "Save & Continue". Your key is stored locally in your browser's localStorage.

### Step 2: Upload PDF

![Upload Screen](https://via.placeholder.com/800x500?text=PDF+Upload+Screen)

Click the upload area or drag and drop your newspaper PDF file.

### Step 3: Analyze

![Analysis Screen](https://via.placeholder.com/800x500?text=Analysis+Progress)

Click "Start Deep Analysis" and wait 30-60 seconds for processing.

### Step 4: Review Results

![Results Screen](https://via.placeholder.com/800x500?text=Analysis+Results)

Review the comprehensive report with:
- Market Overview
- Business News Analysis
- Investment Insights
- Economic Indicators
- Chart & Visual Recommendations
- Key Insights
- Actionable Recommendations

### Step 5: Download

Click "Download" to save the report as a text file for future reference.

---

## 🏗️ Architecture

### Tech Stack

- **Frontend Framework:** React 18
- **Styling:** Tailwind CSS
- **AI Engine:** Anthropic Claude Sonnet 4
- **Build Tool:** None (uses CDN resources)
- **Deployment:** Static hosting (GitHub Pages, Netlify, etc.)

### Project Structure

```
newsanalyzer-ai/
├── index.html          # Single-file application
└── README.md          # This file
```

### Key Technologies

| Technology | Purpose | Source |
|------------|---------|--------|
| React 18 | UI Framework | unpkg.com CDN |
| React DOM 18 | React Rendering | unpkg.com CDN |
| Babel Standalone | JSX Compilation | unpkg.com CDN |
| Tailwind CSS | Styling | cdn.tailwindcss.com |
| Claude API | AI Analysis | api.anthropic.com |

---

## 🔧 Configuration

### API Settings

The application uses these default API settings:

```javascript
model: 'claude-sonnet-4-20250514'
max_tokens: 4000
anthropic-version: '2023-06-01'
```

### Customization

To modify the analysis prompt, edit the `text` field in the API request (around line 180 in `index.html`):

```javascript
text: `Analyze this newspaper PDF with deep research focus...`
```

---

## 💰 Cost Information

### Anthropic API Pricing

| Tier | Input Cost | Output Cost |
|------|-----------|-------------|
| Standard | ~$3/million tokens | ~$15/million tokens |

### Estimated Costs Per Analysis

| PDF Size | Estimated Cost |
|----------|---------------|
| Small (1-5 pages) | $0.01 - $0.05 |
| Medium (5-20 pages) | $0.05 - $0.20 |
| Large (20+ pages) | $0.20 - $0.50 |

**Note:** New accounts receive $5 in free credits, enough for 25-500 analyses depending on PDF size.

---

## 🔒 Privacy & Security

### Data Handling

- ✅ **API Key:** Stored locally in browser localStorage only
- ✅ **PDF Files:** Sent directly to Anthropic API, never stored on servers
- ✅ **Analysis Results:** Kept in browser memory, not persisted
- ✅ **No Backend:** Completely client-side application
- ✅ **No Tracking:** Zero analytics or tracking scripts

### Security Best Practices

1. **Never share your API key** with others
2. **Use HTTPS hosting** (GitHub Pages provides this automatically)
3. **Clear API key** when using public computers (click "Change API Key")
4. **Monitor API usage** at [console.anthropic.com](https://console.anthropic.com)
5. **Rotate keys regularly** for enhanced security

---

## 🐛 Troubleshooting

### Common Issues

**Problem:** "Failed to fetch" error
- **Solution:** Verify API key is correct
- Check internet connection
- Ensure API key is active at console.anthropic.com

**Problem:** PDF not uploading
- **Solution:** Ensure file is a valid PDF format
- Try a smaller file (under 10MB recommended)
- Check file isn't corrupted

**Problem:** Analysis takes too long
- **Solution:** Large PDFs may take 30-60 seconds
- Complex content requires more processing time
- Check your API quota hasn't been exceeded

**Problem:** JSON parsing error
- **Solution:** Retry the analysis
- System has automatic fallback for non-JSON responses

**Problem:** API key not saving
- **Solution:** Check browser allows localStorage
- Try in a different browser
- Disable strict privacy/cookie blocking

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Reporting Bugs

1. Check if the issue already exists in [Issues](https://github.com/yourusername/newsanalyzer-ai/issues)
2. Create a new issue with:
   - Clear title and description
   - Steps to reproduce
   - Expected vs actual behavior
   - Screenshots (if applicable)
   - Browser and OS information

### Suggesting Features

1. Open an issue with the "enhancement" label
2. Describe the feature and its benefits
3. Provide examples or mockups if possible

### Pull Requests

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Make your changes
4. Test thoroughly
5. Commit changes (`git commit -m 'Add AmazingFeature'`)
6. Push to branch (`git push origin feature/AmazingFeature`)
7. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2026 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Acknowledgments

- **Anthropic** for providing the Claude API
- **React Team** for the amazing framework
- **Tailwind CSS** for the utility-first CSS framework
- **Open Source Community** for inspiration and support

---

## 📞 Support

### Get Help

- 📧 **Email:** support@yourproject.com
- 💬 **Discord:** [Join our community](https://discord.gg/yourserver)
- 🐦 **Twitter:** [@yourhandle](https://twitter.com/yourhandle)
- 📖 **Documentation:** [Read the docs](https://yourusername.github.io/newsanalyzer-ai/docs)

### Anthropic API Support

- 📚 **Documentation:** [docs.anthropic.com](https://docs.anthropic.com)
- 💌 **Email:** support@anthropic.com

---

## 🗺️ Roadmap

### Version 1.1 (Coming Soon)
- [ ] Multi-language support
- [ ] Export to PDF format
- [ ] Batch processing for multiple PDFs
- [ ] Custom analysis templates

### Version 2.0 (Future)
- [ ] Interactive charts generation
- [ ] Historical analysis comparison
- [ ] Email report delivery
- [ ] API key encryption
- [ ] Team collaboration features

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yourusername/newsanalyzer-ai&type=Date)](https://star-history.com/#yourusername/newsanalyzer-ai&Date)

---

## 📊 Stats

![GitHub repo size](https://img.shields.io/github/repo-size/yourusername/newsanalyzer-ai)
![GitHub stars](https://img.shields.io/github/stars/yourusername/newsanalyzer-ai?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/newsanalyzer-ai?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/yourusername/newsanalyzer-ai?style=social)

---

<div align="center">

**Made with ❤️ by [Your Name](https://github.com/yourusername)**

**Powered by [Claude AI](https://www.anthropic.com/claude)**

[⬆ Back to Top](#-newsanalyzer-ai)

</div>
