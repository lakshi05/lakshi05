<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lakshiyien Namasivayam | Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-slate-900 text-slate-100 font-sans leading-relaxed">

  <!-- Navigation -->
  <nav class="max-w-5xl mx-auto p-6 flex justify-between items-center border-b border-slate-800">
    <h1 class="text-xl font-bold tracking-wider text-teal-400">Lakshiyien N.</h1>
    <div class="space-x-6 text-sm text-slate-400">
      <a href="#about" class="hover:text-teal-400 transition">About</a>
      <a href="#projects" class="hover:text-teal-400 transition">Projects</a>
      <a href="#experience" class="hover:text-teal-400 transition">Experience</a>
      <a href="#contact" class="hover:text-teal-400 transition">Contact</a>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="max-w-5xl mx-auto px-6 py-20">
    <p class="text-teal-400 font-mono text-sm mb-2">Hi, my name is</p>
    <h2 class="text-4xl sm:text-6xl font-extrabold text-slate-100">Lakshiyien Namasivayam.</h2>
    <h3 class="text-3xl sm:text-5xl font-bold text-slate-400 mt-2">Data Analyst in the Making.</h3>
    <p class="mt-6 max-w-2xl text-slate-400">
      BSc Statistics student at the University of Auckland specializing in Applied Statistics. Passionate about statistical modeling, turning raw data into actionable insights, and building end-to-end analytical workflows[cite: 1].
    </p>
    <div class="mt-8 flex gap-4">
      <a href="mailto:lakshiyien777@gmail.com" class="px-6 py-3 border border-teal-400 text-teal-400 rounded hover:bg-teal-400/10 transition">Get In Touch</a>
      <a href="https://www.linkedin.com/in/l-namasivayam" target="_blank" class="px-6 py-3 border border-slate-700 text-slate-300 rounded hover:border-slate-500 transition">LinkedIn</a>
    </div>
  </header>

  <!-- Projects Section -->
  <section id="projects" class="max-w-5xl mx-auto px-6 py-12">
    <h2 class="text-2xl font-bold text-slate-100 mb-8 border-l-4 border-teal-400 pl-3">Featured Projects</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      
      <!-- Project 1 -->
      <div class="bg-slate-800/50 p-6 rounded-lg border border-slate-700/50 hover:border-slate-600 transition">
        <h3 class="text-xl font-bold text-slate-200">NZ Housing Market Analysis</h3>
        <p class="text-slate-400 text-sm mt-2">
          Analyzed long-term New Zealand housing trends using Reserve Bank of New Zealand (RBNZ) datasets and regression modeling[cite: 1].
        </p>
        <div class="mt-4 flex gap-2 font-mono text-xs text-teal-400">
          <span>R</span> • <span>Regression Modeling</span> • <span>RBNZ Data</span>
        </div>
      </div>

      <!-- Project 2 -->
      <div class="bg-slate-800/50 p-6 rounded-lg border border-slate-700/50 hover:border-slate-600 transition">
        <h3 class="text-xl font-bold text-slate-200">Live Gym Session Tracker</h3>
        <p class="text-slate-400 text-sm mt-2">
          Built an automated data pipeline capturing inputs via Google Forms to generate dynamic, automated R Markdown reports[cite: 1].
        </p>
        <div class="mt-4 flex gap-2 font-mono text-xs text-teal-400">
          <span>R Markdown</span> • <span>Google Forms API</span> • <span>Automation</span>
        </div>
      </div>

    </div>
  </section>

  <!-- Experience & Simulations Section -->
  <section id="experience" class="max-w-5xl mx-auto px-6 py-12">
    <h2 class="text-2xl font-bold text-slate-100 mb-8 border-l-4 border-teal-400 pl-3">Experience & Simulations</h2>
    <div class="space-y-6">

      <div class="bg-slate-800/30 p-6 rounded border border-slate-800">
        <div class="flex justify-between items-start">
          <h3 class="font-bold text-slate-200">Administrative Assistant <span class="text-teal-400">@ AI Izhiqar Trading & Supply LLC</span></h3>
          <span class="text-xs text-slate-500 font-mono">Nov 2025 – Jan 2026</span>
        </div>
        <ul class="list-disc list-inside text-sm text-slate-400 mt-2 space-y-1">
          <li>Audited invoice and expense records to identify reporting discrepancies and improve financial accuracy[cite: 1].</li>
          <li>Designed structured documentation systems to reduce retrieval time across workflows[cite: 1].</li>
        </ul>
      </div>

      <div class="bg-slate-800/30 p-6 rounded border border-slate-800">
        <div class="flex justify-between items-start">
          <h3 class="font-bold text-slate-200">STATS 210 Class Representative <span class="text-teal-400">@ University of Auckland</span></h3>
          <span class="text-xs text-slate-500 font-mono">Jul 2025 – Oct 2025</span>
        </div>
        <ul class="list-disc list-inside text-sm text-slate-400 mt-2 space-y-1">
          <li>Acted as liaison between 100+ students and faculty to synthesize feedback into academic improvements[cite: 1].</li>
        </ul>
      </div>

    </div>
  </section>

  <!-- Contact Section -->
  <footer id="contact" class="max-w-5xl mx-auto px-6 py-20 text-center border-t border-slate-800">
    <h2 class="text-3xl font-bold text-slate-100">Get In Touch</h2>
    <p class="text-slate-400 max-w-md mx-auto mt-2 text-sm">
      Open to Auckland Analytics & Data Internships for 2026[cite: 1]. Feel free to reach out via email or LinkedIn!
    </p>
    <div class="mt-6">
      <a href="mailto:lakshiyien777@gmail.com" class="text-teal-400 border border-teal-400 px-6 py-3 rounded hover:bg-teal-400/10 transition inline-block">
        Say Hello
      </a>
    </div>
    <p class="text-xs text-slate-600 mt-12">Designed for deployment on Netlify • Lakshiyien Namasivayam</p>
  </footer>

</body>
</html>
