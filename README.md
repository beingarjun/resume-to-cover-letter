# Resume to Cover Letter Generator

A free, locally-running Streamlit app that converts your resume into tailored cover letters using open-source AI models.

## Live Demo

![App Interface](screenshots/app-interface.png)

*Professional interface showing Hugging Face API integration, smart upload guidance, and comprehensive feature set*

## Features

- **Multiple Resume Formats**: Upload PDF, DOCX, or TXT files
- **Smart Matching**: Analyzes job descriptions for keyword optimization
- **Free AI**: Uses Hugging Face's free API with open-source models
- **Editable Output**: Tweak generated letters before export
- **Export Options**: Download as .docx or copy to clipboard
- **Smart Analysis**: Identifies missing keywords and potential gaps

## Quick Start

### 1. Install Dependencies

```bash
pip install -r requirements.txt
```

### 2. Set Up Free API (Optional)

For better results, get a free Hugging Face API token:

1. Sign up at [huggingface.co](https://huggingface.co)
2. Go to Settings → Access Tokens → Create new token
3. Set environment variable:

**Windows (PowerShell):**
```powershell
$env:HUGGINGFACE_API_TOKEN="your_token_here"
```

**macOS/Linux:**
```bash
export HUGGINGFACE_API_TOKEN="your_token_here"
```

### 3. Run the App

```bash
streamlit run app.py
```

## Usage

1. **Upload Resume**: Drag & drop or browse for your resume file
2. **Paste Job Description**: Copy the full job posting text
3. **Fill Details** (optional): Company name, role, hiring manager
4. **Generate**: Click the generate button
5. **Edit & Export**: Make tweaks and download as .docx

## Free API Options

The app supports multiple free AI services:

- **Hugging Face** (recommended): Free tier with good models
- **Local Mode**: Basic template-based generation (no API needed)
- **Ollama**: Run models locally (requires separate installation)

## Project Structure

```
Resume to Cover Letter/
├── app.py                 # Main Streamlit application
├── requirements.txt       # Python dependencies
├── README.md             # This file
├── .github/
│   └── copilot-instructions.md
└── .env.example          # Environment variables template
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

MIT License - feel free to use and modify!

## Troubleshooting

**API Issues**: Check your token and try the local mode fallback
**File Upload**: Ensure your resume is in PDF, DOCX, or TXT format
**Performance**: For faster results, use a Hugging Face token

---

**Ready to land your dream job?** Upload your resume and start generating tailored cover letters!