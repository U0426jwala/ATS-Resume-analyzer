# 📄 AI Powered Resume Analyzer 📄

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Gradio](https://img.shields.io/badge/Gradio-Latest-orange.svg)](https://gradio.app/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Database-green.svg)](https://www.mongodb.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> 🚀 **Transform your job application process with AI-powered resume analysis, cover letter generation, and interview preparation!**

## ✨ Features

### 🎯 **Resume Analysis**
- **ATS-Optimized Scoring**: Get precise match percentages against job descriptions
- **Keyword Analysis**: Identify missing keywords crucial for ATS systems
- **Comprehensive Feedback**: Detailed analysis of Impact, Brevity, Style, and Sections
- **Smart Recommendations**: Actionable suggestions with examples for improvement

### 📝 **Content Enhancement**
- **ATS Content Rephraser**: Transform your content to pass ATS screening
- **Quantifiable Improvements**: Add measurable achievements to your resume
- **Professional Formatting**: Ensure consistent and professional presentation

### 💼 **Job Application Tools**
- **AI Cover Letter Generator**: Create tailored cover letters for specific positions
- **Interview Questions Generator**: Get probable interview questions based on job descriptions
- **Multi-format Support**: Works with PDF and DOCX resume formats

### 📊 **Data Management**
- **MongoDB Integration**: Store and track your analysis history
- **Performance Tracking**: Monitor your resume improvement over time

## 🛠️ Installation

### Prerequisites
- Python 3.8 or higher
- MongoDB database
- Groq API key

### Quick Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ATS-Resume-Analyzer.git
   cd ATS-Resume-Analyzer
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the root directory:
   ```env
   MONGO_URI=your_mongodb_connection_string
   MONGO_DB=resume_analyzer
   MONGO_COLLECTION=analysis_results
   GROQ_API_KEY=your_groq_api_key
   ```

4. **Run the application**
   ```bash
   python app.py
   ```

## 📦 Requirements

Create a `requirements.txt` file with the following dependencies:

```txt
gradio
groq
PyPDF2
python-docx
pymongo
python-dotenv
```

## 🚀 Usage

### 1. Resume Analysis
- Upload your resume (PDF/DOCX format)
- Enter the job description (optional)
- Choose analysis type:
  - **With Job Description**: Get ATS match percentage and keyword analysis
  - **Without Job Description**: Get general resume improvement suggestions
- Click "Analyze Resume" for detailed feedback

### 2. Content Rephrasing
- Paste any text that needs ATS optimization
- Get rephrased content with quantifiable measures
- Improve bullet points for better ATS screening

### 3. Cover Letter Generation
- First analyze your resume with a job description
- Navigate to Cover Letter tab
- Generate a tailored cover letter automatically

### 4. Interview Preparation
- Enter the job description
- Get 10 probable interview questions
- Includes technical, behavioral, and cultural fit questions

## 🎨 Interface Preview

The application features a modern dark theme with:
- **Intuitive Tab Navigation**: Easy switching between features
- **Real-time Processing**: Instant feedback and results
- **Responsive Design**: Works on desktop and mobile devices
- **Professional Styling**: Clean and user-friendly interface

## 🔧 Configuration

### Temperature & Token Settings
- **Temperature**: Controls creativity (0-1, default: 0.5)
- **Max Tokens**: Response length (50-1024, default: 1024)

### MongoDB Setup
Ensure your MongoDB instance is running and accessible with the connection string in your `.env` file.

## 📊 API Integration

The application uses:
- **Groq API**: For AI-powered text generation and analysis
- **MongoDB**: For storing analysis results and user data
- **Gradio**: For the web interface

## 🔒 Security Notes

- Keep your API keys secure and never commit them to version control
- Use environment variables for all sensitive configuration
- Regularly rotate your API keys for security

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Ujwala Kusma**
- LinkedIn: [Ujwala Kusma](https://www.linkedin.com/in/ujwala-kusma-77748a246/)

## 🙏 Acknowledgments

- Thanks to the Groq team for their powerful AI API
- Gradio team for the excellent web interface framework
- MongoDB for reliable data storage solutions

## 🐛 Issues & Support

If you encounter any issues or have questions:
1. Check the [Issues](https://github.com/U0426jwala/ATS-Resume-Analyzer/issues) page
2. Create a new issue with detailed description
3. Include error messages and steps to reproduce

## 🔄 Changelog

### v1.0.0
- Initial release with core ATS analysis features
- Resume analysis with and without job descriptions
- Content rephrasing functionality
- Cover letter generation
- Interview questions generation
- MongoDB integration

---

⭐ **If you found this project helpful, please give it a star!** ⭐

---

<div align="center">
  <strong>Built with ❤️ for job seekers worldwide</strong>
</div>
