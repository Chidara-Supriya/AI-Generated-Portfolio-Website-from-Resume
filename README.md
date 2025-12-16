AI-Generated Portfolio Website from Resume

An end-to-end AI-powered application that automatically converts a PDF or DOCX resume into a fully functional, professional portfolio website.
The system uses LLMs, prompt engineering, and automation to generate production-ready HTML, CSS, and JavaScript with live preview and download support.

📌 Project Overview

Building a portfolio website typically requires frontend skills, design experience, and significant manual effort.
This project eliminates those barriers by leveraging Generative AI to transform a resume into a complete personal website — automatically.

Resume → AI Understanding → Website Code → Preview → Deployable ZIP

✨ Key Features

📄 Upload resume in PDF or DOCX format

🧠 AI-powered resume understanding & prompt generation

💻 Automatic generation of HTML, CSS, and JavaScript

🌐 Live website preview inside Streamlit

📦 Downloadable ZIP with production-ready files

🎨 Clean, professional, multi-section portfolio layout
🧠 System Architecture

Streamlit UI – Resume upload & preview

Resume Parser – Extracts text using PyPDF2 / python-docx

LLM #1 – Converts resume content into structured website prompt

LLM #2 – Generates complete website source code

Preview Engine – Renders HTML inside Streamlit

ZIP Exporter – Bundles files for deployment
🔄 Workflow

User uploads resume (PDF/DOCX)

Resume text is extracted

LLM generates structured website content

LLM generates HTML/CSS/JS code

Website preview is rendered

ZIP file is generated for download
📂 Example Output Files
index.html   # Website structure
style.css    # Layout & theme
script.js    # Interactivity
🔮 Future Enhancements

Multiple portfolio themes

AI-based resume entity extraction (NER)

Profile photo upload

Animated templates

One-click deployment to GitHub Pages / Netlify
📌 Skills Demonstrated

Generative AI • Prompt Engineering • LLM Integration • Python • Streamlit • Automation • Resume Parsing • Full-Stack Development
