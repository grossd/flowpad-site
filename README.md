<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Enterprise Sales Enablement Platform</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    backgroundImage: {
                        'gradient-custom': 'linear-gradient(to right, #1e40af, #6b21a8)',
                    }
                }
            }
        }
    </script>
    <style>
        .hover-lift {
            transition: transform 0.3s ease;
        }
        .hover-lift:hover {
            transform: translateY(-10px);
        }
    </style>
</head>
<body class="bg-gray-50 font-sans">
    <!-- Header / Hero Section -->
    <header class="bg-gradient-custom text-white py-20">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-5xl font-bold mb-6">
                Elevate Your Enterprise Sales Performance
            </h1>
            <p class="text-xl mb-10 max-w-2xl mx-auto">
                A comprehensive sales enablement platform designed to transform your sales team's productivity, insights, and results.
            </p>
            <div class="space-x-4">
                <a href="#demo" class="inline-block bg-white text-blue-800 px-6 py-3 rounded-lg font-bold hover:bg-gray-100 transition">
                    Request Demo
                </a>
                <a href="#features" class="inline-block border-2 border-white text-white px-6 py-3 rounded-lg font-bold hover:bg-white/10 transition">
                    Learn More
                </a>
            </div>
        </div>
    </header>

    <!-- Features Section -->
    <section id="features" class="container mx-auto py-20 px-4">
        <div class="text-center mb-16">
            <h2 class="text-4xl font-bold mb-4">
                Powerful Features for Modern Sales Teams
            </h2>
            <p class="text-xl text-gray-600 max-w-2xl mx-auto">
                Our platform is engineered to provide enterprise sales teams with the tools they need to succeed in today's competitive market.
            </p>
        </div>

        <div class="grid md:grid-cols-2 gap-8">
            <div class="bg-white p-6 rounded-lg shadow hover-lift">
                <div class="flex items-center space-x-6">
                    <i class="fas fa-chart-bar text-blue-600 text-5xl"></i>
                    <div>
                        <h3 class="text-2xl font-semibold mb-2">Advanced Analytics</h3>
                        <p class="text-gray-600">
                            Gain deep insights into sales performance with AI-powered analytics that track every stage of the sales process.
                        </p>
                    </div>
                </div>
            </div>

            <div class="bg-white p-6 rounded-lg shadow hover-lift">
                <div class="flex items-center space-x-6">
                    <i class="fas fa-users text-green-600 text-5xl"></i>
                    <div>
                        <h3 class="text-2xl font-semibold mb-2">Team Collaboration</h3>
                        <p class="text-gray-600">
                            Streamline communication and knowledge sharing across your entire sales organization with integrated collaboration tools.
                        </p>
                    </div>
                </div>
            </div>

            <div class="bg-white p-6 rounded-lg shadow hover-lift">
                <div class="flex items-center space-x-6">
                    <i class="fas fa-shield-alt text-purple-600 text-5xl"></i>
                    <div>
                        <h3 class="text-2xl font-semibold mb-2">Enterprise-Grade Security</h3>
                        <p class="text-gray-600">
                            Protect sensitive sales data with robust security measures and comprehensive compliance features.
                        </p>
                    </div>
                </div>
            </div>

            <div class="bg-white p-6 rounded-lg shadow hover-lift">
                <div class="flex items-center space-x-6">
                    <i class="fas fa-bolt text-yellow-600 text-5xl"></i>
                    <div>
                        <h3 class="text-2xl font-semibold mb-2">AI-Powered Insights</h3>
                        <p class="text-gray-600">
                            Leverage artificial intelligence to predict sales trends, identify opportunities, and optimize sales strategies.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="bg-gray-100 py-20">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-4xl font-bold mb-12">Trusted by Industry Leaders</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-lg shadow hover-lift">
                    <p class="italic mb-4">"Transformed our sales strategy and increased revenue by 40%."</p>
                    <p class="font-semibold text-gray-700">- Global Tech Inc.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow hover-lift">
                    <p class="italic mb-4">"The most comprehensive sales enablement tool we've ever used."</p>
                    <p class="font-semibold text-gray-700">- Enterprise Solutions LLC</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow hover-lift">
                    <p class="italic mb-4">"AI insights have been game-changing for our sales approach."</p>
                    <p class="font-semibold text-gray-700">- International Consulting Group</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action -->
    <section class="bg-gradient-custom text-white py-20">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-4xl font-bold mb-6">
                Ready to Revolutionize Your Sales Performance?
            </h2>
            <p class="text-xl mb-10 max-w-2xl mx-auto">
                Schedule a personalized demo and see how our enterprise sales enablement platform can transform your team.
            </p>
            <a href="#demo" class="inline-block bg-white text-blue-800 px-8 py-4 rounded-lg font-bold hover:bg-gray-100 transition text-xl">
                Book a Demo
            </a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-4 text-center">
            <p>&copy; 2024 Enterprise Sales Enablement Platform. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
