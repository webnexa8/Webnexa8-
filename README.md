<!DOCTYPE html>
<html lang="en">
<head>
    <base target="_self">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Webnexa8 | Panter's Special Birthday & Social Growth</title>
    <meta name="description" content="Celebrate Panter's special birthday with Webnexa8. Expert social media growth services to grow your followers, likes, comments, views, and shares.">
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&family=Dancing+Script:wght@400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: "#FF6B8B",
                        secondary: "#4ECDC4",
                        accent: "#FFD166",
                        dark: "#1A1C2C",
                        light: "#F7F9FC"
                    },
                    fontFamily: {
                        'poppins': ['Poppins', 'sans-serif'],
                        'dancing': ['Dancing Script', 'cursive']
                    }
                }
            }
        }
    </script>
    <style>
        .gradient-bg { background: linear-gradient(135deg, #FF6B8B 0%, #FFD166 50%, #4ECDC4 100%); }
        .card-hover:hover { transform: translateY(-5px); transition: all 0.3s ease; box-shadow: 0 20px 40px rgba(0,0,0,0.1); }
        .social-growth-card { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
        #qrcode img { margin: 0 auto; border: 8px solid white; border-radius: 10px; }
    </style>
</head>
<body class="min-h-screen bg-light font-poppins">
    <header class="gradient-bg text-white sticky top-0 z-50 shadow-lg">
        <nav class="container mx-auto px-4 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <div class="w-10 h-10 bg-white rounded-full flex items-center justify-center">
                    <i class="fas fa-rocket text-primary text-xl"></i>
                </div>
                <h1 class="text-2xl font-bold">Webnexa8</h1>
            </div>
            <div class="hidden md:flex space-x-8 font-medium">
                <a href="#social-growth" class="hover:text-dark transition">Social Growth</a>
                <a href="#instagram-qr" class="hover:text-dark transition">Connect</a>
                <a href="#registration" class="hover:text-dark transition">RSVP</a>
            </div>
            <a href="https://www.instagram.com/webnexa8?igsh=OGJrMXd2N2Jhb2ll" target="_blank" class="bg-dark text-white px-6 py-2 rounded-full text-sm font-semibold hover:bg-white hover:text-dark transition">
                Follow @Webnexa8
            </a>
        </nav>
    </header>

    <section class="py-20 text-center bg-white px-4">
        <h2 class="text-5xl font-bold text-dark mb-4">Panter's Birthday <span class="text-primary font-dancing">&</span> Social Growth</h2>
        <p class="text-xl text-gray-600 max-w-2xl mx-auto mb-10">Celebrate with us and skyrocket your digital presence. Powered by Webnexa8.</p>
        <div class="flex justify-center gap-4">
            <a href="#registration" class="bg-primary text-white px-8 py-3 rounded-full font-bold shadow-lg hover:scale-105 transition">Register for Event</a>
            <a href="#social-growth" class="bg-secondary text-white px-8 py-3 rounded-full font-bold shadow-lg hover:scale-105 transition">Grow My Account</a>
        </div>
    </section>

    <section id="social-growth" class="py-16 bg-dark text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-2">Grow Your Social Media Presence</h2>
            <p class="text-gray-400 mb-12">Expert services tailored for maximum engagement</p>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                <div class="social-growth-card p-8 rounded-2xl card-hover">
                    <i class="fas fa-users text-4xl mb-4"></i>
                    <h3 class="text-xl font-bold mb-2">Followers</h3>
                    <p class="text-sm opacity-80">Organic and targeted growth for your profile.</p>
                </div>
                <div class="bg-gradient-to-r from-green-400 to-blue-500 p-8 rounded-2xl card-hover">
                    <i class="fas fa-heart text-4xl mb-4"></i>
                    <h3 class="text-xl font-bold mb-2">Engagement</h3>
                    <p class="text-sm opacity-80">Boost your likes and meaningful comments.</p>
                </div>
                <div class="bg-gradient-to-r from-purple-400 to-pink-500 p-8 rounded-2xl card-hover">
                    <i class="fas fa-eye text-4xl mb-4"></i>
                    <h3 class="text-xl font-bold mb-2">Views</h3>
                    <p class="text-sm opacity-80">Viral-ready views for Reels, Videos, and Stories.</p>
                </div>
                <div class="bg-gradient-to-r from-yellow-400 to-red-500 p-8 rounded-2xl card-hover">
                    <i class="fas fa-share-alt text-4xl mb-4"></i>
                    <h3 class="text-xl font-bold mb-2">Shares</h3>
                    <p class="text-sm opacity-80">Amplify your reach across all platforms.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="instagram-qr" class="py-16 bg-light">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold text-dark mb-4">Connect with Webnexa8</h2>
            <p class="text-gray-600 mb-8">Scan the QR code to visit our official Instagram</p>
            <div class="inline-block p-6 bg-white rounded-3xl shadow-xl">
                <div id="qrcode"></div>
                <p class="mt-4 font-bold text-primary">@webnexa8</p>
            </div>
        </div>
    </section>

    <section id="registration" class="py-16 bg-white">
        <div class="container mx-auto px-4 max-w-lg">
            <div class="bg-light p-8 rounded-3xl shadow-inner border border-gray-100">
                <h2 class="text-3xl font-bold text-center mb-8">Event RSVP</h2>
                <form class="space-y-4">
                    <input type="text" placeholder="Your Name" class="w-full p-4 rounded-xl border outline-none focus:ring-2 focus:ring-primary">
                    <input type="email" placeholder="Your Email" class="w-full p-4 rounded-xl border outline-none focus:ring-2 focus:ring-primary">
                    <select class="w-full p-4 rounded-xl border outline-none focus:ring-2 focus:ring-primary">
                        <option>Number of Guests</option>
                        <option>1</option>
                        <option>2</option>
                        <option>3+</option>
                    </select>
                    <button class="w-full bg-dark text-white py-4 rounded-xl font-bold hover:bg-primary transition">Confirm Attendance</button>
                </form>
            </div>
        </div>
    </section>

    <footer class="bg-dark text-white py-12 border-t border-gray-800">
        <div class="container mx-auto px-4 text-center">
            <h3 class="text-2xl font-bold mb-6 font-dancing text-accent">Webnexa8</h3>
            <div class="flex flex-col items-center space-y-4">
                <div class="flex items-center space-x-3">
                    <i class="fas fa-envelope text-primary"></i>
                    <a href="mailto:Webnexa8@gmail.com" class="hover:text-primary transition">Webnexa8@gmail.com</a>
                </div>
                <div class="flex space-x-6 py-4">
                    <a href="https://www.instagram.com/webnexa8?igsh=OGJrMXd2N2Jhb2ll" class="text-2xl hover:text-primary"><i class="fab fa-instagram"></i></a>
                    <a href="#" class="text-2xl hover:text-primary"><i class="fab fa-facebook"></i></a>
                    <a href="#" class="text-2xl hover:text-primary"><i class="fab fa-whatsapp"></i></a>
                </div>
                <p class="text-gray-500 text-sm">&copy; 2024 Webnexa8. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Generate QR Code for Instagram
        new QRCode(document.getElementById("qrcode"), {
            text: "https://www.instagram.com/webnexa8?igsh=OGJrMXd2N2Jhb2ll",
            width: 200,
            height: 200,
            colorDark : "#1A1C2C",
            colorLight : "#ffffff",
            correctLevel : QRCode.CorrectLevel.H
        });
    </script>
</body>
</html>
