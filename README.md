<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jake Palmer for Dorm Hall President</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700;800&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .gradient-text {
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
        }
        .cta-button {
            transition: all 0.3s ease-in-out;
        }
        .cta-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header & Navigation -->
    <header id="home" class="bg-white/80 backdrop-blur-md sticky top-0 z-50 shadow-sm">
        <div class="w-full max-w-screen-2xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#home" class="text-xl font-bold text-indigo-600 whitespace-nowrap">Jake Palmer & Zander Mettler</a>
            <nav class="hidden md:flex space-x-6 items-center">
                <a href="#about" class="text-gray-600 hover:text-indigo-600 transition-colors whitespace-nowrap">About Us</a>
                <a href="#philosophy" class="text-gray-600 hover:text-indigo-600 transition-colors whitespace-nowrap">Our Philosophy</a>
                <a href="#platform" class="text-gray-600 hover:text-indigo-600 transition-colors whitespace-nowrap">Our Promises</a>
                <a href="#impact" class="text-gray-600 hover:text-indigo-600 transition-colors whitespace-nowrap">Our Impact</a>
                <a href="#events" class="text-gray-600 hover:text-indigo-600 transition-colors">Events</a>
                <a href="#contact" class="bg-indigo-600 text-white px-4 py-2 rounded-lg shadow-md hover:bg-indigo-700 transition-all cta-button whitespace-nowrap">Contact Us</a>
            </nav>
            <button id="mobile-menu-button" class="md:hidden">
                <i data-lucide="menu" class="text-gray-700"></i>
            </button>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden px-6 pb-4">
            <a href="#about" class="block py-2 text-gray-600 hover:text-indigo-600">About Us</a>
            <a href="#philosophy" class="block py-2 text-gray-600 hover:text-indigo-600">Our Philosophy</a>
            <a href="#platform" class="block py-2 text-gray-600 hover:text-indigo-600">Our Promises</a>
            <a href="#impact" class="block py-2 text-gray-600 hover:text-indigo-600">Our Impact</a>
            <a href="#events" class="block py-2 text-gray-600 hover:text-indigo-600">Events</a>
            <a href="#contact" class="block mt-2 bg-indigo-600 text-white text-center px-4 py-2 rounded-lg shadow-md hover:bg-indigo-700 transition-all cta-button">Contact Us</a>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="py-24 md:py-32 bg-white">
            <div class="w-full max-w-screen-2xl mx-auto px-6 text-center">
                <img src="DSC_0142-removebg-preview.png" alt="Jake Palmer" class="w-32 h-32 md:w-40 md:h-40 object-cover mx-auto rounded-full shadow-2xl mb-6 ring-4 ring-indigo-100" onerror="this.onerror=null;this.src='https://placehold.co/150x150/E9D5FF/4C1D95?text=Jake+P';">
                <h1 class="text-4xl md:text-6xl font-extrabold mb-4">
                    The <span class="gradient-text bg-gradient-to-r from-indigo-500 to-purple-600">Communal Fork Party</span>
                </h1>
                <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-8">Led by Jake Palmer and Zander Mettler, we're here to provide the essentials for a better dorm life.</p>
                <a href="#platform" class="bg-indigo-600 text-white px-8 py-3 rounded-full font-bold text-lg shadow-lg hover:bg-indigo-700 transition-all cta-button">See Our Promises</a>
            </div>
        </section>

        <!-- About Us Section -->
        <section id="about" class="py-20 md:py-28">
            <div class="w-full max-w-screen-2xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-3xl font-bold mb-4 text-gray-900">Meet <span class="text-indigo-600">Jake & Zander</span></h2>
                    <p class="text-gray-700 mb-4 leading-relaxed">
                        We are the Communal Fork Party, and we're running for Dorm Hall President and Vice President because we believe in direct action and practical solutions. We've seen a need for basic amenities that make life easier, and we're here to deliver.
                    </p>
                    <p class="text-gray-700 mb-4 leading-relaxed">
                        Our philosophy is simple: focus on what matters. Instead of vague promises, we're committing to tangible improvements that you'll use every day. We're dedicated to making our dorm a more convenient and functional place for everyone.
                    </p>
                </div>
                <div class="flex justify-center">
                    <img src="DSC_0138-removebg-preview.png" alt="Zander Mettler" class="rounded-2xl shadow-xl w-full max-w-md" onerror="this.onerror=null;this.src='https://placehold.co/600x400/E0E7FF/4338CA?text=Zander+M';">
                </div>
            </div>
        </section>
        
        <!-- Our Philosophy Section -->
        <section id="philosophy" class="py-20 md:py-28 bg-white">
            <div class="w-full max-w-4xl mx-auto px-6 text-center">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900">The Philosophy of the Communal Fork</h2>
                <p class="text-lg text-gray-600 mt-2 mb-8">It's more than just a utensil; it's an idea.</p>
                <div class="text-left space-y-4 text-gray-700 leading-relaxed bg-gray-50 p-8 rounded-2xl border border-gray-200">
                     <p>
                        At its heart, the name "Communal Fork Party" is a rhetorical concept. Imagine a single, shared fork for the entire dorm. In this ideal world, that fork represents ultimate unity, trust, and shared experience. It symbolizes that we are one community, eating from the same table, relying on the same tools. It's a powerful image of togetherness.
                    </p>
                    <p>
                        But we are pragmatists. We understand the practical and hygienic challenges of a single fork. That’s why we are compromising. Our promise of readily available plastic forks is the tangible manifestation of this ideal. Each individual fork is your personal key to the communal spirit. It’s not about sharing the <em>same</em> fork, but sharing the <em>idea</em> that everyone in our community will always have what they need, when they need it. We're providing the tools for community, one clean fork at a time.
                    </p>
                </div>
            </div>
        </section>

        <!-- Platform Section -->
        <section id="platform" class="py-20 md:py-28">
            <div class="w-full max-w-screen-2xl mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900">Our Three Main Promises</h2>
                    <p class="text-lg text-gray-600 mt-2">Simple. Essential. Guaranteed.</p>
                </div>
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Platform Point 1 -->
                    <div class="bg-white p-8 rounded-2xl shadow-md border border-gray-100 hover:shadow-lg transition-shadow">
                        <div class="flex items-center justify-center h-12 w-12 rounded-full bg-indigo-100 text-indigo-600 mb-4">
                            <i data-lucide="utensils-crossed"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-2">Plastic Forks</h3>
                        <p class="text-gray-600">Never get caught without a utensil again. We'll ensure a steady supply of plastic forks is always available in the common areas for your late-night ramen or leftover pizza.</p>
                    </div>
                    <!-- Platform Point 2 -->
                    <div class="bg-white p-8 rounded-2xl shadow-md border border-gray-100 hover:shadow-lg transition-shadow">
                        <div class="flex items-center justify-center h-12 w-12 rounded-full bg-indigo-100 text-indigo-600 mb-4">
                            <i data-lucide="sparkles"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-2">Scrub Daddies</h3>
                        <p class="text-gray-600">Tired of that one gross, ancient sponge in the kitchen? We'll provide a consistent stock of Scrub Daddies to make cleaning your dishes less of a chore. A clean sink is a happy sink.</p>
                    </div>
                    <!-- Platform Point 3 -->
                    <div class="bg-white p-8 rounded-2xl shadow-md border border-gray-100 hover:shadow-lg transition-shadow">
                        <div class="flex items-center justify-center h-12 w-12 rounded-full bg-indigo-100 text-indigo-600 mb-4">
                            <i data-lucide="cup-soda"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-2">Plastic Straws</h3>
                        <p class="text-gray-600">For those who prefer a classic drinking experience. We'll make sure there are plastic straws available for your beverages, because sometimes you just need a straw.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Our Impact Section -->
        <section id="impact" class="py-20 md:py-28 bg-white">
            <div class="w-full max-w-screen-2xl mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900">More Than Just Forks</h2>
                    <p class="text-lg text-gray-600 mt-2">Our platform has tangible benefits for health and our local economy.</p>
                </div>
                <div class="grid md:grid-cols-2 gap-12 items-center">
                    <div>
                        <h3 class="text-2xl font-bold text-indigo-600 mb-3">Health, Hygiene, and Economics</h3>
                        <p class="text-gray-700 mb-4 leading-relaxed">
                            Providing disposable plastic forks isn't just about convenience—it's about cleanliness. Communal kitchen spaces can be breeding grounds for germs, and relying on questionably-washed metal cutlery is a risk. Our plan reduces potential cross-contamination, promoting a healthier environment for everyone.
                        </p>
                        <p class="text-gray-700 leading-relaxed">
                            Furthermore, this is a targeted economic stimulus. Instead of funds disappearing into the vast DSU budget, every fork, straw, and sponge we purchase will be sourced from businesses right here in Madison, SD. We believe in giving back and stimulating our local microeconomy. It's a small investment that keeps resources within our community.
                        </p>
                    </div>
                    <div>
                        <div class="bg-gray-50 p-6 rounded-2xl shadow-lg border">
                           <h4 class="text-center font-bold text-gray-700 mb-2">Projected Local Economic Growth</h4>
                           <canvas id="economicGrowthChart"></canvas>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Events Section -->
        <section id="events" class="py-20 md:py-28">
            <div class="w-full max-w-screen-2xl mx-auto px-6">
                 <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900">Planned Events</h2>
                    <p class="text-lg text-gray-600 mt-2">Come meet us, ask questions, and share your ideas!</p>
                </div>
                <div class="max-w-3xl mx-auto bg-white rounded-2xl shadow-lg p-8 border border-gray-100">
                     <div class="relative flex space-x-4 items-center">
                        <div>
                          <span class="h-12 w-12 rounded-full bg-indigo-500 flex items-center justify-center ring-8 ring-white">
                            <i data-lucide="donut" class="h-6 w-6 text-white"></i>
                          </span>
                        </div>
                        <div class="flex-1">
                          <p class="font-bold text-xl text-gray-900">Doughnut & Discussion Party</p>
                          <p class="text-md text-gray-600">(Because doughnuts are better than cookies)</p>
                          <p class="text-sm text-gray-500 mt-1">Date & Time: To Be Announced! Stay tuned.</p>
                        </div>
                      </div>
                </div>
            </div>
        </section>

        <!-- Contact Us Section -->
        <section id="contact" class="py-20 md:py-32 bg-indigo-700 text-white">
            <div class="w-full max-w-screen-2xl mx-auto px-6 text-center">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Contact Us</h2>
                <p class="text-lg text-indigo-200 max-w-2xl mx-auto mb-8">Have questions, ideas, or just want to say hi? Reach out to us directly!</p>
                <div class="flex flex-col sm:flex-row justify-center items-center gap-8">
                    <div class="text-center">
                        <h3 class="font-bold text-xl">Jake Palmer</h3>
                        <a href="mailto:Jake.Palmer@trojans.dsu.edu" class="text-indigo-200 hover:text-white underline transition-colors">Jake.Palmer@trojans.dsu.edu</a>
                    </div>
                     <div class="text-center">
                        <h3 class="font-bold text-xl">Zander Mettler</h3>
                        <a href="mailto:Zander.Mettler@trojans.dsu.edu" class="text-indigo-200 hover:text-white underline transition-colors">Zander.Mettler@trojans.dsu.edu</a>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-gray-300">
        <div class="w-full max-w-screen-2xl mx-auto px-6 py-8 text-center">
            <p class="mb-2">&copy; 2025 Campaign for Jake Palmer & Zander Mettler</p>
            <p class="text-sm text-gray-500">Paid for by the Communal Fork Party</p>
        </div>
    </footer>

    <script>
        // Initialize Lucide Icons
        lucide.createIcons();

        // Mobile Menu Toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when a link is clicked
        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        // Economic Growth Chart
        const ctx = document.getElementById('economicGrowthChart').getContext('2d');
        const economicGrowthChart = new Chart(ctx, {
            type: 'line',
            data: {
                labels: ['Before Our Term', 'With Communal Fork Party'],
                datasets: [{
                    label: 'Local Economic Activity Index',
                    data: [100, 100.05], // Miniscule growth
                    backgroundColor: 'rgba(79, 70, 229, 0.1)',
                    borderColor: 'rgba(79, 70, 229, 1)',
                    borderWidth: 3,
                    fill: true,
                    tension: 0.4
                }]
            },
            options: {
                scales: {
                    y: {
                        beginAtZero: false,
                        ticks: {
                            display: false,
                        },
                        grid: {
                           display: false,
                           drawBorder: false,
                        }
                    },
                    x: {
                         grid: {
                           display: false,
                           drawBorder: false,
                        }
                    }
                },
                plugins: {
                    legend: {
                        display: false
                    },
                    tooltip: {
                        enabled: true,
                        callbacks: {
                            label: function(context) {
                                return ' A small, but meaningful, impact.';
                            }
                        }
                    }
                },
                maintainAspectRatio: true,
                responsive: true
            }
        });
    </script>
</body>
</html>



