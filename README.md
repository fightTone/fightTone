# Hi there! I'm Geronyl S. Paragoso 👋
### Senior Software Engineer | Data Science Specialist | Full-Stack Developer

![Screenshot](https://github.com/fightTone/fightTone/blob/main/images/full-stack-development.gif)

## About Me
Experienced Software Engineer with **5+ years** of industry expertise in full-stack development, specializing in **Data Science**, **Progressive Web Applications**, and **Data Engineering**. I have a proven track record of collaborating with international clients across Asia Pacific and North America to deliver impactful software solutions.

## 🚀 What I Do
- 🔭 Building scalable data pipelines and real-time analytics systems
- 🌱 Developing machine learning models and AI-powered applications
- 👯 Creating full-stack web applications with modern frameworks
- 💡 Architecting cloud solutions and automated deployment systems

## 🛠️ Tech Stack

<div align="center">

<!-- Animated typing effect -->
<a href="#"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=Senior+Software+Engineer;Data+Science+%26+AI%2FML+Specialist;Full-Stack+Developer;Cloud+Architecture+Expert;5%2B+Years+Experience" alt="Typing SVG" /></a>

<div id="tech-showcase" style="margin: 20px 0; padding: 15px; border: 2px solid #00D9FF; border-radius: 10px; background: linear-gradient(45deg, #1a1a2e, #16213e); color: #00D9FF;">
  <h3 id="code-title" style="text-align: center; margin-bottom: 15px;">🚀 Live Code Demo</h3>
  <div id="code-container" style="font-family: 'Courier New', monospace; font-size: 14px; line-height: 1.5;">
    <div id="code-line-1">const developer = {</div>
    <div id="code-line-2" style="margin-left: 20px;">name: "Geronyl Paragoso",</div>
    <div id="code-line-3" style="margin-left: 20px;">experience: "5+ years",</div>
    <div id="code-line-4" style="margin-left: 20px;">skills: ["Python", "JavaScript", "AI/ML"],</div>
    <div id="code-line-5" style="margin-left: 20px;">status: "Available for opportunities"</div>
    <div id="code-line-6">};</div>
  </div>
</div>

<script>
// Animate tech showcase on load
document.addEventListener('DOMContentLoaded', function() {
  const lines = ['code-line-1', 'code-line-2', 'code-line-3', 'code-line-4', 'code-line-5', 'code-line-6'];
  
  // Hide all lines initially
  lines.forEach(line => {
    document.getElementById(line).style.opacity = '0';
    document.getElementById(line).style.transform = 'translateX(-20px)';
    document.getElementById(line).style.transition = 'all 0.5s ease';
  });
  
  // Animate lines one by one
  lines.forEach((line, index) => {
    setTimeout(() => {
      const element = document.getElementById(line);
      element.style.opacity = '1';
      element.style.transform = 'translateX(0)';
    }, index * 300);
  });
  
  // Add hover effects to tech badges
  const badges = document.querySelectorAll('img[src*="shields.io"]');
  badges.forEach(badge => {
    badge.style.transition = 'transform 0.3s ease';
    badge.addEventListener('mouseenter', () => {
      badge.style.transform = 'scale(1.1) rotate(2deg)';
    });
    badge.addEventListener('mouseleave', () => {
      badge.style.transform = 'scale(1) rotate(0deg)';
    });
  });
});

// Pulse animation for title
setInterval(() => {
  const title = document.getElementById('code-title');
  if (title) {
    title.style.transform = 'scale(1.05)';
    title.style.transition = 'transform 0.3s ease';
    setTimeout(() => {
      title.style.transform = 'scale(1)';
    }, 300);
  }
}, 3000);

// Flashy cursor trail effect
document.addEventListener('mousemove', function(e) {
  createTrailDot(e.clientX, e.clientY);
});

function createTrailDot(x, y) {
  const dot = document.createElement('div');
  dot.style.position = 'fixed';
  dot.style.left = x + 'px';
  dot.style.top = y + 'px';
  dot.style.width = '8px';
  dot.style.height = '8px';
  dot.style.borderRadius = '50%';
  dot.style.background = `hsl(${Math.random() * 360}, 100%, 60%)`;
  dot.style.pointerEvents = 'none';
  dot.style.zIndex = '9999';
  dot.style.animation = 'cursorTrail 0.8s ease-out forwards';
  dot.style.boxShadow = `0 0 10px hsl(${Math.random() * 360}, 100%, 60%)`;
  
  document.body.appendChild(dot);
  
  setTimeout(() => {
    if (dot.parentNode) {
      dot.parentNode.removeChild(dot);
    }
  }, 800);
}

// Custom cursor glow effect
document.body.style.cursor = 'none';
const cursor = document.createElement('div');
cursor.style.position = 'fixed';
cursor.style.width = '20px';
cursor.style.height = '20px';
cursor.style.borderRadius = '50%';
cursor.style.background = 'radial-gradient(circle, #00D9FF, transparent)';
cursor.style.pointerEvents = 'none';
cursor.style.zIndex = '10000';
cursor.style.mixBlendMode = 'difference';
cursor.style.transition = 'transform 0.1s ease';
document.body.appendChild(cursor);

document.addEventListener('mousemove', function(e) {
  cursor.style.left = (e.clientX - 10) + 'px';
  cursor.style.top = (e.clientY - 10) + 'px';
});

// Add CSS animation keyframes
const style = document.createElement('style');
style.textContent = `
  @keyframes cursorTrail {
    0% {
      transform: scale(1);
      opacity: 1;
    }
    100% {
      transform: scale(0);
      opacity: 0;
    }
  }
  
  body {
    cursor: none !important;
  }
  
  * {
    cursor: none !important;
  }
`;
document.head.appendChild(style);
</script>

### Core Proficiency
<a href="#"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white" /></a>

### Experience
<a href="#"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" /></a>
<a href="#"><img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" /></a>
<a href="#"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" /></a>

### Cloud & AI/ML
<a href="#"><img src="https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white" /></a>

</div>


## 💼 Professional Focus

🎯 **Specializing in:** Full-Stack Development | Data Science & Engineering | AI/ML Solutions | Cloud Architecture

🚀 **Expertise:** Building scalable data pipelines, developing intelligent applications, and architecting cloud-native solutions

🌐 **Impact:** Delivering enterprise-grade solutions for international clients across Asia Pacific and North America

## 📫 Let's Connect!
- 📧 Email: qgee123@gmail.com
- 💼 LinkedIn: [geronyl-paragoso](https://www.linkedin.com/in/geronyl-paragoso-618232168)
- 📱 Phone: +63 955 913 7671
- 📍 Location: Linamon, Lanao del Norte, Philippines

---
*Open to collaboration on innovative projects in Data Science, AI/ML, and Full-Stack Development!*
