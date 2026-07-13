# DevVistaPersonalPortfolio


**Live Demo**: https://devvista-app.s3-website-us-east-1.amazonaws.com

A responsive portfolio website with 3 professional templates. Built as part of DevVista - AI Powered Portfolio Generator.

## ✨ Features
- **3 Templates**: Nexus for Developers, Forge for Designers, Prism for Freelancers
- **Fully Responsive**: Optimized for Mobile, Tablet, and Desktop
- **Modern UI/UX**: Clean design with smooth animations
- **AWS Deployed**: Hosted on Amazon S3 for fast and reliable access
- **Easy Customization**: Pure HTML, CSS, and JavaScript

## 🛠️ Tech Stack
- **Frontend**: HTML5, CSS3, JavaScript
- **Hosting**: AWS S3 Static Website Hosting
- **Design**: Responsive Web Design, Mobile-First Approach
## Project Structure
DevVista/
│
├── index.html                 # Landing page
├── login.html                 # Signup / Login page
├── script.js                  # Wizard logic + template generation
├── style.css                  # Global styling
├── logo.jpg                   # Brand logo
│
├── assets/                    # Template preview images
│   ├── t1_thumb.png           # Nexus template preview
│   ├── t2_thumb.png           # Forge template preview
│   └── t3_thumb.png           # Prism template preview
│
├── templates/                 # Portfolio Templates
│   ├── nexus/
│   │   └── index.html         # Template 1: Nexus
│   ├── forge/
│   │   └── index.html         # Template 2: Forge
│   └── prism/
│       └── index.html         # Template 3: Prism
│
└── backend/                   # AWS Lambda Functions
    ├── auth/
    │   ├── index.mjs          # Lambda function - Auth logic
    │   └── package.json       # Dependencies
    └── node_modules/
        └── bcryptjs/


## 🚀 Deployment
This project is deployed on AWS S3:
1. Built static HTML/CSS/JS files
2. Uploaded to S3 bucket: `devvista-app`
3. Enabled Static Website Hosting
4. Live at: https://devvista-app.s3-website-us-east-1.amazonaws.com

## 👩‍💻 My Role
**Frontend Developer**
- Designed and developed all 3 portfolio templates
- Implemented responsive layouts for all devices
- Handled UI/UX and deployed project on AWS S3

## 📌 Future Improvements
- Add dark/light mode toggle
- Add more template variations
- Integrate with backend for dynamic content

---
Made with ❤️ as part of DevVista Project
