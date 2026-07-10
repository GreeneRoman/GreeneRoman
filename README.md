<h1 align="center">
  <svg viewBox="0 0 1000 240" width="100%" height="240" xmlns="http://www.w3.org/2000/svg" style="background: #0d1117; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">
    
    <!-- DEFINE ANIMATIONS & GRADIENTS -->
    <defs>
      <!-- Deep Aqua Glowing Text Gradient -->
      <linearGradient id="whaleTextGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#a7ffeb" />
        <stop offset="50%" stop-color="#00e5ff" />
        <stop offset="100%" stop-color="#0088cc" />
      </linearGradient>

      <!-- Glassmorphic Glow Filter -->
      <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="6" result="blur" />
        <feComposite in="SourceGraphic" in2="blur" operator="over" />
      </filter>
    </defs>

    <!-- LAYER 1: THE TEXT TO BE EATEN (GreeneRoman) -->
    <!-- It slides right, shrinks, and fades out as it approaches the whale's mouth -->
    <g transform="translate(50, 90)">
      <text font-weight="900" font-size="42" fill="url(#whaleTextGrad)" filter="url(#glow)">
        Hi there, I'm GreeneRoman 👋
        <animate attributeName="opacity" values="1; 1; 0; 0; 1" dur="7s" repeatCount="indefinite" keyTimes="0; 0.3; 0.45; 0.85; 0.95" />
        <animate attributeName="x" values="0; 20; 100; 100; 0" dur="7s" repeatCount="indefinite" keyTimes="0; 0.3; 0.45; 0.85; 0.95" />
        <animate attributeName="font-size" values="42; 42; 10; 10; 42" dur="7s" repeatCount="indefinite" keyTimes="0; 0.3; 0.45; 0.85; 0.95" />
      </text>
    </g>

    <!-- LAYER 2: THE REVEALED TEXT (Spatial Computing Graphics Engineer) -->
    <!-- Appears out of the bioluminescent trail, shaking under a retro-neon look -->
    <g transform="translate(50, 160)">
      <text font-weight="700" font-size="28" fill="#4ee7a2" filter="url(#glow)" letter-spacing="3">
        🎩 SPATIAL COMPUTING GRAPHICS ENGINEER 🥽✨
        <!-- Fade-in reveal timing -->
        <animate attributeName="opacity" values="0; 0; 1; 1; 0" dur="7s" repeatCount="indefinite" keyTimes="0; 0.42; 0.48; 0.85; 0.92" />
        <!-- Structural horizontal shaking effect -->
        <animateTransform attributeName="transform" type="translate" values="0,0; 2,0; -2,0; 1,-1; 0,0" dur="0.2s" repeatCount="indefinite" />
      </text>
    </g>

    <!-- LAYER 3: THE SHINY HOLOGRAPHIC BLUE WHALE -->
    <!-- Swims forward, chomps down rhythmically, and dives down -->
    <g transform="translate(620, 30)">
      <!-- Whole Whale Movement Sequence -->
      <animateTransform attributeName="transform" type="translate" 
        values="650,30; 520,30; 500,30; 750,50; 650,30" 
        dur="7s" repeatCount="indefinite" keyTimes="0; 0.32; 0.48; 0.85; 1" />

      <!-- Vector Shape of the Whale with Bioluminescent Lines -->
      <path d="M150 40 C210 20, 270 40, 290 60 C320 80, 300 120, 260 130 C230 140, 180 130, 150 110 C120 120, 80 130, 40 100 C10 80, 0 50, 20 40 C40 30, 70 60, 100 60 C120 60, 130 50, 150 40 Z" 
        fill="#005577" stroke="#00e5ff" stroke-width="3" filter="url(#glow)">
        <!-- Subtle breathing/glowing vector pulse -->
        <animate attributeName="fill" values="#004466; #0077aa; #004466" dur="3s" repeatCount="indefinite" />
      </path>

      <!-- The Moving Jaw (Chomp Action timing matches text disappearing) -->
      <path d="M60 85 C80 95, 110 95, 130 85 C110 100, 80 100, 60 85 Z" fill="#00e5ff">
        <animateTransform attributeName="transform" type="rotate" 
          values="0 60 85; 25 60 85; -5 60 85; 0 60 85" 
          dur="7s" repeatCount="indefinite" keyTimes="0; 0.3; 0.42; 1" />
      </path>

      <!-- Glowing Whale Eye -->
      <circle cx="95" cy="70" r="3" fill="#a7ffeb" filter="url(#glow)" />

      <!-- Sprinkling Digital Particle Particles being eaten -->
      <g opacity="0">
        <animate attributeName="opacity" values="0; 1; 0; 0" dur="7s" repeatCount="indefinite" keyTimes="0; 0.3; 0.45; 1" />
        <circle cx="20" cy="70" r="4" fill="#00e5ff" />
        <rect x="0" y="80" width="6" height="6" fill="#a7ffeb" />
        <circle cx="-15" cy="65" r="3" fill="#005577" />
      </g>
    </g>
  </svg>
</h1>



## ⚡ Quick Overview
- 🛠️ Currently developing high-value, optimized spatial computing frameworks.
- 🎨 Core focus: 3D graphics pipeline execution, shaders, and real-time engine systems.
- 📐 Backed by a strong foundation in linear algebra and 3D coordinate transformations.

---

## 🛠️ Immersive Tech Stack

| Domain | Tools & Technologies |
| :--- | :--- |
| **Engines & APIs** | `Unity3D` `Unreal Engine` `WebXR API` `Three.js` `WebGL` |
| **Languages** | `C#` `C++` `GLSL / HLSL` `TypeScript` |
| **Core Systems** | `Linear Algebra` `Performance Profiling` `Shader Development` |

---

## 🏗️ Pinned Masterpieces (In Development)

<details>
<summary><b>🛠️ Project 1: Performance Optimization Sandbox</b></summary>
<br>
An isolated XR tech demo built to stress-test standalone mobile VR hardware. Focusing on memory allocation management, custom object pooling, and draw call reduction to hit a locked 90 FPS.
<br>
<i>Status: Architectural phase. Codebase coming soon.</i>
</details>

<details>
<summary><b>🎨 Project 2: Custom Shader & Graphics Showpiece</b></summary>
<br>
A mathematical graphics project manipulating vertex and fragment shaders directly to handle dynamic, real-time spatial rendering.
<br>
<i>Status: Algorithmic phase. Codebase coming soon.</i>
</details>

---

## 📊 Live Contribution Stream
<!-- START_SECTION:activity -->
<!-- END_SECTION:activity -->

---

## 🥽 Immersive Simulation Matrix

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GreeneRoman/GreeneRoman/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/GreeneRoman/GreeneRoman/output/github-contribution-grid-snake.svg" />
  <img alt="Spatial Grid Simulation" src="https://raw.githubusercontent.com/GreeneRoman/GreeneRoman/output/github-contribution-grid-snake.svg" />
</picture>
