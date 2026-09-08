<div align="center">
<img src="https://raw.githubusercontent.com/AditiDeshwal11/AditiDeshwal11/main/aditi_deshwal_github_banner.svg" width="100%" alt="banner"/>
<svg xmlns="http://www.w3.org/2000/svg"
     width="1400" height="400"
     viewBox="0 0 1400 400">

<defs>

  <!-- BACKGROUND -->
  <radialGradient id="bg">
    <stop offset="0" stop-color="#111b3d"/>
    <stop offset="0.55" stop-color="#070b19"/>
    <stop offset="1" stop-color="#02040b"/>
  </radialGradient>

  <!-- NEON -->
  <filter id="neon">
    <feGaussianBlur stdDeviation="4" result="blur"/>
    <feMerge>
      <feMergeNode in="blur"/>
      <feMergeNode in="SourceGraphic"/>
    </feMerge>
  </filter>

  <!-- GRID -->
  <pattern id="grid"
           width="40" height="40"
           patternUnits="userSpaceOnUse">
    <path d="M40 0H0V40"
          fill="none"
          stroke="#26395c"
          stroke-width="0.7"
          opacity="0.35"/>
  </pattern>

  <!-- GRADIENT -->
  <linearGradient id="cyanPurple">
    <stop offset="0" stop-color="#00f5ff"/>
    <stop offset="0.5" stop-color="#7b61ff"/>
    <stop offset="1" stop-color="#ff4fd8"/>
  </linearGradient>

</defs>


<!-- ================================================= -->
<!-- BACKGROUND -->
<!-- ================================================= -->

<rect width="1400"
      height="400"
      rx="25"
      fill="url(#bg)"/>

<rect width="1400"
      height="400"
      fill="url(#grid)"/>


<!-- ================================================= -->
<!-- HOLOGRAPHIC BORDER -->
<!-- ================================================= -->

<rect x="8" y="8"
      width="1384"
      height="384"
      rx="23"
      fill="none"
      stroke="url(#cyanPurple)"
      stroke-width="2"
      opacity=".8">

  <animate
    attributeName="opacity"
    values=".35;1;.35"
    dur="3s"
    repeatCount="indefinite"/>

</rect>


<!-- ================================================= -->
<!-- FLOATING PARTICLE FIELD -->
<!-- ================================================= -->

<g fill="#00f5ff">

<circle cx="720" cy="55" r="2">
 <animate attributeName="cy"
          values="55;25;55"
          dur="3s"
          repeatCount="indefinite"/>
</circle>

<circle cx="780" cy="130" r="3">
 <animate attributeName="cy"
          values="130;100;130"
          dur="4s"
          repeatCount="indefinite"/>
</circle>

<circle cx="850" cy="50" r="2">
 <animate attributeName="cy"
          values="50;80;50"
          dur="2.5s"
          repeatCount="indefinite"/>
</circle>

<circle cx="920" cy="115" r="2">
 <animate attributeName="cy"
          values="115;75;115"
          dur="3s"
          repeatCount="indefinite"/>
</circle>

<circle cx="1030" cy="45" r="3">
 <animate attributeName="cy"
          values="45;75;45"
          dur="4s"
          repeatCount="indefinite"/>
</circle>

<circle cx="1130" cy="120" r="2">
 <animate attributeName="cy"
          values="120;80;120"
          dur="2.7s"
          repeatCount="indefinite"/>
</circle>

</g>


<!-- ================================================= -->
<!-- MAIN NAME -->
<!-- ================================================= -->

<text x="65"
      y="120"
      font-family="Arial"
      font-size="56"
      font-weight="900"
      letter-spacing="3"
      fill="white"
      filter="url(#neon)">

ADITI DESHWAL

<animate
 attributeName="opacity"
 values=".65;1;.65"
 dur="2.5s"
 repeatCount="indefinite"/>

</text>


<!-- ================================================= -->
<!-- GLITCH LINE -->
<!-- ================================================= -->

<rect x="68"
      y="138"
      width="280"
      height="3"
      rx="2"
      fill="url(#cyanPurple)">

<animate
 attributeName="width"
 values="40;300;180;280"
 dur="2s"
 repeatCount="indefinite"/>

