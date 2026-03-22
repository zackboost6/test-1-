<!DOCTYPE html>
<html lang="pt-br" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jardim dos Sonhos | Serviços Profissionais de Jardinagem</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Poppins:wght@300;400;500;600&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
        }
        
        h1, h2, h3 {
            font-family: 'Playfair+Display', serif;
        }
        
        .hero-bg {
            background-image: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1585320806297-9794b3e4eeae?ixlib=rb-1.2.1&auto=format&fit=crop&w=1950&q=80');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body class="bg-stone-50 text-stone-800">

    <!-- Navbar -->
    <nav class="fixed w-full z-50 bg-white/90 backdrop-blur-sm shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20 items-center">
                <div class="flex items-center space-x-2">
                    <i class="fas fa-leaf text-green-600 text-3xl"></i>
                    <span class="text-2xl font-bold text-stone-900 tracking-tight">Jardim <span class="text-green-600">Sonhos</span></span>
                </div>
                <div class="hidden md:flex space-x-8 items-center">
                    <a href="#home" class="hover:text-green-600 transition-colors font-medium">Início</a>
                    <a href="#servicos" class="hover:text-green-600 transition-colors font-medium">Serviços</a>
                    <a href="#galeria" class="hover:text-green-600 transition-colors font-medium">Galeria</a>
                    <a href="#contato" class="bg-green-600 text-white px-6 py-2 rounded-full hover:bg-green-700 transition-all shadow-md">Fale Conosco</a>
                </div>
                <div class="md:hidden">
                    <button id="mobile-menu-button" class="text-stone-600 focus:outline-none">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t border-stone-100 p-4 space-y-4">
            <a href="#home" class="block py-2 text-stone-800 hover:text-green-600">Início</a>
            <a href="#servicos" class="block py-2 text-stone-800 hover:text-green-600">Serviços</a>
            <a href="#galeria" class="block py-2 text-stone-800 hover:text-green-600">Galeria</a>
            <a href="#contato" class="block py-2 text-green-600 font-bold">Fale Conosco</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-bg h-screen flex items-center justify-center text-center text-white pt-20">
        <div class="max-w-4xl px-4">
            <span class="inline-block px-4 py-1 bg-green-600/30 rounded-full mb-4 backdrop-blur-sm text-sm font-semibold tracking-wider uppercase">Natureza em sua casa</span>
            <h1 class="text-5xl md:text-7xl font-bold mb-6 leading-tight">Transforme seu jardim em um paraíso</h1>
            <p class="text-lg md:text-xl mb-10 text-stone-100 max-w-2xl mx-auto leading-relaxed">Design de paisagismo profissional, manutenção e cuidados especializados para o seu espaço verde.</p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <a href="#servicos" class="bg-green-600 text-white px-8 py-4 rounded-full text-lg font-semibold hover:bg-green-700 transition-all shadow-xl flex items-center justify-center gap-2">
                    Nossos Serviços <i class="fas fa-arrow-right text-sm"></i>
                </a>
                <a href="#contato" class="bg-white/10 backdrop-blur-md border border-white/20 text-white px-8 py-4 rounded-full text-lg font-semibold hover:bg-white/20 transition-all flex items-center justify-center">
                    Ver Portfólio
                </a>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="servicos" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl md:text-5xl font-bold text-stone-900 mb-4">O que fazemos por você</h2>
                <div class="w-24 h-1 bg-green-600 mx-auto rounded-full mb-6"></div>
                <p class="text-stone-500 max-w-2xl mx-auto">Oferecemos uma gama completa de serviços de jardinagem para manter seu espaço sempre vibrante e saudável.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="group p-8 rounded-2xl bg-stone-50 hover:bg-green-50 transition-all duration-300 border border-stone-100 hover:border-green-200">
                    <div class="w-16 h-16 bg-green-100 text-green-600 rounded-2xl flex items-center justify-center mb-6 group-hover:bg-green-600 group-hover:text-white transition-all">
                        <i class="fas fa-tree text-2xl"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4 text-stone-900">Paisagismo</h3>
                    <p class="text-stone-500 leading-relaxed">Criação de projetos únicos que harmonizam plantas, pedras e elementos decorativos para o seu espaço.</p>
                </div>
                
                <!-- Service 2 -->
                <div class="group p-8 rounded-2xl bg-stone-50 hover:bg-green-50 transition-all duration-300 border border-stone-100 hover:border-green-200">
                    <div class="w-16 h-16 bg-green-100 text-green-600 rounded-2xl flex items-center justify-center mb-6 group-hover:bg-green-600 group-hover:text-white transition-all">
                        <i class="fas fa-scissors text-2xl"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4 text-stone-900">Manutenção</h3>
                    <p class="text-stone-500 leading-relaxed">Poda, adubação e controle de pragas regular para garantir que seu jardim cresça saudável o ano todo.</p>
                </div>
                
                <!-- Service 3 -->
                <div class="group p-8 rounded-2xl bg-stone-50 hover:bg-green-50 transition-all duration-300 border border-stone-100 hover:border-green-200">
                    <div class="w-16 h-16 bg-green-100 text-green-600 rounded-2xl flex items-center justify-center mb-6 group-hover:bg-green-600 group-hover:text-white transition-all">
                        <i class="fas fa-tint text-2xl"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4 text-stone-900">Irrigação</h3>
                    <p class="text-stone-500 leading-relaxed">Instalação e manutenção de sistemas de irrigação automatizados para maior praticidade e economia.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="galeria" class="py-24 bg-stone-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row justify-between items-end mb-12 gap-6">
                <div>
                    <h2 class="text-4xl md:text-5xl font-bold text-stone-900 mb-4">Nossa Galeria</h2>
                    <p class="text-stone-500">Inspire-se com alguns dos nossos projetos recentes.</p>
                </div>
                <a href="#" class="text-green-600 font-bold hover:underline flex items-center gap-2">Ver tudo no Instagram <i class="fab fa-instagram"></i></a>
            </div>
            
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                <div class="aspect-square rounded-2xl overflow-hidden shadow-lg group">
                    <img src="https://images.unsplash.com/photo-1558905734-b83298a23056?ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=80" alt="Projeto 1" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                </div>
                <div class="aspect-square rounded-2xl overflow-hidden shadow-lg group">
                    <img src="https://images.unsplash.com/photo-1592150621344-82454a652028?ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=80" alt="Projeto 2" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                </div>
                <div class="aspect-square rounded-2xl overflow-hidden shadow-lg group">
                    <img src="https://images.unsplash.com/photo-1598902108854-10e335adac99?ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=80" alt="Projeto 3" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                </div>
                <div class="aspect-square rounded-2xl overflow-hidden shadow-lg group">
                    <img src="https://images.unsplash.com/photo-1416870213417-194e9292751e?ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=80" alt="Projeto 4" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contato" class="py-24 bg-white overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-green-900 rounded-[3rem] p-12 md:p-20 relative overflow-hidden shadow-2xl">
                <!-- Background decoration -->
                <div class="absolute -right-20 -bottom-20 w-80 h-80 bg-green-800 rounded-full opacity-50 blur-3xl"></div>
                <div class="absolute -left-20 -top-20 w-80 h-80 bg-green-700 rounded-full opacity-30 blur-3xl"></div>
                
                <div class="relative z-10 grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
                    <div>
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-8 leading-tight">Vamos criar algo verde juntos?</h2>
                        <div class="space-y-6">
                            <div class="flex items-center gap-4 text-stone-200">
                                <div class="w-12 h-12 bg-white/10 rounded-full flex items-center justify-center">
                                    <i class="fas fa-phone"></i>
                                </div>
                                <div>
                                    <p class="text-sm opacity-60">Ligue para nós</p>
                                    <p class="text-lg font-semibold">(11) 99999-9999</p>
                                </div>
                            </div>
                            <div class="flex items-center gap-4 text-stone-200">
                                <div class="w-12 h-12 bg-white/10 rounded-full flex items-center justify-center">
                                    <i class="fas fa-envelope"></i>
                                </div>
                                <div>
                                    <p class="text-sm opacity-60">Mande um e-mail</p>
                                    <p class="text-lg font-semibold">contato@jardimsonhos.com.br</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <form class="bg-white p-8 rounded-3xl shadow-xl space-y-4">
                        <div>
                            <label class="block text-sm font-medium text-stone-700 mb-1">Seu Nome</label>
                            <input type="text" placeholder="Como podemos te chamar?" class="w-full px-4 py-3 rounded-xl border border-stone-200 focus:outline-none focus:ring-2 focus:ring-green-500">
                        </div>
                        <div>
                            <label class="block text-sm font-medium text-stone-700 mb-1">WhatsApp</label>
                            <input type="tel" placeholder="(00) 00000-0000" class="w-full px-4 py-3 rounded-xl border border-stone-200 focus:outline-none focus:ring-2 focus:ring-green-500">
                        </div>
                        <div>
                            <label class="block text-sm font-medium text-stone-700 mb-1">Mensagem</label>
                            <textarea rows="4" placeholder="Conte-nos sobre o seu projeto..." class="w-full px-4 py-3 rounded-xl border border-stone-200 focus:outline-none focus:ring-2 focus:ring-green-500"></textarea>
                        </div>
                        <button type="submit" class="w-full bg-green-600 text-white font-bold py-4 rounded-xl hover:bg-green-700 transition-colors shadow-lg shadow-green-200">
                            Enviar Mensagem
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-12 bg-stone-900 text-white">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <div class="flex items-center justify-center space-x-2 mb-8">
                <i class="fas fa-leaf text-green-500 text-2xl"></i>
                <span class="text-xl font-bold tracking-tight">Jardim <span class="text-green-500">Sonhos</span></span>
            </div>
            <div class="flex justify-center space-x-6 mb-8">
                <a href="#" class="text-stone-400 hover:text-white transition-colors text-2xl"><i class="fab fa-facebook"></i></a>
                <a href="#" class="text-stone-400 hover:text-white transition-colors text-2xl"><i class="fab fa-instagram"></i></a>
                <a href="#" class="text-stone-400 hover:text-white transition-colors text-2xl"><i class="fab fa-whatsapp"></i></a>
            </div>
            <p class="text-stone-500">&copy; 2026 Jardim Sonhos. Todos os direitos reservados.</p>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when clicking a link
        const mobileLinks = mobileMenu.querySelectorAll('a');
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>
