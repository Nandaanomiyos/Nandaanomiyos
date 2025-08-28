<!-- Banner tengah -->
<div align="center">

  <!-- Efek ngetik warna hijau (pakai Readme Typing SVG) -->
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=26&duration=3000&pause=700&color=22C55E&center=true&vCenter=true&width=700&lines=Hi+there%2C+I'm+Nx+Hunter;Bug+Hunter+%7C+Learner+%7C+Gamer;Welcome+to+my+GitHub+profile!" alt="Typing SVG" />

  <br/><br/>

  <!-- Logos: Linux, Kali, HTML, CSS, JS, Python, Java -->
  <!-- NOTE: If any SVG doesn't render in your README, replace with a PNG hosted somewhere. -->
  <img alt="linux" height="28" src="https://cdn.jsdelivr.net/npm/simple-icons@v12/icons/linux.svg" style="margin-right:6px; filter:invert(25%) sepia(85%) saturate(600%) hue-rotate(80deg) brightness(95%);" />
  <img alt="kali" height="28" src="https://cdn.jsdelivr.net/npm/simple-icons@v12/icons/kalilinux.svg" style="margin-right:6px; filter:invert(25%) sepia(85%) saturate(600%) hue-rotate(80deg) brightness(95%);" />
  <img alt="html" height="28" src="https://cdn.jsdelivr.net/npm/simple-icons@v12/icons/html5.svg" style="margin-right:6px; filter:invert(11%) sepia(80%) saturate(600%) hue-rotate(80deg) brightness(95%;" />
  <img alt="css" height="28" src="https://cdn.jsdelivr.net/npm/simple-icons@v12/icons/css3.svg" style="margin-right:6px; filter:invert(11%) sepia(80%) saturate(600%) hue-rotate(80deg) brightness(95%);" />
  <img alt="js" height="28" src="https://cdn.jsdelivr.net/npm/simple-icons@v12/icons/javascript.svg" style="margin-right:6px; filter:invert(11%) sepia(80%) saturate(600%) hue-rotate(80deg) brightness(95%);" />
  <img alt="python" height="28" src="https://cdn.jsdelivr.net/npm/simple-icons@v12/icons/python.svg" style="margin-right:6px; filter:invert(11%) sepia(80%) saturate(600%) hue-rotate(80deg) brightness(95%);" />
  <img alt="java" height="28" src="https://cdn.jsdelivr.net/npm/simple-icons@v12/icons/java.svg" style="margin-right:6px; filter:invert(11%) sepia(80%) saturate(600%) hue-rotate(80deg) brightness(95%);" />

  <br/><br/>
  <!-- Badges -->
  <img src="https://img.shields.io/badge/Focus-OSINT-22C55E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Tools-Kali%20%7C%20Nmap%20%7C%20Sqlmap-22C55E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Lang-HTML%20%7C%20CSS%20%7C%20JS-22C55E?style=for-the-badge" />

</div>

---

### 🧑‍💻 About me
- 🔭 Currently exploring: bug hunting & unique game ideas  
- 🌱 Learning: HTML/CSS/JS, a bit of Python & Java  
- 🎯 Goal: Build small, fun projects & share notes

### 🧰 Tech & Tools
`Kali` · `Nmap` · `sqlmap` · `Nuclei` · `Subfinder` · `John` · `Git` · `VS Code`

---

### 🐍 Mini Snake — animated (SVG)
Below is a small, self-contained **animated SVG snake** that "slithers" left→right on the README. Paste as-is into your README; it's pure SVG (no JS), so it works on GitHub profile READMEs.

<div align="center">

```html
<!-- Paste this exact block into your README where you want the snake -->
<svg width="420" height="80" viewBox="0 0 420 80" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid meet">
  <!-- background 'terminal' rectangle -->
  <rect width="100%" height="100%" rx="8" fill="#0b0f08"/>
  <!-- Matrix-like green stream (decorative) -->
  <g opacity="0.18" transform="translate(10,6)">
    <text x="0" y="14" font-family="monospace" font-size="12" fill="#0fa75a">101010100110011001010101010100110101010</text>
    <text x="80" y="34" font-family="monospace" font-size="12" fill="#0fa75a">010101010110010101001100101010001100101</text>
    <text x="20" y="54" font-family="monospace" font-size="12" fill="#0fa75a">110100101001011001010100100101010010101</text>
  </g>

  <!-- Snake body: series of circles -->
  <g id="snake" transform="translate(-120,40)">
    <!-- head -->
    <circle cx="0" cy="0" r="7" fill="#22C55E"/>
    <!-- body segments -->
    <circle cx="-18" cy="0" r="6" fill="#1f9b4a"/>
    <circle cx="-34" cy="0" r="5.5" fill="#1a8a43"/>
    <circle cx="-48" cy="0" r="5" fill="#15753a"/>
    <circle cx="-60" cy="0" r="4.5" fill="#116f33"/>
    <circle cx="-70" cy="0" r="4" fill="#0d5c29"/>
  </g>

  <!-- animate the snake group to move across -->
  <animateTransform xlink:href="#snake" attributeName="transform" type="translate"
    values="-140 40; 420 40; -140 40" dur="6s" repeatCount="indefinite" />

  <!-- simple tongue flick (head) -->
  <line x1="0" y1="40" x2="10" y2="36" stroke="#9bffb8" stroke-width="1.5" stroke-linecap="round">
    <animate attributeName="x2" values="10;14;10" dur="0.6s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="36;34;36" dur="0.6s" repeatCount="indefinite"/>
  </line>

  <!-- caption -->
  <text x="12" y="16" font-family="monospace" font-size="12" fill="#88f7a6">~ Nx Hunter — coding & hunting</text>
</svg>
