<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>NAGIREDDY RAMESH KUMAR REDDY — Portfolio</title>
  <meta name="description" content="Portfolio of NAGIREDDY RAMESH KUMAR REDDY: Python developer, projects, skills, education, and contact." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: { sans: ['Inter', 'ui-sans-serif', 'system-ui'] },
          colors: { brand: { 600: '#2563eb', 700: '#1d4ed8' } },
          boxShadow: { soft: '0 10px 25px -10px rgba(0,0,0,0.15)' }
        }
      },
      darkMode: 'class'
    }
  </script>
</head>
<body class="bg-white text-slate-800 dark:bg-slate-950 dark:text-slate-100 font-sans">

  <!-- Hero -->
  <section id="home" class="py-20 px-6 max-w-5xl mx-auto">
    <h1 class="text-4xl font-extrabold">Hi, I'm <span class="text-brand-600">NAGIREDDY RAMESH KUMAR REDDY</span></h1>
    <p class="mt-4 text-lg">Enthusiastic and dedicated Python Developer with foundational knowledge in web development technologies including HTML and CSS. Passionate about continuous learning and growth within the tech industry.</p>
    <div class="mt-6 flex gap-4">
      <a href="#projects" class="px-5 py-3 rounded-xl bg-brand-600 text-white font-medium hover:bg-brand-700">View Projects</a>
      <a href="#contact" class="px-5 py-3 rounded-xl border border-slate-300 font-medium hover:shadow-soft">Contact Me</a>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills" class="py-16 px-6 max-w-5xl mx-auto border-t">
    <h2 class="text-3xl font-bold">Skills</h2>
    <div class="mt-6 grid md:grid-cols-2 gap-6">
      <div>
        <h3 class="font-semibold">Technical</h3>
        <ul class="mt-3 space-y-2 text-slate-700 dark:text-slate-300">
          <li>Python,HTML</li>
           </ul>
      </div>
      <div>
          <h3 class="font-semibold">Tools</h3>
          <li> Notepad++, VS Code, Power BI,MS Excel</li>
        </ul>
      </div>
      <div>
        <h3 class="font-semibold">Languages Known</h3>
        <ul class="mt-3 space-y-2 text-slate-700 dark:text-slate-300">
          <li>English</li>
          <li>Telugu</li>
          <li>Hindi</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="py-16 px-6 max-w-5xl mx-auto border-t">
    <h2 class="text-3xl font-bold">Projects</h2>
    <div class="mt-6 grid md:grid-cols-2 gap-6">
      <div class="p-6 rounded-xl border hover:shadow-soft">
        <h3 class="font-semibold text-xl">Real-Time Drowsiness Detection System for Drivers</h3>
        <p class="mt-2 text-slate-700 dark:text-slate-300">Developed a system using computer vision algorithms to detect driver drowsiness by measuring forward head tilt angle and eye aspect ratio and alerting drivers to prevent accidents.
      </div>
    </div>
  </section>

  <!-- Education -->
  <section id="education" class="py-16 px-6 max-w-5xl mx-auto border-t">
    <h2 class="text-3xl font-bold">Education</h2>
    <ul class="mt-6 space-y-4">
      <li>
        <p class="font-semibold">B.Tech in ECE — Sri Venkateswara College Of Engineering & Technology</p>
        <p class="text-slate-600 dark:text-slate-300">2022 – 2026 </p>
         <p class="text-slate-600 dark:text-slate-300"> CGPA 8.33</p>
      </li>
      <li>
        <p class="font-semibold">Intermediate — BJSR Jr College</p>
        <p class="text-slate-600 dark:text-slate-300">2020 – 2022 </p>
         <p class="text-slate-600 dark:text-slate-300">87% </p>
      </li>
      <li>
        <p class="font-semibold">SSC — Keshava Reddy EMHS</p>
        <p class="text-slate-600 dark:text-slate-300">2019 – 2020 </p>
        <p class="text-slate-600 dark:text-slate-300">94%</p>
      </li>
    </ul>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-16 px-6 max-w-5xl mx-auto border-t">
    <h2 class="text-3xl font-bold">Contact</h2>
    <p class="mt-4">Feel free to reach out to me for collaborations, opportunities, or just to connect.</p>
    <ul class="mt-6 space-y-2">
      <li><strong>Email:</strong> <a href="mailto:nagireddyr112@gmail.com" class="text-brand-600 hover:underline">nagireddyr112@gmail.com</a></li>
      <li><strong>Phone:</strong> +91 8074973074</li>
      <li><strong>Location:</strong> Kadapa, Andhra Pradesh</li>
    </ul>
  </section>

  <footer class="py-6 text-center border-t">
    <p>© <span id="year"></span> NAGIREDDY RAMESH KUMAR REDDY. All rights reserved.</p>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
