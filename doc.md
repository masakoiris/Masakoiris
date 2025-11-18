
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>IYUS FIRDAUS — Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html { scroll-behavior: smooth; }
    body {
      background: radial-gradient(circle at top, #0f0f1a 0%, #000 100%);
      color: white;
      overflow-x: hidden;
    }
    .neon-text {
      color: #fff;
      text-shadow: 0 0 10px #9f7aea, 0 0 20px #6366f1, 0 0 40px #4338ca;
    }
    .glow-border {
      box-shadow: 0 0 20px #6366f1;
    }
    .float {
      animation: float 4s ease-in-out infinite;
    }
    @keyframes float {
      0%,100%{ transform: translateY(0);}
      50%{ transform: translateY(-10px);}
    }
    /* partikel latar belakang */
    #particles-js {
      position: fixed;
      width: 100%;
      height: 100%;
      z-index: -1;
      top: 0;
      left: 0;
    }
  </style>
</head> 

<body class="font-sans"> 

  <!-- Background Particles -->
  <div id="particles-js"></div> 

  <!-- HERO -->
  <section class="h-screen flex flex-col justify-center items-center text-center px-4">
    <img src="https://i.ibb.co/0n1V7zB/ai-avatar.jpg" 
         alt="Iyus Firdaus"
         class="w-40 h-40 rounded-full glow-border mb-6 float" />
    <h2 class="text-gray-400 mb-2">👋 Hi, I'm</h2>
    <h1 class="text-5xl md:text-6xl font-bold neon-text mb-4">IYUS FIRDAUS</h1>
    <p class="text-gray-300 text-lg mb-6">
      AI Mentor • System Architect • Prompt Engineer<br>
      Creative Automation • Digital Artistry
    </p>
    <a href="#projects" 
       class="px-6 py-3 border border-indigo-400 rounded-full hover:bg-indigo-500 hover:text-white transition neon-text">
       View My Work
    </a>
  </section> 

  <!-- SKILLS -->
  <section id="skills" class="py-20 text-center bg-opacity-10 backdrop-blur-md">
    <h2 class="text-3xl font-bold mb-10 neon-text">EXPERTISE</h2>
    <div class="grid md:grid-cols-4 gap-6 max-w-5xl mx-auto">
      <div class="p-6 bg-gray-900/60 rounded-xl hover:scale-105 transition glow-border">
        <h3 class="text-xl mb-2">LLM Fine-Tuning</h3>
        <p class="text-gray-400 text-sm">Generative AI and intelligent design systems</p>
      </div>
      <div class="p-6 bg-gray-900/60 rounded-xl hover:scale-105 transition glow-border">
        <h3 class="text-xl mb-2">AI Workflow Design</h3>
        <p class="text-gray-400 text-sm">Automation pipeline for creative processes</p>
      </div>
      <div class="p-6 bg-gray-900/60 rounded-xl hover:scale-105 transition glow-border">
        <h3 class="text-xl mb-2">Digital Art Direction</h3>
        <p class="text-gray-400 text-sm">Creative AI model supervision and styling</p>
      </div>
      <div class="p-6 bg-gray-900/60 rounded-xl hover:scale-105 transition glow-border">
        <h3 class="text-xl mb-2">System Architecture</h3>
        <p class="text-gray-400 text-sm">Building scalable intelligent infrastructures</p>
      </div>
    </div>
  </section> 

  <!-- PROJECTS -->
  <section id="projects" class="py-20 text-center">
    <h2 class="text-3xl font-bold mb-10 neon-text">FEATURED PROJECTS</h2>
    <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto px-6">
      <div class="bg-gray-900/70 p-6 rounded-xl hover:scale-105 transition glow-border">
        <img src="https://source.unsplash.com/600x400/?ai,technology" class="rounded-lg mb-4">
        <h3 class="text-xl font-semibold mb-2">AI Prompt System</h3>
        <p class="text-gray-400 text-sm">A custom framework for creative automation.</p>
      </div>
      <div class="bg-gray-900/70 p-6 rounded-xl hover:scale-105 transition glow-border">
        <img src="https://source.unsplash.com/600x400/?digital,art" class="rounded-lg mb-4">
        <h3 class="text-xl font-semibold mb-2">Creative Automation Lab</h3>
        <p class="text-gray-400 text-sm">AI tools for design and digital expression.</p>
      </div>
      <div class="bg-gray-900/70 p-6 rounded-xl hover:scale-105 transition glow-border">
        <img src="https://source.unsplash.com/600x400/?neon,futuristic" class="rounded-lg mb-4">
        <h3 class="text-xl font-semibold mb-2">Neon Studio Interface</h3>
        <p class="text-gray-400 text-sm">A generative interface for futuristic UX.</p>
      </div>
    </div>
  </section> 

  <!-- CONTACT -->
  <section id="contact" class="py-20 text-center bg-gray-900/60">
    <h2 class="text-3xl font-bold mb-6 neon-text">CONTACT</h2>
    <p class="text-gray-300 mb-8">Let's collaborate or create something inspiring.</p>
    <a href="mailto:iyusfirdaus@gmail.com" class="px-8 py-3 border border-indigo-400 rounded-full hover:bg-indigo-500 hover:text-white transition neon-text">
      Say Hello 👋
    </a>
  </section> 

 [https://github.com/masakoiris/Masakoiris.git ](url)[link text](url)

</body>
</html>