</rect>


<!-- ================================================= -->
<!-- PROFESSIONAL TITLE -->
<!-- ================================================= -->

<text x="68"
      y="185"
      font-family="Arial"
      font-size="21"
      font-weight="700"
      letter-spacing="1"
      fill="#72faff">

AI/ML RESEARCHER × FRAUD DETECTION × DATA ANALYST

</text>


<!-- ================================================= -->
<!-- TERMINAL -->
<!-- ================================================= -->

<g transform="translate(65 225)">

<rect width="470"
      height="105"
      rx="10"
      fill="#050912"
      stroke="#203557"/>

<circle cx="20" cy="20" r="5" fill="#ff4f81"/>
<circle cx="38" cy="20" r="5" fill="#ffd166"/>
<circle cx="56" cy="20" r="5" fill="#00f5a0"/>

<text x="20"
      y="50"
      font-family="monospace"
      font-size="15"
      fill="#6ff">

$ python analyze.py

</text>

<text x="20"
      y="72"
      font-family="monospace"
      font-size="14"
      fill="#7aff9c">

&gt; fraud_model.................. 98.7%

</text>

<text x="20"
      y="93"
      font-family="monospace"
      font-size="14"
      fill="#b68cff">

&gt; neural_network............... ONLINE

</text>

</g>


<!-- ================================================= -->
<!-- LIVE DATA GRAPH -->
<!-- ================================================= -->

<g transform="translate(580 225)">

<text x="0"
      y="-15"
      font-family="Arial"
      font-size="13"
      fill="#6ff">

LIVE ANALYTICS

</text>

<polyline
 points="0,75 45,55 90,70 135,25 180,48 225,15 270,42 315,5"
 fill="none"
 stroke="#00f5ff"
 stroke-width="3"
 filter="url(#neon)">

<animate
 attributeName="points"
 values="
 0,75 45,55 90,70 135,25 180,48 225,15 270,42 315,5;
 0,55 45,75 90,35 135,60 180,20 225,50 270,15 315,35;
 0,75 45,55 90,70 135,25 180,48 225,15 270,42 315,5"
 dur="4s"
 repeatCount="indefinite"/>

</polyline>

</g>


<!-- ================================================= -->
<!-- NEURAL NETWORK -->
<!-- ================================================= -->

<g stroke="#586cff"
   stroke-width="2"
   opacity=".8">

<line x1="950" y1="205" x2="1030" y2="155"/>
<line x1="1030" y1="155" x2="1110" y2="205"/>
<line x1="1030" y1="155" x2="1080" y2="100"/>
<line x1="1110" y1="205" x2="1190" y2="145"/>
<line x1="1110" y1="205" x2="1160" y2="270"/>
<line x1="1190" y1="145" x2="1260" y2="190"/>

</g>


<!-- NETWORK NODES -->

<g fill="#00f5ff"
   filter="url(#neon)">

<circle cx="950" cy="205" r="5">
 <animate attributeName="r"
          values="4;10;4"
          dur="1.5s"
          repeatCount="indefinite"/>
</circle>

<circle cx="1030" cy="155" r="6">
 <animate attributeName="r"
          values="5;12;5"
          dur="2s"
          repeatCount="indefinite"/>
</circle>

<circle cx="1110" cy="205" r="5">
 <animate attributeName="r"
          values="4;10;4"
          dur="1.7s"
          repeatCount="indefinite"/>
</circle>

<circle cx="1190" cy="145" r="6">
 <animate attributeName="r"
          values="5;11;5"
          dur="2.3s"
          repeatCount="indefinite"/>
</circle>

</g>


<!-- ================================================= -->
<!-- MOVING NEURAL SIGNAL -->
<!-- ================================================= -->

<circle r="6"
        fill="#ffffff"
        filter="url(#neon)">

<animateMotion
 dur="2.5s"
 repeatCount="indefinite"
 path="M950,205 L1030,155 L1110,205 L1190,145 L1260,190"/>

</circle>


<!-- ================================================= -->
<!-- RADAR -->
<!-- ================================================= -->

<g transform="translate(1270 285)">

