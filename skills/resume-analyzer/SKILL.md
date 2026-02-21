---
name: resume-analyzer
description: AI-powered Resume Analyzer that scores resumes against job descriptions. Use when users want to check resume quality, ATS compatibility, keyword matching, or get improvement suggestions. Deploys as a static web app on Vercel/Netlify for free.
---

# Resume Analyzer

An AI-powered resume analysis tool that scores resumes, checks ATS compatibility, and provides improvement suggestions.

## Features
- Paste resume text and get instant scoring (0-100)
- ATS keyword matching against job descriptions
- Section-by-section analysis (Experience, Skills, Education, Format)
- Actionable improvement suggestions
- Export report as PDF

## Tech Stack
- Single HTML file with vanilla JS + Tailwind CSS via CDN
- Claude API integration for AI analysis (called from frontend artifact)
- Deploy free on Vercel / Netlify / GitHub Pages

## Trigger Phrases
- "analyze my resume"
- "check resume score"
- "is my resume ATS friendly"
