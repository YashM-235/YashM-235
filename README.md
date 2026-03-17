## 🎯Final Year CSE Student | AI Engineer & Data Science Practitioner | Building Intelligent Systems

<div align="center">

```ascii
╭─────────────────────────────────────────────────────────────────────────────────────╮
│  ██╗   ██╗ █████╗ ███████╗██╗  ██╗    ███╗   ███╗███████╗██╗  ██╗████████╗ █████╗  │
│  ╚██╗ ██╔╝██╔══██╗██╔════╝██║  ██║    ████╗ ████║██╔════╝██║  ██║╚══██╔══╝██╔══██╗ │
│   ╚████╔╝ ███████║███████╗███████║    ██╔████╔██║█████╗  ███████║   ██║   ███████║ │
│    ╚██╔╝  ██╔══██║╚════██║██╔══██║    ██║╚██╔╝██║██╔══╝  ██╔══██║   ██║   ██╔══██║ │
│     ██║   ██║  ██║███████║██║  ██║    ██║ ╚═╝ ██║███████╗██║  ██║   ██║   ██║  ██║ │
│     ╚═╝   ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝    ╚═╝     ╚═╝╚══════╝╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝ │
╰─────────────────────────────────────────────────────────────────────────────────────╯
```

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=28&duration=4000&pause=1000&color=0969DA&center=true&vCenter=true&multiline=true&width=800&height=120&lines=🎓+Computer+Science+Student+2026;🤖+Machine+Learning+Enthusiast;🏗️+Full-Stack+Project+Builder;🚀+Aspiring+Software+Engineer" alt="Student Typing Animation"/>

