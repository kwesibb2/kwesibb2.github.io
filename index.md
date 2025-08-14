---
layout: default
title: Kwesi Boahene:
---
<style>
/* Global typography */

/* Headings */
h1, h2, h3 {
  font-weight: 700;
  color: #ffffff;
}

/* Accent links */
a {
  color: #4f9cf9;
  text-decoration: none;
  transition: color 0.2s;
}
a:hover {
  color: #f39c12;
  text-decoration: underline;
}

/* Project card styling */
.project-card {
  background-color: #1e1e1e;
  border: 1px solid #333;
  padding: 1.5rem;
  border-radius: 8px;
  margin-bottom: 1.5rem;
  transition: transform 0.2s, box-shadow 0.2s;
}
.project-card:hover {
  transform: scale(1.02);
  box-shadow: 0 4px 12px rgba(0,0,0,0.3);
}

</style>

# Kwesi Boahene

**Aspiring Data Analyst | Data Scientist | Machine Learning Enthusiast**  
Econometrics & Quantitative Economics graduate from UIUC with minors in Computer Science and Statistics.  
Interested in applying data-driven insights to **finance, operations, retail, sports analytics, and AI/ML applications**.

---


## Interests
- Predictive modeling and forecasting for finance and retail
- Optimization and analytics in operations and supply chain
- Sports performance and game outcome analytics
- Machine learning applications, AI pipelines, and data-driven decision-making

---

## Skills

- Programming & Data Tools: Python, R, SQL, C++, Excel, Tableau, Power BI  
- Data Science & ML: Time Series Analysis, Forecasting Models, Econometrics, Lasso Regression, Statistical Modeling  
- Visualization: Matplotlib, ggplot2, Plotly, Tableau, Power BI  
- Cloud & Collaboration: Git, Docker, AWS, GCP  
- Other: Data Wrangling, EDA, Model Evaluation (RMSE, Cross-validation), Experimental Design  


---

## Projects

### [📊 Walmart Sales Forecasting](https://github.com/kwesibb2/Walmart-Sales)
State-level sales prediction with ARMA and Lasso models, RMSE evaluation, and insights for inventory and workforce optimization.  
*Tech stack:* R, RMarkdown, glmnet, plotly, HTML 

### [🤖 Machine Learning Trading Bot](https://github.com/yourusername/project-link)
An automated options trading bot with backtesting and risk management.  
*Tech stack:* Python, QuantConnect API, Scikit-learn

### [📈 Sales Dashboard](https://github.com/yourusername/project-link)
Interactive business intelligence dashboard for tracking KPIs.  
*Tech stack:* Tableau, SQL, Excel

---

## 📫 Contact

- **Email:** pkwesi4@gmail.com 


---

Lovable
6:09 PM on Aug 14

Thought for 10 seconds
I'll create a modern, sleek dark-themed portfolio page inspired by the Jekyll Slate theme. This will be a beautiful, professional GitHub portfolio that showcases your data science expertise.

Show all
Editing
src/components/portfolio/projects-section.tsx
This message was cancelled.



Umm also I just want it in the index.md file. I already have a config.yml that selects the jerkyll theme I just want a few overrides to make it look better nothing complicated I am new to this
Lovable
6:10 PM on Aug 14

Thought for 7 seconds
I understand you want to improve your Jekyll site's styling, but I'm in a React/Vite environment and can't directly edit Jekyll markdown files.

I can create a modern dark portfolio page in React that you could use as inspiration for your Jekyll CSS overrides, or help you understand what specific CSS changes would improve your current Jekyll setup.

Would you prefer:

A React version you can reference for styling ideas
Specific CSS suggestions for your Jekyll index.md file
Which approach would be more helpful for your Jekyll site?




Don't edit just give .2 that I can copy and paste
Lovable
6:10 PM on Aug 14

Thought for 5 seconds
Here's improved CSS you can copy-paste to replace your current styles in your Jekyll index.md file:


<style>
/* Import modern font */
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');

/* Global styling */
body {
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
  line-height: 1.7;
  color: #e2e8f0;
  background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
  min-height: 100vh;
  margin: 0;
  padding: 2rem;
}

/* Container */
.container {
  max-width: 800px;
  margin: 0 auto;
}