<circle r="65"
        fill="none"
        stroke="#00f5ff"
        opacity=".35"/>

<circle r="45"
        fill="none"
        stroke="#00f5ff"
        opacity=".3"/>

<circle r="25"
        fill="none"
        stroke="#00f5ff"
        opacity=".3"/>

<line x1="-65"
      y1="0"
      x2="65"
      y2="0"
      stroke="#00f5ff"
      opacity=".25"/>

<line x1="0"
      y1="-65"
      x2="0"
      y2="65"
      stroke="#00f5ff"
      opacity=".25"/>

<!-- RADAR SWEEP -->

<line x1="0"
      y1="0"
      x2="0"
      y2="-62"
      stroke="#00f5ff"
      stroke-width="4"
      filter="url(#neon)">

<animateTransform
 attributeName="transform"
 type="rotate"
 from="0"
 to="360"
 dur="1.8s"
 repeatCount="indefinite"/>

</line>

</g>


<!-- ================================================= -->
<!-- SCANNING LASER -->
<!-- ================================================= -->

<rect x="40"
      y="350"
      width="1320"
      height="2"
      fill="#00f5ff"
      opacity=".7"
      filter="url(#neon)">

<animate
 attributeName="x"
 values="40;1360;40"
 dur="5s"
 repeatCount="indefinite"/>

</rect>


<!-- ================================================= -->
<!-- FOOTER -->
<!-- ================================================= -->

<text x="68"
      y="370"
      font-family="monospace"
      font-size="12"
      fill="#526987">

SYSTEM STATUS: ONLINE • ML PIPELINE: ACTIVE • DATA STREAM: LIVE

</text>

</svg>

# Hi, I'm Aditi Deshwal 👋

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2EA3F2&center=true&vCenter=true&width=600&lines=AI%2FML+Researcher+%7C+Fraud+Detection;Data+%26+Business+Analyst;Turning+Data+Into+Decisions" alt="Typing SVG" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-LINKEDIN-HERE)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aditideshwal1234@gmail.com)

</div>

## 🎯 About Me

I'm a final-year Computer Science graduate (University of Delhi) who got hooked on the intersection of **AI/ML and real-world problem solving** — specifically how machine learning can fight fraud in banking. My research on AI-driven fraud prevention was presented at an **international conference (March 2026)**, and I'm certified as a Business Analyst, which means I care as much about the "why it matters to the business" as I do about the model accuracy.

## 🔬 Research & Projects

**AI in Fraud Detection & Prevention in Banking** — *Research, Aug 2025–Mar 2026*
- Developed & evaluated Random Forest, XGBoost, Gradient Boosting, and Neural Network models for fraud detection
- Applied feature engineering and rigorous evaluation to improve detection accuracy
- Presented findings at an international conference

**Credit Card Fraud Detection** — *ML Project, Nov 2023–Jan 2024*
- Built Logistic Regression + Anomaly Detection models achieving **97% accuracy**
- Used Cross-Validation, SMOTE oversampling, and EDA to reduce false negatives

## 🛠️ Tools & Tech

**Languages:** Python, C++, SQL, PHP, JavaScript, HTML/CSS, LaTeX
**ML/AI:** TensorFlow, PyTorch, Scikit-Learn, XGBoost, SMOTE, Feature Engineering
**Data & BI:** Power BI, Excel, MySQL, PostgreSQL
**Design:** Figma, Canva Pro, Adobe Illustrator

## 📊 GitHub Stats

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=AditiDeshwal11&show_icons=true&theme=tokyonight" width="48%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AditiDeshwal11&layout=compact&theme=tokyonight" width="45%"/>
</div>

## 🎤 Speaking

- Featured Speaker — International Girls in ICT Day (AIR FM Rainbow 102.6), Apr 2026
- Guest Speaker — Alpha Gen: Youth Speaks (Prasar Bharati), May 2026

## 🚀 Open To

Entry-level roles / internships in **AI/ML Engineering, Data Science, or Data Analytics**

## 📫 Connect

[LinkedIn](https://linkedin.com/in/YOUR-LINKEDIN-HERE) · [Email](mailto:aditideshwal1234@gmail.com)
