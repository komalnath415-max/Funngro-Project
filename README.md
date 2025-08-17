# Funngro-Project
A two-page website for Funngro's Website Revamp project.
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Funngro - एक नए भारत का निर्माण</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Inter Font -->
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">

    <!-- Navbar/Header Section -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <!-- Logo -->
            <a href="https://funngro.com" class="text-2xl font-bold text-gray-900">Funngro</a>
            <!-- Mobile Menu Button (hidden on desktop) -->
            <button id="mobile-menu-button" class="md:hidden p-2 text-gray-600 hover:text-gray-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-500 rounded-md">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16m-7 6h7" />
                </svg>
            </button>
            <!-- Desktop Navigation -->
            <nav class="hidden md:flex space-x-6 font-medium">
                <a href="#hero" class="text-gray-600 hover:text-gray-900 transition duration-300">होम</a>
                <a href="#about" class="text-gray-600 hover:text-gray-900 transition duration-300">हमारे बारे में</a>
                <a href="#features" class="text-gray-600 hover:text-gray-900 transition duration-300">सुविधाएँ</a>
                <a href="#contact" class="text-gray-600 hover:text-gray-900 transition duration-300">संपर्क</a>
            </nav>
        </div>
        <!-- Mobile Menu (initially hidden) -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-lg py-2">
            <a href="#hero" class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 transition duration-300">होम</a>
            <a href="#about" class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 transition duration-300">हमारे बारे में</a>
            <a href="#features" class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 transition duration-300">सुविधाएँ</a>
            <a href="#contact" class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 transition duration-300">संपर्क</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="hero" class="relative bg-gradient-to-r from-blue-500 to-purple-600 text-white py-20 px-4 rounded-b-xl overflow-hidden">
        <div class="absolute inset-0 opacity-20" style="background-image: url('https://placehold.co/1000x500/000000/FFFFFF?text=Funngro+Background'); background-size: cover; background-position: center;"></div>
        <div class="container mx-auto relative z-10 text-center">
            <h1 class="text-4xl sm:text-5xl md:text-6xl font-extrabold leading-tight mb-4 drop-shadow-md">
                एक नया भारत, एक नया विकास
            </h1>
            <p class="text-lg sm:text-xl font-light mb-8 max-w-2xl mx-auto drop-shadow-sm">
                बच्चों के लिए डिजिटल शिक्षा और वित्तीय साक्षरता को बढ़ावा देना।
            </p>
            <a href="https://funngro.com" class="inline-block bg-white text-blue-600 font-bold py-3 px-8 rounded-full shadow-lg hover:bg-gray-200 transition-transform transform hover:scale-105 duration-300">
                आज ही शुरू करें
            </a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 px-4 bg-gray-100">
        <div class="container mx-auto">
            <h2 class="text-3xl sm:text-4xl font-bold text-center mb-8">हमारे बारे में</h2>
            <p class="text-center text-lg max-w-3xl mx-auto leading-relaxed">
                Funngro एक ऐसा प्लेटफॉर्म है जो बच्चों को खेल-खेल में सीखने और भविष्य के लिए तैयार होने में मदद करता है। हम वित्तीय साक्षरता, डिजिटल कौशल और रचनात्मकता को बढ़ावा देने के लिए डिज़ाइन किए गए इंटरैक्टिव मॉड्यूल और गतिविधियों की पेशकश करते हैं।
            </p>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="py-16 px-4 bg-white">
        <div class="container mx-auto">
            <h2 class="text-3xl sm:text-4xl font-bold text-center mb-12">हमारी मुख्य सुविधाएँ</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Feature 1 -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-md text-center">
                    <div class="text-blue-500 mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M13 10V3L4 14h7v7l9-11h-7z" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">वित्तीय साक्षरता</h3>
                    <p class="text-gray-600">बच्चों को पैसे का प्रबंधन, बचत और निवेश सिखाएं।</p>
                </div>
                <!-- Feature 2 -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-md text-center">
                    <div class="text-blue-500 mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M9 12h6m-6 4h6m-7 4h8a2 2 0 002-2V6a2 2 0 00-2-2H8a2 2 0 00-2 2v12a2 2 0 002 2z" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">डिजिटल कौशल</h3>
                    <p class="text-gray-600">गेमीफाइड मॉड्यूल के माध्यम से कोडिंग और अन्य डिजिटल कौशल सीखें।</p>
                </div>
                <!-- Feature 3 -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-md text-center">
                    <div class="text-blue-500 mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M19 11H5m14 0a2 2 0 012 2v4a2 2 0 01-2 2H5a2 2 0 01-2-2v-4a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0a2 2 0 012-2h6a2 2 0 012 2M7 7h10" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">रचनात्मकता</h3>
                    <p class="text-gray-600">रचनात्मक सोच और समस्या-समाधान को प्रोत्साहित करें।</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 px-4 bg-gray-100">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl sm:text-4xl font-bold mb-4">संपर्क करें</h2>
            <p class="text-lg max-w-2xl mx-auto mb-8">
                अधिक जानकारी के लिए, कृपया हमें ईमेल करें या सोशल मीडिया पर फॉलो करें।
            </p>
            <div class="flex justify-center space-x-4">
                <a href="mailto:info@funngro.com" class="bg-blue-600 text-white font-semibold py-3 px-6 rounded-full hover:bg-blue-700 transition duration-300">
                    ईमेल भेजें
                </a>
                <a href="https://funngro.com" class="bg-gray-300 text-gray-800 font-semibold py-3 px-6 rounded-full hover:bg-gray-400 transition duration-300">
                    अधिक जानें
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8 px-4 rounded-t-xl">
        <div class="container mx-auto text-center">
            <p>&copy; 2025 Funngro. सर्वाधिकार सुरक्षित।</p>
            <p class="text-sm mt-2">
                <a href="#" class="hover:underline">गोपनीयता नीति</a> | <a href="#" class="hover:underline">सेवा की शर्तें</a>
            </p>
        </div>
    </footer>

    <!-- JavaScript for Mobile Menu -->
    <script>
        // Mobile menu toggle logic
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
    </script>
</body>
</html>