/* Typography */
h1 {
  font-size: 2.5rem;
  font-weight: 700;
  color: #f8fafc;
  margin-bottom: 0.5rem;
  background: linear-gradient(135deg, #3b82f6, #8b5cf6);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

h2 {
  font-size: 1.5rem;
  font-weight: 600;
  color: #f1f5f9;
  margin: 2rem 0 1rem 0;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid #334155;
}

h3 {
  font-size: 1.25rem;
  font-weight: 600;
  color: #cbd5e1;
  margin-bottom: 0.5rem;
}

/* Links */
a {
  color: #60a5fa;
  text-decoration: none;
  transition: all 0.2s ease;
  border-radius: 4px;
  padding: 2px 4px;
}

a:hover {
  color: #93c5fd;
  background-color: rgba(96, 165, 250, 0.1);
  transform: translateY(-1px);
}

/* Project cards */
.project-card {
  background: linear-gradient(135deg, #1e293b 0%, #334155 100%);
  border: 1px solid #475569;
  padding: 1.5rem;
  border-radius: 12px;
  margin-bottom: 1.5rem;
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
}

.project-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 1px;
  background: linear-gradient(90deg, transparent, #60a5fa, transparent);
  opacity: 0;
  transition: opacity 0.3s ease;
}

.project-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.4);
  border-color: #60a5fa;
}

.project-card:hover::before {
  opacity: 1;
}

/* Skills section */
.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
  margin: 1rem 0;
}

.skill-category {
  background: rgba(30, 41, 59, 0.5);
  padding: 1rem;
  border-radius: 8px;
  border-left: 3px solid #60a5fa;
}

/* Intro section */
.intro {
  text-align: center;
  margin-bottom: 3rem;
  padding: 2rem;
  background: rgba(30, 41, 59, 0.3);
  border-radius: 16px;
  border: 1px solid #334155;
}

/* Contact section */
.contact {
  text-align: center;
  margin-top: 3rem;
  padding: 2rem;
  background: linear-gradient(135deg, #1e293b, #0f172a);
  border-radius: 12px;
  border: 1px solid #475569;
}

/* Icons */
.icon {
  vertical-align: middle;
  margin-right: 0.5rem;
  font-size: 1.2em;
}

/* Responsive */
@media (max-width: 768px) {
  body {
    padding: 1rem;
  }
  
  h1 {
    font-size: 2rem;
  }
  
  .skills-grid {
    grid-template-columns: 1fr;
  }
}
</style>

# Kwesi Boahene

**Aspiring Data Analyst | Data Scientist | Machine Learning Enthusiast**  
Econometrics & Quantitative Economics graduate from UIUC with minors in Computer Science and Statistics.  
Interested in applying data-driven insights to **finance, operations, retail, sports analytics, and AI/ML applications**.

---


## Interests
- Predictive modeling and forecasting for finance and retail
- Optimization and analytics in operations and supply chain
- Sports performance and game outcome analytics
- Machine learning applications, AI pipelines, and data-driven decision-making

---

## Skills

- Programming & Data Tools: Python, R, SQL, C++, Excel, Tableau, Power BI  
- Data Science & ML: Time Series Analysis, Forecasting Models, Econometrics, Lasso Regression, Statistical Modeling  
- Visualization: Matplotlib, ggplot2, Plotly, Tableau, Power BI  
- Cloud & Collaboration: Git, Docker, AWS, GCP  
- Other: Data Wrangling, EDA, Model Evaluation (RMSE, Cross-validation), Experimental Design  


---

## Projects

### [📊 Walmart Sales Forecasting](https://github.com/kwesibb2/Walmart-Sales)
State-level sales prediction with ARMA and Lasso models, RMSE evaluation, and insights for inventory and workforce optimization.  
*Tech stack:* R, RMarkdown, glmnet, plotly, HTML 

### [🤖 Machine Learning Trading Bot](https://github.com/yourusername/project-link)
An automated options trading bot with backtesting and risk management.  
*Tech stack:* Python, QuantConnect API, Scikit-learn

### [📈 Sales Dashboard](https://github.com/yourusername/project-link)
Interactive business intelligence dashboard for tracking KPIs.  
*Tech stack:* Tableau, SQL, Excel

---

## 📫 Contact

- **Email:** pkwesi4@gmail.com 


---
