<!DOCTYPE HTML> 
<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
    content="width=device-width, initial-scale=1.0">
    <title> Vũ Tiến Vinh - CV Cá nhân </title>

    <!--Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Cấu hình Tailwind CSS -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        inter: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        primary: '#1e3a8a', / / Màu xanh đậm
                        secondary: '#3b82f6', / / Màu xanh nhạt
                        dark: '#0f172a', / / Màu nền tối
                        light: '#f8fafc', / / Màu nền sáng
                    }
                }
            }
        }
    </script>

    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* Màu nền sáng */
        }
        .glass-nav {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
        }
        section {
            scroll-margin-top: 5rem;
        }
    </style>
</head>
<body class="text-gray-800 antialiased
selection:bg-primary selection:text-white">

    <!-- Navbar -->
    <nav class="glass-nav fixed w-full z-50 top-0 border-b border-gray-200 shadow-sm transition all duration-300">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20 items-center">
                <!-- Logo -->  
                <div class="flex-shrink-0 flex items-center">
                    <a href="#" class="font-bold text-2xl text-primary tracking-tight">Vũ Tiến Vinh</a>
                </div>

                <!-- Menu Desktop-->
                <div class="hidden md:flex space-x-8">
                    <a href="#about" class="text-gray-600 hover:text-primary font-medium transition-colors">Tóm tắt</a>
                    <a href="#education" class="text-gray-600 hover:text-primary font-medium transition-colors">Học vấn</a>
                    <a href="#projects" class="text-gray-600 hover:text-primary font-medium transition-colors">Kinh nghiệm</a>
                    <a href="#skills" class="text-gray-600 hover:text-primary font-medium transition-colors">Kỹ năng</a>
                    <a href="#contact" class="text-gray-600 hover:text-primary font-medium transition-colors">Liên hệ</a>
                </div>

                <!-- Nút Hamberger cho Mobile-->
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-button" class="text-gray-600 hover:text-primary focus:outline-none text-2xl">
                        <i class="fa-solid fa-bars"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-b border-gray-200 absolute w-full ">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#about" class="text-gray-600 hover:text-primary font-medium transition-colors">Tóm tắt</a>
                <a href="#education" class="text-gray-600 hover:text-primary font-medium transition-colors">Học vấn</a>
                <a href="#projects" class="text-gray-600 hover:text-primary font-medium transition-colors">Kinh nghiệm</a>
                <a href="#skills" class="text-gray-600 hover:text-primary font-medium transition-colors">Kỹ năng</a>
                <a href="#contact" class="text-gray-600 hover:text-primary font-medium transition-colors">Liên hệ</a>
            </div>
        </div>
    </nav>

    <!-- Sections -->
    <section id="about" class="min-h-screen flex items-center justify-center bg-light">
        <h1 class="text-4xl font-bold text-primary">Giới thiệu về tôi</h1>
    </section>

    <section id="skills" class="min-h-screen flex items-center justify-center bg-secondary">
        <h1 class="text-4xl font-bold text-light">Kỹ năng của tôi</h1>
    </section>

    <section id="projects" class="min-h-screen flex items-center justify-center bg-light">
        <h1 class="text-4xl font-bold text-primary">Các dự án của tôi</h1>
    </section>

    <section id="contact" class="min-h-screen flex items-center justify-center bg-secondary">
        <h1 class="text-4xl font-bold text-light">Liên hệ với tôi</h1>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-light py-6">

</html>