[![Profile Views](https://komarev.com/ghpvc/?username=YashM-235&color=0969DA&style=flat-square&label=Profile+Views)](https://github.com/YashM-235)
[![GitHub followers](https://img.shields.io/github/followers/YashM-235?style=flat-square&color=0969DA&label=Followers)](https://github.com/YashM-235)
[![Graduation](https://img.shields.io/badge/Graduation-2026-0969DA?style=flat-square)](https://linkedin.com/in/yash-mehta-402239163)

</div>

---

## 🎖️ **ABOUT ME**

<div align="center">
  <img src="https://media.giphy.com/media/L1R1tvI9svkIWwpVYr/giphy.gif" width="400">
</div>

> **Passionate Computer Science student** with a love for building innovative solutions and exploring cutting-edge technologies. Currently in my final year at Bennett University with hands-on experience in **AI/ML projects**, **full-stack development**, and **research**. Eager to contribute to impactful projects and learn from industry experts.

```python
class YashMehta:
    def __init__(self):
        self.status = "Final Year CSE Student"
        self.graduation = "2026"
        self.passion = [
            "Machine Learning & AI",
            "Full-Stack Development", 
            "Research & Innovation",
            "Problem Solving"
        ]
        self.achievements = {
            "projects_built"  : 15,
            "hackathon_recog" : "LexHack 1.0 — Appreciated by Judges",
            "certifications"  : 7,   # NVIDIA · IBM · Google · IIT Delhi
            "research_papers" : 2,   # IEEE published · Springer in press
        }
        
    def career_goal(self):
        return "Building the future through code and innovation! 🚀"
```

---

## 🏢 **TECHNICAL SKILLS & LEARNING JOURNEY**

<div align="center">

| **Domain** | **Proficiency** | **Key Technologies** | **Learning Since** |
|------------|-----------------|---------------------|-------------------|
| **Machine Learning** | ████████████████▓▓▓▓ | TensorFlow, Scikit-learn, PyTorch | 2023 |
| **Full-Stack Development** | ████████████████▓▓▓▓ | Flask, React, REST APIs | 2022 |
| **Data Science** | ██████████████▓▓▓▓▓▓ | Pandas, NumPy, Matplotlib | 2023 |
| **Programming** | ████████████████████ | Python, Java, C++, JavaScript | 2022 |
| **Web Technologies** | ██████████████▓▓▓▓▓▓ | HTML/CSS, MySQL, MongoDB | 2022 |
| **Research & Analysis** | ████████████████▓▓▓▓ | Academic Writing, Experimentation | 2024 |

</div>

---

## 🏆 **FEATURED PROJECTS & ACHIEVEMENTS**

### 🔮 **Amazon Stock Prediction System** | *Time Series Forecasting*
<img src="https://media.giphy.com/media/l3vR85PnGsBwu1PFK/giphy.gif" width="180" align="right">

**Advanced ML Project for Financial Prediction**

• **Innovation**: Built hybrid ensemble combining 7 different models (ARIMA, LSTM, GRU, Prophet, Transformers)  
• **Achievement**: Custom TimeSeriesTransformer achieving impressive RMSE of 0.03285  
• **Learning**: Deep dive into time series analysis, model ensembling, and financial data  
• **Tech Stack**: Python, TensorFlow, Pandas, Flask, data visualization  
• **Outcome**: Comprehensive understanding of production ML pipelines  

<details>
<summary><b>🔬 What I Learned & Built</b></summary>

```python
class TimeSeriesTransformer(nn.Module):
    """
    My custom transformer architecture for stock prediction
    Learned about attention mechanisms and temporal modeling
    """
    def __init__(self, d_model=512, n_heads=8, dropout=0.1):
        super().__init__()
        self.multihead_attn = nn.MultiHeadAttention(d_model, n_heads, dropout)
        self.positional_encoding = TemporalPositionalEncoding(d_model)
        self.layer_norm = nn.LayerNorm(d_model)
        
    def forward(self, src):
        # Implementing attention for time series - fascinating learning experience!
        src = self.positional_encoding(src)
        attn_output, _ = self.multihead_attn(src, src, src)
        return self.layer_norm(attn_output + src)
```

**Key Learning Outcomes:**
- Model architecture design and hyperparameter tuning
- Handling financial time series data and feature engineering  
- Building ensemble models and weighted prediction systems
- Creating REST APIs for model serving
</details>

[![View Project](https://img.shields.io/badge/View_Project-GitHub-black?style=for-the-badge&logo=github)](https://github.com/YashM-235/Amazon-Stock-Price-Prediction)

---

### ⚖️ **FIR Generator & Legal AI** | **LexHack 1.0**
<img src="https://media.giphy.com/media/3o7abAHdYvZdBNnGZq/giphy.gif" width="180" align="right">

**Judge-Recognized Idea at LexHack 1.0**

• **Recognition**: 🌟 Appreciated & praised by judges for innovation and real-world impact  
• **Problem Solved**: Streamlined legal complaint filing with AI assistance  
• **Innovation**: Real-time location tracking + AI-powered legal guidance  
• **Tech Challenge**: Integrated multiple APIs (Google Maps, Gemini AI) in 48 hours  
• **Team Leadership**: Led development team and presented to judges  

**What Made This Special:**
- 📱 Built responsive web app from scratch in a weekend
- 🤖 Implemented AI chatbot for legal assistance
- 🗺️ Real-time geolocation features for crime reporting
- 🎯 Focused on solving real-world problems

[![View Project](https://img.shields.io/badge/View_Project-GitHub-black?style=for-the-badge&logo=github)](https://github.com/YashM-235/FIR-genie)
---

### 👁️ **Fog Detection using Computer Vision** | *Research Project*
<img src="https://images.bhaskarassets.com/webp/thumb/512x0/web2images/521/2025/01/04/gif2_1735948901.gif" width="180" align="right">

**Academic Research with Real-World Applications**

• **Research Goal**: Improve visibility detection for autonomous systems  
• **Innovation**: Hybrid CNN + Vision Transformer architecture  
• **Achievement**: 15% accuracy improvement over existing methods  
• **Datasets**: Worked with FRIDA2, HSTS, RTTS, SOTS benchmark datasets  
• **Learning**: Deep understanding of computer vision and deep learning  

**Research Skills Developed:**
- Literature review and academic paper analysis
- Experimental design and statistical validation
- Model architecture experimentation
- Real-time computer vision pipeline development

---

## 🧠 **RESEARCH EXPERIENCE & ACADEMIC WORK**

<div align="center">
  <img src="https://media.giphy.com/media/HscDLzkO8EOTmgkhQP/giphy.gif" width="250">
</div>

### 📚 **Current Research Projects**
- **Blockchain Security in Autonomous Vehicles** (Bennett University, 2024)
  - Working under faculty guidance on novel consensus mechanisms
  - Achieved 35% reduction in spoofing vulnerability in simulations

- **Fake News Detection Research** (Collaboration with IIT Roorkee, 2025)  
  - Built ML pipeline achieving 87% accuracy using TF-IDF + Random Forest
  - **Presented at SocProS 2025** - My first international conference!

### 🎓 **Academic Performance**
- **CGPA**: 8.2/10 (Consistent academic excellence)
- **Relevant Coursework**: Data Structures, Algorithms, Machine Learning, Database Systems, Software Engineering
- **Key Projects**: 15+ academic and personal projects showcasing diverse skills

###   **Research Papers:**

  1) Fake News Detection Using Machine Learning and Sentiment Analysis Integrated in a Flask Web Application
  
     [![SocPros Paper](https://img.shields.io/badge/Open-Page%2089-blue?style=for-the-badge)](https://socpros2025.iitr.ac.in/wp-content/uploads/2025/04/Book_of_Abstracts_ScoProS_25.pdf#page=90)
  
     (Earlier paper was published in Book of Abstracts, SocPros-25 (Soft Computing for Problem Solving), IIT Roorkee)
  
     Update: Paper is in Publication with Springer. (More details soon)
  
  3) Mehta et. al., "Fog Detection Using Hybrid Deep Learning Models: A Multi-Modal CNN-LSTM Approach", IEEE, 7th International Conference on Computing, Communication and Automation (ICCCA), Galgotias University,    Greater Noida, pp 1-6, Nov 28-30, 2025. (DOI: 10.1109/ICCCA66364.2025.11325690)
  
     [![IEEE Paper](https://img.shields.io/badge/IEEE-View%20Paper-blue?style=for-the-badge)](https://ieeexplore.ieee.org/document/11325690)

---

## 🔧 **TECHNOLOGY STACK & LEARNING PATH**

<div align="center">

```mermaid
mindmap
  root((Learning Journey))
    Programming Foundations
      Python
        Data Science
        ML/AI
        Web Development
      Java
        Object-Oriented Design
        Backend Development
      C++
        Algorithms
        Competitive Programming
      JavaScript
        Frontend Development
        Full-Stack Projects
    Specialized Skills
      Machine Learning
        TensorFlow
        Scikit-learn
        Computer Vision
      Web Development
        Flask
        React
        REST APIs
      Data Science
        Pandas
        NumPy
        Visualization
    Tools & Platforms
      Development
        Git/GitHub
        Jupyter Notebooks
        Google Colab
      Databases
        MySQL
        MongoDB
      Cloud
        Basic AWS
        Deployment
```

</div>

### **My Technical Arsenal**

| **Category** | **Technologies** | **Comfort Level** |
|--------------|------------------|-------------------|
| **Programming** | Python, Java, C++, JavaScript | ⭐⭐⭐⭐⭐ |
| **ML/AI** | TensorFlow, Scikit-learn, OpenCV, Pandas | ⭐⭐⭐⭐⭐ |
| **Web Dev** | Flask, React, HTML/CSS, REST APIs | ⭐⭐⭐⭐☆ |
| **Databases** | MySQL, MongoDB | ⭐⭐⭐⭐☆ |
| **Tools** | Git, Jupyter, Google Colab, Postman | ⭐⭐⭐⭐⭐ |
| **Cloud** | Basic AWS, Docker (Learning) | ⭐⭐⭐☆☆ |

---

## 📊 **ACHIEVEMENTS & MILESTONES**

<div align="center">
  <img src="https://media.giphy.com/media/26BRuo6sLetdllPAQ/giphy.gif" width="300">
</div>

```diff
+ 🎯 15+ Personal & Academic Projects Completed
+ 🌟 Appreciated by Judges at LexHack 1.0 for Innovation & Real-World Impact
+ 📚 2 Research Papers (IEEE Published · Springer In Press)
+ 🎓 7 Industry Certifications — NVIDIA, IBM, Google, IIT Delhi
+ 📈 8.2 CGPA - Consistent Academic Excellence
+ 🚀 500+ Students Helped Through Career Guidance Platform
+ 🌟 Featured in Bennett University Industry Showcase
+ 💻 1000+ Hours of Coding Experience Across Multiple Languages
```

### **Key Milestones in My Journey**
- **2022**: Started serious programming with Python
- **2023**: First machine learning project and hackathon participation
- **2024**: Won first major hackathon, started research work
- **2025**: International conference presentation, preparing for placements

---

## 🎓 **EDUCATION & CONTINUOUS LEARNING**

### **Current Education**
- **B.Tech in Computer Science & Engineering** | Bennett University (2022-2026)
  - **CGPA**: 8.2/10 
  - **Focus Areas**: Machine Learning, Software Engineering, Data Structures & Algorithms
  - **Final Year Project**: Advanced time series forecasting with transformer architectures

### **Certifications & Online Learning**
- 🏅 **Fundamentals of Deep Learning** - NVIDIA (https://learn.nvidia.com/certificates?id=y1TgN2K4SBWLBG9szfuKog)
- 🏅 **IBM Machine Learning Professional Certificate** - IBM (Coursera) (https://coursera.org/share/7ae117774d78ea70b664c8ed92892d4a) 
- 🏅 **Introduction to Generative AI** - Google Cloud (https://coursera.org/share/aba89c1a80b41760b05c0d4082d884d9)
- 🏅 **Google Data Analytics Professional Certificate** - Google (https://coursera.org/share/78ca15b1194bc73415788be6e3838a0b)
- 🏅 **Generative AI Fundamentals** - IBM (https://coursera.org/share/de7638e79f581fcd6d5eee3e177bcf64)
- 🏅 **AI Foundations for Business** - IBM (https://coursera.org/share/399ff90f4d2f623f3a0220764bf0985d)
- 🏅 **Quantum Computing & Quantum Key Distribution (QKD)** - IIT Delhi (3-Day Workshop)

---

## 🌟 **INTERNSHIP & PRACTICAL EXPERIENCE**

### **Professional Experience**
- **Software & API Development Intern** | MNNIT Allahabad (2024)
  - Developed RESTful APIs using Flask, improved backend performance by 20%
  - Collaborated in Agile development environment with senior developers
  - Learned professional coding standards, Git workflows, and code reviews
  - **Key Takeaway**: Understanding of production-level software development

### **Leadership & Community**
- **Technical Mentor**: Helped 50+ junior students with programming concepts
- **Project Collaborator**: Led teams in multiple hackathons and group projects
- **Open Source Enthusiast**: Contributing to GitHub projects and building reusable components

---

## 🔗 **CONNECT WITH ME**

<div align="center">
  
  <a href="https://linkedin.com/in/yash-mehta-402239163">
    <img src="https://img.shields.io/badge/LinkedIn-Let's_Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/YashM-235">
    <img src="https://img.shields.io/badge/GitHub-Follow_My_Journey-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="mailto:yash34m6@gmail.com">
    <img src="https://img.shields.io/badge/Email-Say_Hello-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Portfolio-View_My_Work-FF6B6B?style=for-the-badge&logo=firefox&logoColor=white"/>
  </a>

</div>

---

## 💡 **WHAT I'M LOOKING FOR**

```python
class CareerAspirations:
    def __init__(self):
        self.seeking = [
            "Software Development Engineer roles",
            "Machine Learning Engineer positions", 
            "Research opportunities",
            "Innovative internships at top companies"
        ]
        self.dream_companies = ["FAANG", "Startups", "Research Labs"]
        self.availability = "Graduating 2026 - Open for 2025 internships!"
    
    def what_i_bring(self):
        return [
            "Fresh perspective and enthusiasm",
            "Strong foundation in CS fundamentals", 
            "Proven ability to learn quickly",
            "Real project experience and problem-solving skills"
        ]

# Excited to start my professional journey!
aspirations = CareerAspirations()
print("Ready to contribute, learn, and grow! 🚀")
```

<div align="center">
  <img src="https://media.giphy.com/media/3o7aD2d7hy9ktXNDP2/giphy.gif" width="500"/>
  
  <br><br>
  
  ### 🎯 **"Learning never stops, and neither do I!"**
  
  ---
  
  <img src="https://github-readme-stats.vercel.app/api?username=YashM-235&show_icons=true&theme=github_dark&hide_border=false&bg_color=0d1117&title_color=0969da&text_color=c9d1d9&icon_color=0969da&border_color=0969da&border_radius=8&include_all_commits=true&count_private=true&cache_seconds=1800"/>
  
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YashM-235&layout=compact&theme=github_dark&hide_border=false&bg_color=0d1117&title_color=0969da&text_color=c9d1d9&border_color=0969da&border_radius=8&langs_count=8&cache_seconds=1800"/>

  <br>

  <img src="https://streak-stats.demolab.com?user=YashM-235&theme=github-dark-blue&background=0d1117&border=0969da&ring=0969da&fire=ff6b35&currStreakLabel=0969da&border_radius=8"/>
  
  <br>
  
  **Final Year Student** | **Available for Internships** | **Graduating 2026** | **Ready to Make Impact**
  
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:00f7ff15,100:7b2fff&height=120&section=footer&text=..&fontSize=18&fontColor=00f7ff&animation=twinkling&fontAlignY=70"/>
