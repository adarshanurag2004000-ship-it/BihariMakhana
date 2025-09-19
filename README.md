# BihariMakhana
I am creating a website to deal makhanas
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bihari Makhana - The World Famous Fox Nuts from Bihar</title>
    <meta name="description" content="Discover the authentic taste of world-famous Bihari Makhana. A premium, healthy, and delicious snack sourced directly from the heart of Bihar, India.">
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #111827; /* A dark base color */
        }
        .font-brand {
            font-family: 'Cinzel', serif;
        }
        .hero-bg {
            background-image: linear-gradient(to bottom, rgba(0,0,0,0.8), rgba(0,0,0,0.6)), url('https://img.freepik.com/premium-photo/makhana-fox-nuts-bowl-dark-background-healthy-snack-fasting-eating_748441-267.jpg');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body class="text-gray-200">

    <!-- Header -->
    <header id="header" class="bg-gray-900/80 backdrop-blur-lg sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-3 flex justify-between items-center">
            <!-- Logo -->
            <a href="#" class="flex items-center space-x-2">
                <div class="w-12 h-12">
                     <svg viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                        <defs>
                            <pattern id="makhana-texture-logo" patternUnits="userSpaceOnUse" width="200" height="200">
                                <image href="https://img.freepik.com/premium-photo/close-up-fox-nuts-black-background_965096-73.jpg" x="0" y="0" width="200" height="200" />
                            </pattern>
                            <linearGradient id="gold-logo" x1="0%" y1="0%" x2="0%" y2="100%">
                                <stop offset="0%" stop-color="#FDE047" /><stop offset="100%" stop-color="#EAB308" />
                            </linearGradient>
                            <path id="top-curve-logo" d="M 40,100 a 60,60 0 1,1 120,0" fill="none" />
                            <path id="bottom-curve-logo" d="M 40,100 a 60,60 0 0,0 120,0" fill="none" />
                        </defs>
                        <circle cx="100" cy="100" r="95" fill="url(#makhana-texture-logo)" />
                        <circle cx="100" cy="100" r="75" fill="none" stroke="url(#gold-logo)" stroke-width="4"/>
                        <text font-family="Inter, sans-serif" font-size="12" fill="#FFFFFF" letter-spacing="2" font-weight="500">
                            <textPath xlink:href="#top-curve-logo" startOffset="50%" text-anchor="middle">THE WORLD FAMOUS</textPath>
                        </text>
                        <text class="font-brand" font-size="20" fill="url(#gold-logo)" letter-spacing="1">
                            <textPath xlink:href="#bottom-curve-logo" startOffset="50%" text-anchor="middle">BIHARI MAKHANA</textPath>
                        </text>
                    </svg>
                </div>
                <span class="font-brand text-xl text-yellow-400 hidden sm:inline">Bihari Makhana</span>
            </a>

            <!-- Desktop Nav -->
            <ul class="hidden md:flex items-center space-x-8">
                <li><a href="#home" class="hover:text-yellow-400 transition-colors">Home</a></li>
                <li><a href="#about" class="hover:text-yellow-400 transition-colors">About Us</a></li>
                <li><a href="#products" class="hover:text-yellow-400 transition-colors">Products</a></li>
                <li><a href="#contact" class="hover:text-yellow-400 transition-colors">Contact</a></li>
            </ul>

            <!-- Mobile Menu Button -->
            <button id="mobile-menu-btn" class="md:hidden">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden px-6 pt-2 pb-4 space-y-2">
            <a href="#home" class="block hover:text-yellow-400 transition-colors">Home</a>
            <a href="#about" class="block hover:text-yellow-400 transition-colors">About Us</a>
            <a href="#products" class="block hover:text-yellow-400 transition-colors">Products</a>
            <a href="#contact" class="block hover:text-yellow-400 transition-colors">Contact</a>
        </div>
    </header>

    <main>

        <!-- Hero Section -->
        <section id="home" class="hero-bg min-h-[80vh] flex items-center">
            <div class="container mx-auto px-6 text-center">
                <h1 class="text-4xl md:text-6xl font-brand text-white font-bold leading-tight mb-4">The Authentic Taste of Bihar</h1>
                <p class="text-lg md:text-xl text-gray-300 mb-8 max-w-2xl mx-auto">Experience the superfood snack of kings. Premium, crunchy, and packed with nutrients.</p>
                <a href="#products" class="bg-yellow-500 text-gray-900 font-bold py-3 px-8 rounded-full hover:bg-yellow-400 transition-transform transform hover:scale-105">EXPLORE PRODUCTS</a>
            </div>
        </section>
        
        <!-- About Us Section -->
        <section id="about" class="py-20 bg-gray-900">
            <div class="container mx-auto px-6">
                <div class="grid md:grid-cols-2 gap-12 items-center">
                    <div class="text-center md:text-left">
                        <h2 class="text-3xl font-brand text-yellow-400 mb-4">Our Story: From Bihar's Ponds to Your Palace</h2>
                        <p class="mb-4">Bihari Makhana celebrates the rich heritage of Mithila, Bihar, a region renowned for producing over 90% of the world's Fox Nuts. Our makhana is ethically sourced from local farmers who use traditional harvesting methods passed down through generations.</p>
                        <p>We are committed to delivering not just a snack, but a piece of our culture. Each kernel is carefully selected and roasted to perfection, ensuring a crunchy, guilt-free delight that's as nutritious as it is delicious.</p>
                    </div>
                    <div>
                        <img src="https://images.unsplash.com/photo-1621570233967-3a134a69b47a?q=80&w=2070&auto=format&fit=crop" alt="Bowl of roasted makhana" class="rounded-lg shadow-2xl">
                    </div>
                </div>
            </div>
        </section>

        <!-- Products Section -->
        <section id="products" class="py-20">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl font-brand text-yellow-400 mb-2">Our Premium Selection</h2>
                <p class="text-gray-400 mb-12">Crafted for every palate. Pure, flavored, and always delicious.</p>
                <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Product Card 1 -->
                    <div class="bg-gray-800 rounded-lg shadow-lg overflow-hidden transform hover:-translate-y-2 transition-transform">
                        <img src="https://placehold.co/600x400/1F2937/FBBF24?text=Simply+Salted" class="w-full h-48 object-cover" alt="Simply Salted Makhana">
                        <div class="p-6">
                            <h3 class="text-xl font-semibold mb-2">Simply Salted</h3>
                            <p class="text-gray-400">The timeless classic. Lightly roasted and seasoned with Himalayan pink salt for a perfectly balanced snack.</p>
                        </div>
                    </div>
                    <!-- Product Card 2 -->
                    <div class="bg-gray-800 rounded-lg shadow-lg overflow-hidden transform hover:-translate-y-2 transition-transform">
                        <img src="https://placehold.co/600x400/1F2937/FBBF24?text=Peri+Peri+Spice" class="w-full h-48 object-cover" alt="Peri Peri Spiced Makhana">
                        <div class="p-6">
                            <h3 class="text-xl font-semibold mb-2">Peri Peri Spice</h3>
                            <p class="text-gray-400">A fiery kick for the adventurous. Our signature blend of exotic spices will leave you wanting more.</p>
                        </div>
                    </div>
                    <!-- Product Card 3 -->
                    <div class="bg-gray-800 rounded-lg shadow-lg overflow-hidden transform hover:-translate-y-2 transition-transform">
                        <img src="https://placehold.co/600x400/1F2937/FBBF24?text=Mint+Magic" class="w-full h-48 object-cover" alt="Mint Flavored Makhana">
                        <div class="p-6">
                            <h3 class="text-xl font-semibold mb-2">Mint Magic</h3>
                            <p class="text-gray-400">Cool and refreshing. A delightful combination of pudina (mint) and our crunchy makhana.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-20 bg-gray-900">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl font-brand text-yellow-400 mb-2">Get In Touch</h2>
                <p class="text-gray-400 mb-8">For bulk orders, partnerships, or just to say hello!</p>
                <form class="max-w-xl mx-auto">
                    <div class="grid md:grid-cols-2 gap-4 mb-4">
                        <input type="text" placeholder="Your Name" class="w-full bg-gray-800 rounded-md p-3 border border-gray-700 focus:outline-none focus:ring-2 focus:ring-yellow-500">
                        <input type="email" placeholder="Your Email" class="w-full bg-gray-800 rounded-md p-3 border border-gray-700 focus:outline-none focus:ring-2 focus:ring-yellow-500">
                    </div>
                    <textarea placeholder="Your Message" rows="5" class="w-full bg-gray-800 rounded-md p-3 mb-4 border border-gray-700 focus:outline-none focus:ring-2 focus:ring-yellow-500"></textarea>
                    <button type="submit" class="bg-yellow-500 text-gray-900 font-bold py-3 px-8 rounded-full hover:bg-yellow-400 transition-transform transform hover:scale-105">SEND MESSAGE</button>
                </form>
            </div>
        </section>

    </main>
    
    <!-- Footer -->
    <footer class="bg-gray-900 border-t border-gray-800">
        <div class="container mx-auto px-6 py-8 text-center text-gray-400">
            <p>&copy; 2025 Bihari Makhana. All Rights Reserved.</p>
            <p class="text-sm mt-1">Authentically from Bihar, India. Crafted with love.</p>
        </div>
    </footer>
    
    <script>
        // Mobile menu toggle
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when a link is clicked
        const mobileNavLinks = document.querySelectorAll('#mobile-menu a');
        mobileNavLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>

</body>
</html>

