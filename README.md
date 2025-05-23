# Alby-s-portfolio-<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Alby P Sabu's Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          animation: {
            fadeIn: 'fadeIn 2s ease-in-out',
            bounceIn: 'bounceIn 1s ease',
          },
          keyframes: {
            fadeIn: {
              '0%': { opacity: '0' },
              '100%': { opacity: '1' },
            },
            bounceIn: {
              '0%': { transform: 'scale(0.8)', opacity: '0' },
              '60%': { transform: 'scale(1.05)', opacity: '1' },
              '100%': { transform: 'scale(1)', opacity: '1' },
            },
          },
        }
      }
    }
  </script>
</head>
<body class="bg-gray-50 text-gray-800">
  <!-- Header -->
  <header class="bg-white shadow p-4 sticky top-0 z-10">
    <div class="max-w-6xl mx-auto flex justify-between items-center animate-fadeIn">
      <h1 class="text-2xl font-bold">Alby P Sabu</h1>
      <nav class="space-x-4">
        <a href="#about" class="hover:text-blue-600">About</a>
        <a href="#experience" class="hover:text-blue-600">Experience</a>
        <a href="#skills" class="hover:text-blue-600">Skills</a>
        <a href="#contact" class="hover:text-blue-600">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="text-center py-20 bg-blue-100 animate-fadeIn">
    <img src="alby.jpg" alt="Alby P Sabu" class="mx-auto mb-6 w-40 h-40 object-cover rounded-full shadow-lg animate-bounceIn">
    <h2 class="text-4xl font-bold mb-4">Hi, I'm Alby P Sabu</h2>
    <p class="text-lg mb-4">Aspiring CEO | BCom Finance & Taxation | Insurance Advisor</p>
    <a href="Albypsaburesume.pdf" download class="inline-block px-6 py-2 bg-blue-600 text-white rounded-full hover:bg-blue-700 transition">Download My Resume</a>
    <div class="mt-4">
      <a href="https://www.linkedin.com/in/alby-p-sabu-21177a289?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app" target="_blank" class="text-blue-700 underline hover:text-blue-900">Connect with me on LinkedIn</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-16 max-w-4xl mx-auto px-4 animate-fadeIn">
    <h3 class="text-2xl font-bold mb-4">About Me</h3>
    <p class="mb-2">I'm currently pursuing a BCom degree in Finance and Taxation at Mahatma Gandhi University. Passionate about finance, business, and leadership, I aim to become a CEO in the future.</p>
    <p class="mb-2">I’ve completed a Tax and Accounting internship at Cortal, gaining hands-on experience in Tally ERP 9, Tally Prime, and accounting principles.</p>
    <p>I’ve also attended a Zoho Books Masterclass, learning about cloud accounting, invoice creation, and cloud computing basics.</p>
  </section>

  <!-- Experience Section -->
  <section id="experience" class="py-16 bg-gray-100 max-w-4xl mx-auto px-4 animate-fadeIn">
    <h3 class="text-2xl font-bold mb-4">Experience</h3>
    <ul class="list-disc list-inside space-y-2">
      <li>Insurance Advisor – Special focus on life insurance for salaried women.</li>
      <li>Intern – Tax and Accounting at Cortal (Tally ERP 9, Tally Prime).</li>
      <li>Participant – Zoho Books Masterclass on Cloud Accounting.</li>
    </ul>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="py-16 max-w-4xl mx-auto px-4 animate-fadeIn">
    <h3 class="text-2xl font-bold mb-4">Skills</h3>
    <div class="grid grid-cols-2 gap-4">
      <span>Accounting Principles</span>
      <span>Tally ERP 9 & Tally Prime</span>
      <span>Cloud Accounting</span>
      <span>Communication & Group Discussion</span>
      <span>Leadership & Teamwork</span>
      <span>Financial Planning</span>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-16 bg-white max-w-4xl mx-auto px-4 animate-fadeIn">
    <h3 class="text-2xl font-bold mb-4">Contact Me</h3>
    <p class="mb-2">If you'd like to connect, feel free to email me at <a href="mailto:albypsabujio399@gmail.com" class="text-blue-600 underline">albypsabujio399@gmail.com</a>.</p>
    <p>Phone: <a href="tel:6238027009" class="text-blue-600 underline">6238027009</a></p>
  </section>

  <!-- Footer -->
  <footer class="text-center text-sm py-4 bg-gray-200 mt-8 animate-fadeIn">
    <p>© 2025 Alby P Sabu. All rights reserved.</p>
  </footer>
</body>
</html>
