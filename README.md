
# 🎯 ResumeX - AI-Powered Resume Analyzer

> **Smart feedback for your dream job** -Get AI-powered resume analysis, ATS scoring, and personalized improvement tips to land your next role.

![ResumeX Dashboard](public/readme/hero.webp)

## ✨ Features

### 🤖 AI-Powered Analysis
- **Comprehensive Resume Evaluation**: Get detailed feedback on content, structure, tone, and skills
- **ATS Compatibility Scoring**: Ensure your resume passes Applicant Tracking Systems
- **Job-Specific Feedback**: Tailored analysis based on specific job descriptions and company requirements
- **Visual Score Breakdown**: Easy-to-understand scoring system with actionable insights

### 📊 Detailed Feedback Categories
- **🎯 ATS Score**: Optimize for Applicant Tracking Systems
- **📝 Content Analysis**: Improve resume content quality and relevance
- **🏗️ Structure Evaluation**: Enhance resume layout and organization
- **🎨 Tone & Style**: Perfect your professional writing style


### 🔧 Technical Features
- **PDF Upload & Processing**: Seamless PDF resume upload with image conversion
- **Real-time Analysis**: Instant AI feedback powered by advanced language models
- **Resume History**: Track and compare multiple resume versions
- **Responsive Design**: Beautiful, mobile-friendly interface built with React and Tailwind CSS
- **Cloud Storage**: Secure resume storage and management via Puter.com

## 🚀 Quick Start

### Prerequisites
- Node.js 20+ 
- npm or yarn
- Puter.com account (for cloud storage and AI features)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/vaishnavirajj/ResumeX.git
   cd ResumeX
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to access the application.

### Production Build

```bash
# Build the application
npm run build

# Start the production server
npm run start
```

## 🐳 Docker Deployment

Build and run with Docker:

```bash
# Build the Docker image
docker build -t resumex .

# Run the container
docker run -p 3000:3000 resumex
```

## 🏗️ Project Structure

```
resumex/
├── app/
│   ├── components/          # Reusable UI components
│   │   ├── ATS.tsx         # ATS score display
│   │   ├── FileUploader.tsx # Resume upload component
│   │   ├── ScoreGauge.tsx  # Score visualization
│   │   └── ...
│   ├── routes/             # Application pages
│   │   ├── home.tsx        # Dashboard with resume history
│   │   ├── upload.tsx      # Resume upload and analysis
│   │   ├── resume.tsx      # Detailed feedback view
│   │   └── auth.tsx        # Authentication
│   ├── lib/                # Utility functions
│   │   ├── puter.ts        # Puter.com integration
│   │   ├── pdf2img.ts      # PDF processing
│   │   └── utils.ts        # Helper functions
│   └── app.css            # Global styles
├── constants/              # Application constants
├── types/                  # TypeScript type definitions
├── public/                 # Static assets
└── README.md
```

## 🛠️ Tech Stack

### Frontend
- **React 19** - Modern React with latest features
- **React Router 7** - File-based routing with SSR support
- **TypeScript** - Type-safe development
- **Tailwind CSS 4** - Utility-first styling
- **Vite** - Fast build tool and dev server

### Backend & Services
- **Puter.com** - Cloud storage, authentication, and AI services
- **PDF.js** - Client-side PDF processing
- **React Dropzone** - File upload handling

### State Management
- **Zustand** - Lightweight state management

## 📋 Usage Guide

### 1. Authentication
- Sign in with your Puter.com account to access all features
- New users can create an account instantly

### 2. Upload Resume
- Navigate to the upload page
- Fill in job details (company name, job title, job description)
- Upload your PDF resume
- Click "Analyze Resume" to start the AI analysis

### 3. Review Feedback
- View your overall score and detailed breakdown
- Read specific tips for each category
- Download or share your analysis results

### 4. Track Progress
- Access your resume history from the dashboard
- Compare different versions and improvements
- Monitor your progress over time

## 🎨 Features in Detail

### ATS Scoring System
The application evaluates resumes based on:
- **Keyword Optimization**: Alignment with job requirements
- **Format Compatibility**: ATS-friendly formatting
- **Section Organization**: Proper resume structure
- **Content Relevance**: Job-specific content analysis

### AI-Powered Feedback
- **Content Analysis**: Evaluates work experience, achievements, and descriptions
- **Structure Review**: Assesses resume layout, sections, and organization
- **Tone Assessment**: Analyzes professional writing style and language
- **Skills Evaluation**: Matches skills with job requirements

## 🔒 Privacy & Security

- All resume data is securely stored on Puter.com's cloud infrastructure
- User authentication ensures data privacy
- Files are processed client-side when possible
- No resume content is shared with third parties

## 🤝 Contributing

We welcome contributions! Please see our contributing guidelines:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Puter.com** for providing cloud storage and AI services
- **PDF.js** for client-side PDF processing
- **React Router** team for the excellent routing solution
- **Tailwind CSS** for the utility-first CSS framework

## 📞 Support

- 📧 Email: vaishnaviraj950@gmail.com
- 🐛 Issues: [GitHub Issues](https://github.com/vaishnavirajj/ResumeX/issues)

---

**Made with ❤️ by the Vaishnavi Raj**

*Transform your resume, transform your career!*
