<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kittikorn Kramsaniit - Interactive Resume</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- FontAwesome Icons CDN -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <!-- Google Fonts: Inter & Prompt -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Prompt:wght@300;400;500;600&display=swap" rel="stylesheet">
  
  <style>
    body {
      font-family: 'Inter', 'Prompt', sans-serif;
    }
    @media print {
      .no-print {
        display: none !important;
      }
      body {
        background-color: white !important;
      }
      .resume-card {
        box-shadow: none !important;
        margin: 0 !important;
        max-width: 100% !important;
      }
    }
  </style>
</head>
<body class="bg-slate-100 min-h-screen py-6 px-4 sm:px-6 lg:px-8">

  <!-- Top Action Bar (Hide in Print) -->
  <div class="max-w-4xl mx-auto mb-6 flex justify-between items-center no-print">
    <span class="text-sm text-slate-500 font-medium">
      <i class="fa-solid fa-code branch me-1"></i> Ready for GitHub Pages
    </span>
    <button onclick="window.print()" class="bg-indigo-600 hover:bg-indigo-700 text-white font-medium py-2 px-4 rounded-lg shadow transition flex items-center gap-2 text-sm">
      <i class="fa-solid fa-print"></i> พิมพ์ / Save as PDF
    </button>
  </div>

  <!-- Main Resume Container -->
  <div class="resume-card max-w-4xl mx-auto bg-white rounded-xl shadow-2xl overflow-hidden grid grid-cols-1 md:grid-cols-12 min-h-[900px]">
    
    <!-- LEFT COLUMN: Dark Sidebar -->
    <aside class="md:col-span-4 bg-[#181e24] text-slate-100 p-6 flex flex-col justify-between">
      <div>
        <!-- Profile Image Placeholder -->
        <div class="relative w-40 h-48 mx-auto mb-6 rounded-lg overflow-hidden border-2 border-slate-700 bg-slate-800 shadow-lg">
          <!-- Note: Replace "profile.jpg" with your image file name in GitHub repo -->
          <img src="profile.jpg" alt="Kittikorn Kramsaniit" class="w-full h-full object-cover" onError="this.onerror=null; this.src='https://via.placeholder.com/160x192/2d3748/ffffff?text=Kittikorn';">
        </div>

        <!-- Name & Header -->
        <div class="mb-8 text-center md:text-left">
          <h1 class="text-2xl font-bold tracking-tight text-white">Kittikorn<br>Kramsaniit</h1>
          <p class="text-sm text-slate-400 mt-1 font-medium">Student, Faculty of Applied Science</p>
        </div>

        <!-- Contact Information -->
        <div class="mb-8 space-y-4">
          <h2 class="text-xs uppercase font-bold tracking-wider text-indigo-400 border-b border-slate-700 pb-1">Contact information</h2>
          
          <div class="flex items-start gap-3 text-sm text-slate-300">
            <i class="fa-solid fa-phone text-indigo-400 mt-1 w-4 text-center"></i>
            <a href="tel:0822644302" class="hover:text-white transition">082-264-4302</a>
          </div>

          <div class="flex items-start gap-3 text-sm text-slate-300">
            <i class="fa-solid fa-envelope text-indigo-400 mt-1 w-4 text-center"></i>
            <a href="mailto:s6704022617147@email.kmutnb.ac.th" class="hover:text-white transition break-all">s6704022617147@email.kmutnb.ac.th</a>
          </div>

          <div class="flex items-start gap-3 text-sm text-slate-300">
            <i class="fa-solid fa-location-dot text-indigo-400 mt-1 w-4 text-center"></i>
            <span>37/1 22 Phibunsongkhram Road, Mueang Nonthaburi District, Nonthaburi 11000</span>
          </div>
        </div>

        <!-- Abilities / Skills -->
        <div class="mb-8">
          <h2 class="text-xs uppercase font-bold tracking-wider text-indigo-400 border-b border-slate-700 pb-2 mb-3">Abilities/Skills</h2>
          <ul class="space-y-2 text-sm text-slate-300">
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-400"></span> Visual Studio Code</li>
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-400"></span> Python & Algorithms</li>
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-400"></span> Mathematics & Modeling</li>
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-400"></span> Graphic Design</li>
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-400"></span> Digital Art</li>
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-400"></span> Web Design</li>
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-400"></span> Product Design</li>
          </ul>
        </div>

        <!-- Language Skills -->
        <div class="mb-6">
          <h2 class="text-xs uppercase font-bold tracking-wider text-indigo-400 border-b border-slate-700 pb-2 mb-4">Language skills</h2>
          
          <div class="space-y-3">
            <div>
              <div class="flex justify-between text-xs font-medium mb-1">
                <span>Thai</span>
                <span class="text-slate-400">Excellent</span>
              </div>
              <div class="w-full bg-slate-700 h-1.5 rounded-full overflow-hidden">
                <div class="bg-indigo-400 h-full rounded-full" style="width: 95%"></div>
              </div>
            </div>

            <div>
              <div class="flex justify-between text-xs font-medium mb-1">
                <span>English</span>
                <span class="text-slate-400">Excellent</span>
              </div>
              <div class="w-full bg-slate-700 h-1.5 rounded-full overflow-hidden">
                <div class="bg-indigo-400 h-full rounded-full" style="width: 90%"></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </aside>

    <!-- RIGHT COLUMN: Main Content -->
    <main class="md:col-span-8 p-8 flex flex-col justify-between bg-white text-slate-800">
      <div class="space-y-8">
        
        <!-- SUMMARY -->
        <section>
          <h2 class="text-lg font-bold text-slate-900 border-b-2 border-slate-800 pb-1 mb-3 tracking-wide uppercase">SUMMARY</h2>
          <p class="text-sm text-slate-600 leading-relaxed text-justify">
            I am a graduate from King Mongkut's University of Technology North Bangkok, majoring in Computer Science Mathematics (MQ). With a strong foundation in mathematics and computer science, I possess solid analytical, programming, and logical problem-solving skills. I am passionate about integrating mathematical concepts with practical computer applications in software development. I am eager to contribute to innovative projects and collaborate effectively in a professional team.
          </p>
        </section>

        <!-- EDUCATION -->
        <section>
          <h2 class="text-lg font-bold text-slate-900 border-b-2 border-slate-800 pb-1 mb-4 tracking-wide uppercase">EDUCATION</h2>
          <div class="space-y-4">
            <div class="grid grid-cols-1 sm:grid-cols-12 gap-1 sm:gap-4 text-sm">
              <div class="sm:col-span-4 font-semibold text-slate-800">2026 - Present</div>
              <div class="sm:col-span-8 text-slate-600">
                <strong class="text-slate-900 block">King Mongkut's University of Technology North Bangkok</strong>
                Faculty of Applied Science, Department of Computer Science Mathematics
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-12 gap-1 sm:gap-4 text-sm">
              <div class="sm:col-span-4 font-semibold text-slate-800">2023 - 2025</div>
              <div class="sm:col-span-8 text-slate-600">
                <strong class="text-slate-900 block">Completed</strong>
                Faculty of Applied Science, Department of Computer Science Mathematics
              </div>
            </div>
          </div>
        </section>

        <!-- PROFESSIONAL EXPERIENCE & PROJECTS -->
        <section>
          <h2 class="text-lg font-bold text-slate-900 border-b-2 border-slate-800 pb-1 mb-4 tracking-wide uppercase">PROFESSIONAL EXPERIENCE & PROJECTS</h2>
          <div class="space-y-5">
            
            <div class="grid grid-cols-1 sm:grid-cols-12 gap-1 sm:gap-4 text-sm">
              <div class="sm:col-span-3 font-semibold text-slate-800">2026</div>
              <div class="sm:col-span-9">
                <h3 class="font-bold text-slate-900">DN 2026: Domain/Hosting System Project</h3>
                <p class="text-slate-600 text-xs mt-1">Design and install Turnkey Hosting System.</p>
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-12 gap-1 sm:gap-4 text-sm">
              <div class="sm:col-span-3 font-semibold text-slate-800">2025</div>
              <div class="sm:col-span-9">
                <h3 class="font-bold text-slate-900">Artificial Web & Mobile Intelligence Development Project</h3>
                <p class="text-slate-600 text-xs mt-1">
                  Development code for a sales system for a website that will seat stills electronic devices.
                </p>
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-12 gap-1 sm:gap-4 text-sm">
              <div class="sm:col-span-3 font-semibold text-slate-800">2024</div>
              <div class="sm:col-span-9">
                <h3 class="font-bold text-slate-900">Object-Oriented Programming Project - <em class="not-italic text-indigo-600">Super Battle City</em></h3>
                <p class="text-slate-600 text-xs mt-1">
                  Artificial to a sales solution for a website & involvement project (Name chat with electronic devices).
                </p>
              </div>
            </div>

          </div>
        </section>

        <!-- SOFTWARE -->
        <section>
          <h2 class="text-lg font-bold text-slate-900 border-b-2 border-slate-800 pb-1 mb-4 tracking-wide uppercase">SOFTWARE</h2>
          <div class="grid grid-cols-3 sm:grid-cols-5 gap-4 text-center">
            
            <div class="p-3 bg-slate-50 rounded-lg hover:bg-slate-100 transition border border-slate-100 flex flex-col items-center justify-center">
              <i class="fa-solid fa-code text-blue-500 text-2xl mb-2"></i>
              <span class="text-xs font-semibold text-slate-700">Visual Studio Code</span>
            </div>

            <div class="p-3 bg-slate-50 rounded-lg hover:bg-slate-100 transition border border-slate-100 flex flex-col items-center justify-center">
              <i class="fa-solid fa-[#F9AB00] fa-infinity text-amber-500 text-2xl mb-2"></i>
              <span class="text-xs font-semibold text-slate-700">Google Colab</span>
            </div>

            <div class="p-3 bg-slate-50 rounded-lg hover:bg-slate-100 transition border border-slate-100 flex flex-col items-center justify-center">
              <i class="fa-solid fa-file-excel text-emerald-600 text-2xl mb-2"></i>
              <span class="text-xs font-semibold text-slate-700">Excel</span>
            </div>

            <div class="p-3 bg-slate-50 rounded-lg hover:bg-slate-100 transition border border-slate-100 flex flex-col items-center justify-center">
              <i class="fa-solid fa-image text-blue-700 text-2xl mb-2"></i>
              <span class="text-xs font-semibold text-slate-700">Adobe Photoshop</span>
            </div>

            <div class="p-3 bg-slate-50 rounded-lg hover:bg-slate-100 transition border border-slate-100 flex flex-col items-center justify-center">
              <i class="fa-solid fa-drafting-compass text-red-600 text-2xl mb-2"></i>
              <span class="text-xs font-semibold text-slate-700">AutoCAD</span>
            </div>

          </div>
        </section>

      </div>

      <!-- Footer Note -->
      <div class="mt-8 pt-4 border-t border-slate-100 text-center text-xs text-slate-400 no-print">
        © 2026 Kittikorn Kramsaniit. Built with Tailwind CSS & hosted on GitHub Pages.
      </div>
    </main>

  </div>

</body>
</html>