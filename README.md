<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CyberGuard Insights</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <meta name="description" content="CyberGuard Insights: Professional cybersecurity whitepapers and blog for industry professionals.">
  <link rel="icon" href="/favicon.ico">
</head>
<body class="bg-gray-50 text-gray-800 font-sans">
  <!-- Navigation -->
  <header class="bg-white shadow">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
      <a href="#" class="text-xl font-bold text-gray-900">CyberGuard Insights</a>
      <nav class="space-x-4">
        <a href="#whitepapers" class="hover:text-indigo-600">Whitepapers</a>
        <a href="#blog" class="hover:text-indigo-600">Blog</a>
        <a href="https://blog.example.com/Cole_Mains_Resume_2025.pdf" class="hover:text-indigo-600" target="_blank" rel="noopener">Resume</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="bg-gradient-to-r from-indigo-600 to-blue-500 text-white py-20">
    <div class="container mx-auto px-6 text-center">
      <h1 class="text-4xl font-extrabold mb-4">CyberGuard Insights</h1>
      <p class="mb-6 text-lg">In-depth whitepapers & expert articles on the latest in cybersecurity.</p>
      <a href="#whitepapers" class="bg-white text-indigo-600 px-6 py-3 rounded-lg font-semibold hover:bg-gray-100">View Whitepapers</a>
    </div>
  </section>

  <!-- Featured Whitepapers -->
  <section id="whitepapers" class="container mx-auto px-6 py-16">
    <h2 class="text-3xl font-semibold mb-6">Featured Whitepapers</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

      <!-- Zero Trust -->
      <div class="bg-white rounded-lg shadow-lg overflow-hidden">
        <img src="/assets/images/zero-trust-cover.jpg" alt="Zero Trust in Practice" class="w-full h-48 object-cover">
        <div class="p-6">
          <h3 class="text-2xl font-bold mb-2">Zero Trust in Practice</h3>
          <p class="text-gray-600 mb-4">Explore the principles, implementation strategies, and real-world case studies of Zero Trust architecture in modern enterprises.</p>
          <a href="/assets/whitepapers/zero-trust.pdf" class="text-indigo-600 font-semibold hover:underline">Download PDF</a>
        </div>
      </div>

      <!-- SIEM Optimization -->
      <div class="bg-white rounded-lg shadow-lg overflow-hidden">
        <img src="/assets/images/siem-logs.jpg" alt="SIEM Optimization" class="w-full h-48 object-cover">
        <div class="p-6">
          <h3 class="text-2xl font-bold mb-2">SIEM Optimization Through Automated Log Parsing</h3>
          <p class="text-gray-600 mb-4">Techniques for building custom Python scripts that extract and analyze logs across multiple platforms for streamlined threat detection.</p>
          <a href="/assets/whitepapers/siem-log-parsing.pdf" class="text-indigo-600 font-semibold hover:underline">Download PDF</a>
        </div>
      </div>

      <!-- Azure Security -->
      <div class="bg-white rounded-lg shadow-lg overflow-hidden">
        <img src="/assets/images/azure-security.jpg" alt="Cloud Security Best Practices in Azure" class="w-full h-48 object-cover">
        <div class="p-6">
          <h3 class="text-2xl font-bold mb-2">Cloud Security Best Practices in Azure</h3>
          <p class="text-gray-600 mb-4">Strategies for securing virtual networks, managing IAM policies, and implementing Microsoft Defender for Cloud.</p>
          <a href="/assets/whitepapers/azure-security.pdf" class="text-indigo-600 font-semibold hover:underline">Download PDF</a>
        </div>
      </div>

      <!-- Incident Response -->
      <div class="bg-white rounded-lg shadow-lg overflow-hidden">
        <img src="/assets/images/incident-response.jpg" alt="Incident Response Playbooks for 2025" class="w-full h-48 object-cover">
        <div class="p-6">
          <h3 class="text-2xl font-bold mb-2">Incident Response Playbooks for 2025</h3>
          <p class="text-gray-600 mb-4">Step-by-step playbooks based on real-world attacks with mapped detection, escalation, and containment workflows.</p>
          <a href="/assets/whitepapers/incident-response-2025.pdf" class="text-indigo-600 font-semibold hover:underline">Download PDF</a>
        </div>
      </div>

      <!-- Penetration Testing -->
      <div class="bg-white rounded-lg shadow-lg overflow-hidden">
        <img src="/assets/images/pen-testing.jpg" alt="Penetration Testing Methodologies" class="w-full h-48 object-cover">
        <div class="p-6">
          <h3 class="text-2xl font-bold mb-2">Penetration Testing Methodologies with Burp Suite & Nmap</h3>
          <p class="text-gray-600 mb-4">Hands-on methodology using industry-standard tools for black-box and white-box testing, written from a field-tested perspective.</p>
          <a href="/assets/whitepapers/pen-testing-methods.pdf" class="text-indigo-600 font-semibold hover:underline">Download PDF</a>
        </div>
      </div>

    </div>
  </section>

  <!-- Blog Section -->
  <section id="blog" class="bg-gray-100 py-16">
    <div class="container mx-auto px-6">
      <h2 class="text-3xl font-semibold mb-6">Latest Blog Posts</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Post 1 -->
        <article class="bg-white rounded-lg shadow p-6">
          <h4 class="text-xl font-bold mb-2">Understanding Ransomware Trends in 2025</h4>
          <p class="mb-4 text-gray-600">A deep dive into the evolution of ransomware tactics and how organizations can defend against them.</p>
          <a href="#" class="text-indigo-600 font-semibold hover:underline">Read More →</a>
        </article>
        <!-- Post 2 -->
        <article class="bg-white rounded-lg shadow p-6">
          <h4 class="text-xl font-bold mb-2">Implementing MFA: Tips & Pitfalls</h4>
          <p class="mb-4 text-gray-600">Best practices for multi-factor authentication deployment across diverse environments.</p>
          <a href="#" class="text-indigo-600 font-semibold hover:underline">Read More →</a>
        </article>
        <!-- Post 3 -->
        <article class="bg-white rounded-lg shadow p-6">
          <h4 class="text-xl font-bold mb-2">Securing Cloud-Native Applications</h4>
          <p class="mb-4 text-gray-600">Strategies and tools for ensuring continuous security in containerized microservices.</p>
          <a href="#" class="text-indigo-600 font-semibold hover:underline">Read More →</a>
        </article>
      </div>
    </div>
  </section>

  <!-- Resume Section -->
  <section id="resume" class="container mx-auto px-6 py-16">
    <h2 class="text-3xl font-semibold mb-6">About Me & Resume</h2>
    <p class="mb-4">I am a cybersecurity professional with experience in threat analysis, penetration testing, and secure architecture design. View my full resume to learn more about my skills and experiences.</p>
    <a href="https://blog.example.com/Cole_Mains_Resume_2025.pdf" class="bg-indigo-600 text-white px-6 py-3 rounded-lg font-semibold hover:bg-indigo-700">Download Resume</a>
  </section>

  <!-- Footer -->
  <footer class="bg-white border-t py-6">
    <div class="container mx-auto px-6 text-center">
      <p class="text-gray-600">© 2025 CyberGuard Insights. All rights reserved.</p>
      <div class="mt-4">
        <a href="#" class="mx-2 hover:text-indigo-600">Privacy</a>
        <a href="#" class="mx-2 hover:text-indigo-600">Terms</a>
      </div>
    </div>
  </footer>
</body>
</html>
