# 🚀 Portfolio Website - Heet Patel

> Personal portfolio showcasing my journey as an AI/ML Engineer and Software Developer

[![Live Demo](https://img.shields.io/badge/Live-Demo-success?style=for-the-badge&logo=github)](https://hp161103.github.io/Portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/heetpatel16)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github)](https://github.com/HP161103)

---

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Sections](#sections)
- [Installation](#installation)
- [Customization](#customization)
- [License](#license)
- [Contact](#contact)

---

## 🎯 About

A modern, responsive portfolio website built to showcase my experience in Machine Learning, Data Science, and Software Engineering. This portfolio demonstrates both my technical capabilities and the real-world impact of projects I've built.

**Live Website:** [hp161103.github.io/Portfolio](https://hp161103.github.io/Portfolio/)

### Why This Portfolio?

- **Impact-Driven**: Every project includes quantifiable results ($240K revenue impact, 85% accuracy improvements, etc.)
- **Clean Design**: Modern, professional aesthetic with smooth animations
- **Fully Responsive**: Works seamlessly across desktop, tablet, and mobile devices
- **Performance Optimized**: Fast loading, accessible, and SEO-friendly
- **Easy to Navigate**: Clear sections with smooth scrolling and intuitive UX

---

## ✨ Features

- 🎨 **Modern UI/UX** - Clean, professional design with gradient accents
- 📱 **Fully Responsive** - Mobile-first approach, works on all screen sizes
- ⚡ **Smooth Animations** - AOS (Animate on Scroll) library integration
- 🎯 **Interactive Projects** - Filterable portfolio with hover effects
- 📊 **Impact Metrics** - Quantified results for each project
- 🌙 **Professional Theme** - Consistent color scheme and typography
- 🔗 **Social Integration** - Direct links to GitHub, LinkedIn, LeetCode
- 📄 **Downloadable Resume** - One-click resume download
- 🚀 **Fast Loading** - Optimized assets and lazy loading

---

## 🛠️ Tech Stack

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox & Grid
- **JavaScript** - Interactive functionality
- **Bootstrap 5** - Responsive framework
- **AOS Library** - Scroll animations
- **Typed.js** - Dynamic typing effect
- **GLightbox** - Image gallery
- **Swiper** - Touch slider

### Design
- **Bootstrap Icons** - Icon library
- **Google Fonts** - Roboto, Open Sans, Quicksand
- **Custom CSS** - Tailored styling and animations

### Deployment
- **GitHub Pages** - Free hosting
- **Custom Domain** - heetpatel.ai (optional)

---

## 📑 Sections

### 1. **Hero Section**
- Dynamic typing animation showcasing roles (AI/ML Engineer, Software Developer, Data Scientist)
- Professional introduction with impact statement
- Call-to-action buttons (View Work, Get in Touch, Download Resume)
- Social media links
- Animated statistics (Projects Completed, Years Experience)

### 2. **Skills Section**
- Categorized skill cards (Core Tech Stack, Machine Learning, Deep Learning, Generative AI)
- Progress bars showing proficiency levels
- Professional expertise summary
- Certification badges with links to credentials
- Statistics showcase (Years Experience, Projects Completed)

### 3. **Resume Section**
- **Professional Journey**: Timeline of work experience with achievements
  - Quantum Tree Tech (Software Engineering Intern - Generative AI)
  - CreArt (Software Engineering Intern)
- **Academic Excellence**: Education timeline
  - MS Computer Science @ Northeastern University
  - BE Information Technology @ Sal Engineering Institute
  - Coursera Certifications (Machine Learning, Deep Learning)

### 4. **Projects Section** ⭐
- **Filterable portfolio** (All, ML, DL, GenAI, Full-Stack)
- **6 featured projects** with:
  - Project category and title
  - Clear description
  - **Impact metrics** (quantified results)
  - Tech stack tags
  - GitHub repository links
- **Hover animations** with border effects
- **Responsive grid layout**

**Featured Projects:**
1. **User Churn Prediction System** - 35% churn reduction, $240K impact
2. **Product Analytics Dashboard** - 40% retention boost, 100K+ users
3. **RAG Content Analyzer** - 85% accuracy, 500+ daily users
4. **Email Automation Platform** - $75K saved, 90% efficiency
5. **Real-Time Object Detection** - 89% mAP, 30 FPS
6. **Distributed Web Service** - 99.9% uptime, 100K+ requests/day

### 5. **Contact Section**
- Contact information (Location, Phone, Email, LinkedIn)
- Direct communication channels
- Professional layout

---

## 🚀 Installation

### Prerequisites

```bash
- Git
- Web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.)
```

### Local Setup

1. **Clone the repository**
```bash
git clone https://github.com/HP161103/Portfolio.git
cd Portfolio
```

2. **Open in browser**
```bash
# Simply open index.html in your browser
# Or use a local server:

# Python
python -m http.server 8000

# Node.js (if you have live-server)
npx live-server

# VS Code (Live Server extension)
# Right-click index.html > Open with Live Server
```

3. **View the site**
```
Open browser to: http://localhost:8000
```

### Deployment to GitHub Pages

1. **Push to GitHub**
```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

2. **Enable GitHub Pages**
- Go to repository Settings
- Navigate to Pages section
- Source: Deploy from branch
- Branch: main / (root)
- Save

3. **Access your site**
```
https://hp161103.github.io/Portfolio/
```

---

## 🎨 Customization

### Update Personal Information

**1. Contact Details** (`index.html`)
```html
<!-- Find and update: -->
- Phone number
- Email address
- Location
- LinkedIn URL
- GitHub URL
- LeetCode URL
```

**2. Hero Section**
```html
<!-- Update typed items: -->
<span class="typed" data-typed-items="AI/ML Engineer, Software Developer, Data Scientist"></span>

<!-- Update introduction paragraph -->
<p class="lead">Your compelling introduction here...</p>
```

**3. Resume/CV**
```html
<!-- Update resume link: -->
<a href="assets/resume.pdf" class="btn btn-outline" download>Download Resume</a>
```

### Add New Projects

**Copy this template in the projects grid:**

```html
<article class="project-card" data-category="YOUR-CATEGORY" data-aos="zoom-in">
  <a href="https://github.com/HP161103/YOUR-REPO" target="_blank" rel="noopener noreferrer" class="project-link">
    <div class="github-badge">
      <i class="bi bi-github"></i>
    </div>
    <div class="project-header">
      <span class="project-category">Your Category</span>
      <h3 class="project-title">Project Name</h3>
    </div>
    <p class="project-description">
      Brief description of what it does and why it matters.
    </p>
    <div class="project-impact">
      <div class="impact-metric">
        <i class="bi bi-icon-name"></i>
        <div class="metric-content">
          <span class="metric-value">XX%</span>
          <span class="metric-label">Metric Name</span>
        </div>
      </div>
      <!-- Add 2 more metrics -->
    </div>
    <div class="project-tech">
      <span class="tech-tag">Tech1</span>
      <span class="tech-tag">Tech2</span>
      <span class="tech-tag">Tech3</span>
    </div>
  </a>
</article>
```

### Color Customization

**Update accent color in CSS:**

```css
/* Find in assets/css/main.css and update: */
:root {
  --accent-color: #667eea;  /* Change to your preferred color */
}

/* Or update gradients: */
background: linear-gradient(135deg, #667eea, #764ba2);
```

**Popular color schemes:**
- **Blue/Purple**: `#667eea, #764ba2` (current)
- **Green/Blue**: `#11998e, #38ef7d`
- **Orange/Red**: `#f12711, #f5af19`
- **Pink/Purple**: `#ff9a9e, #fecfef`

---

## 📁 Project Structure

```
Portfolio/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── main.css       # Main stylesheet
│   ├── js/
│   │   └── main.js        # JavaScript functionality
│   ├── img/
│   │   ├── profile/       # Profile images
│   │   └── projects/      # Project screenshots (optional)
│   ├── vendor/            # Third-party libraries
│   │   ├── bootstrap/
│   │   ├── aos/
│   │   ├── typed.js/
│   │   ├── glightbox/
│   │   └── ...
│   └── resume.pdf         # Downloadable resume
├── README.md              # This file
└── LICENSE                # MIT License
```

---

## 🎓 Key Highlights

### Professional Experience
- **Quantum Tree Tech** (YC W24) - Software Engineering Intern, Generative AI
  - Built RAG pipelines with 85% accuracy improvement
  - Optimized systems achieving 90% performance boost
  - Served 500+ daily users
  
- **CreArt Solutions** - Software Engineering Intern
  - Developed full-stack automation platform
  - Saved $75K+ annually through efficiency improvements
  - Reduced manual operations by 90%

### Technical Skills
- **Languages**: Python, Java, JavaScript, TypeScript, SQL, C++, R
- **ML/AI**: TensorFlow, PyTorch, scikit-learn, XGBoost, Hugging Face, LangChain
- **Data Science**: Pandas, NumPy, SQL, Statistical Analysis, Data Visualization
- **Web**: React, Node.js, Django, FastAPI, HTML/CSS
- **DevOps**: Docker, Kubernetes, AWS, Git, CI/CD

### Education
- **MS Computer Science** - Northeastern University (Expected 2027)
- **BE Information Technology** - Sal Engineering Institute (2025)
- **Certifications** - Machine Learning (Stanford), Deep Learning (DeepLearning.AI)

---

## 🌟 Featured Projects

### 1. User Churn Prediction System
**Impact**: 35% churn reduction, $240K revenue impact, 87% model AUC
- Built ML pipeline with XGBoost achieving high predictive accuracy
- Conducted statistical analysis on 50K+ user records
- Implemented A/B testing framework for validation

### 2. Product Analytics Dashboard
**Impact**: 40% retention improvement, 100K+ users analyzed, 92% forecast accuracy
- Interactive Streamlit dashboard with cohort analysis
- Time-series forecasting with ARIMA models
- Real-time metrics visualization with Plotly

### 3. RAG Content Analyzer
**Impact**: 85% accuracy boost, 500+ daily users, sub-5s response time
- Retrieval-Augmented Generation with LangChain and FAISS
- Optimized text embeddings with HuggingFace transformers
- Scalable backend with FastAPI

### 4. Email Automation Platform
**Impact**: 90% time saved, $75K annual savings, 10K+ emails/month
- Full-stack application with Django backend
- Drag-and-drop template builder with JavaScript
- SendGrid API integration with delivery tracking

### 5. Real-Time Object Detection
**Impact**: 89% mAP, 30 FPS processing, 80% latency reduction
- YOLOv5 architecture with PyTorch
- CUDA-accelerated inference pipeline
- Real-time computer vision application

### 6. Distributed Web Service
**Impact**: 99.9% uptime, 100K+ requests/day, 75% query optimization
- Microservices architecture with Java and Go
- Redis caching and Kubernetes orchestration
- Comprehensive monitoring and alerting

---

## 📈 Performance

- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)
- **Page Load Time**: < 2 seconds
- **Mobile Friendly**: 100% responsive design
- **Cross-Browser**: Compatible with Chrome, Firefox, Safari, Edge

---

## 🤝 Contributing

While this is a personal portfolio, I welcome:
- Bug reports
- Suggestions for improvements
- Design feedback

Feel free to open an issue or reach out directly!

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

Feel free to use this as inspiration for your own portfolio, but please:
- Don't copy the content (projects, experience, personal info)
- Give credit if you use significant portions of the code
- Make it your own!

---

## 📬 Contact

**Heet Patel**

- 🌐 Website: [hp161103.github.io/Portfolio](https://hp161103.github.io/Portfolio/)
- 💼 LinkedIn: [linkedin.com/in/heetpatel16](https://linkedin.com/in/heetpatel16)
- 📧 Email: heetpatel16003@gmail.com
- 💻 GitHub: [github.com/HP161103](https://github.com/HP161103)
- 🧩 LeetCode: [leetcode.com/u/patelh2003](https://leetcode.com/u/patelh2003)

---

## 🙏 Acknowledgments

- **Design Inspiration**: Modern portfolio trends and best practices
- **Libraries Used**: 
  - [Bootstrap](https://getbootstrap.com/) - UI framework
  - [AOS](https://michalsnik.github.io/aos/) - Animate on scroll
  - [Typed.js](https://github.com/mattboldt/typed.js/) - Typing animation
  - [GLightbox](https://biati-digital.github.io/glightbox/) - Lightbox
  - [Bootstrap Icons](https://icons.getbootstrap.com/) - Icon set
  
---

## 💡 Future Enhancements

- [ ] Add dark mode toggle
- [ ] Include blog section for technical articles
- [ ] Add project demo videos
- [ ] Implement contact form backend
- [ ] Add more interactive visualizations
- [ ] Create case studies for major projects

---

## 📊 Stats

![GitHub Repo Size](https://img.shields.io/github/repo-size/HP161103/Portfolio?style=flat-square)
![GitHub Last Commit](https://img.shields.io/github/last-commit/HP161103/Portfolio?style=flat-square)
![GitHub Language Count](https://img.shields.io/github/languages/count/HP161103/Portfolio?style=flat-square)
![Visitors](https://visitor-badge.laobi.icu/badge?page_id=HP161103.Portfolio)

---

<div align="center">

### ⭐ If you find this portfolio inspiring, consider giving it a star!

**Built with 💻 and ☕ by Heet Patel**

[![GitHub Stars](https://img.shields.io/github/stars/HP161103/Portfolio?style=social)](https://github.com/HP161103/Portfolio/stargazers)

</div>

---

## 🔄 Changelog

### Version 2.0 (Current)
- Redesigned projects section with impact metrics
- Added filterable portfolio
- Enhanced hover animations
- Improved mobile responsiveness
- Updated professional experience
- Added new projects with quantified results

### Version 1.0
- Initial portfolio launch
- Basic sections: About, Skills, Projects, Contact
- Responsive design implementation
- AOS animations integration

---

*Last Updated: November 2024*
