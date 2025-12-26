<!DOCTYPE html>
<html lang="en" class="scroll-smooth">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chethan Nanjangudu</title>
    
    <meta name="description" content="Chethan Nanjangudu's professional portfolio: Graphic Designer, Video Editor, Web Developer, and AI Educator. Crafting visually stunning digital experiences.">
    <meta name="keywords" content="Chethan Nanjangudu, Graphic Designer, Video Editor, Web Developer, AI Educator, portfolio, freelance, design, web development, Tailwind CSS, Glassmorphism">
    <meta property="og:title" content="Chethan Nanjangudu - Digital Creator & AI Educator">
    <meta property="og:image" content="https://www.youtube.com/watch?v=TUJlixeJB00">
    <meta property="og:url" content="[Your Portfolio URL]">
    <meta property="og:type" content="website">

    <script src="https://cdn.tailwindcss.com"></script>
    
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap');

        :root {
            --accent: #58a6ff;
            --accent-glow: rgba(88, 166, 255, 0.4);
            --bg-dark: #0d1117;
            --bg-card: rgba(22, 27, 34, 0.7);
        }

        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: var(--bg-dark);
            color: #c9d1d9;
            scroll-behavior: smooth;
            overflow-x: hidden;
        }

        /* Animated Background Mesh */
        .mesh-bg {
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            background: radial-gradient(circle at 50% -20%, #162a4a 0%, transparent 50%),
                        radial-gradient(circle at 0% 100%, #0d1117 0%, transparent 40%);
            z-index: -1;
        }

        .section-padding { padding: 8rem 1.5rem; }

        /* Glassmorphism Refined */
        .glass-card {
            background: var(--bg-card);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.05);
            border-radius: 1.5rem;
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .glass-card:hover {
            border-color: var(--accent);
            transform: translateY(-8px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.4), 0 0 20px var(--accent-glow);
        }

        /* Gradient Text */
        .text-gradient {
            background: linear-gradient(135deg, #fff 30%, #58a6ff 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        /* Buttons */
        .btn-primary {
            background: linear-gradient(135deg, #58a6ff 0%, #1f6feb 100%);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .btn-primary:hover {
            filter: brightness(1.1);
            transform: scale(1.02);
            box-shadow: 0 0 20px var(--accent-glow);
        }

        .btn-secondary {
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: all 0.3s ease;
        }

        .btn-secondary:hover {
            background: rgba(255, 255, 255, 0.08);
            border-color: var(--accent);
        }

        /* Section Transitions */
        .section-content {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s cubic-bezier(0.16, 1, 0.3, 1);
        }
        .section-content.is-visible {
            opacity: 1;
            transform: translateY(0);
        }

        /* Custom Scrollbar */
        ::-webkit-scrollbar { width: 10px; }
        ::-webkit-scrollbar-track { background: #0d1117; }
        ::-webkit-scrollbar-thumb { background: #30363d; border-radius: 5px; }
        ::-webkit-scrollbar-thumb:hover { background: var(--accent); }

        #testimonial-slider-container {
            scrollbar-width: none;
            -ms-overflow-style: none;
        }
    </style>
</head>

<body>
    <div class="mesh-bg"></div>

    <header class="fixed top-0 w-full z-50 border-b border-white/5 bg-black/40 backdrop-blur-xl">
        <nav class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#home" class="text-white text-xl font-bold tracking-tighter">
                Chethan<span class="text-[#58a6ff]"> </span>Nanjangudu
            </a>
            
            <div class="hidden md:flex space-x-8 items-center text-sm font-medium uppercase tracking-widest text-gray-400">
                <a href="#home" class="hover:text-white transition-colors">Home</a>
                <a href="#about" class="hover:text-white transition-colors">About</a>
                <a href="#skills" class="hover:text-white transition-colors">Skills</a>
                <a href="#portfolio" class="hover:text-white transition-colors">Work</a>
                <a href="#contact" class="hover:text-white transition-colors">Contact</a>
            </div>

                     <div class="flex items-center space-x-5">
    <a href="[Your GitHub URL]" target="_blank" class="text-gray-400 hover:text-white transition-transform hover:scale-110">
        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.6.11.819-.26.819-.578 0-.28-.01-1.015-.015-1.998-3.334.722-4.04-1.603-4.04-1.603-.546-1.385-1.332-1.755-1.332-1.755-1.085-.745.08-.73.08-.73 1.202.085 1.838 1.237 1.838 1.237 1.066 1.83 2.808 1.3 3.493.996.108-.775.419-1.3.76-1.605-2.665-.3-5.465-1.334-5.465-5.932 0-1.31.467-2.38 1.235-3.218-.124-.302-.535-1.517.117-3.179 0 0 1.008-.323 3.301 1.23.957-.266 1.983-.4 3.003-.404 1.02.004 2.046.138 3.006.404 2.29-1.553 3.3-1.23 3.3-1.23.652 1.662.241 2.877.118 3.179.77.838 1.233 1.908 1.233 3.218 0 4.61-2.8 5.626-5.474 5.923.43.37.814 1.12.814 2.256 0 1.605-.015 2.898-.015 3.286 0 .322.217.693.824.577C20.56 21.794 24 17.302 24 12 24 5.373 18.627 0 12 0z"/></svg>
    </a>
    <a href="https://in.linkedin.com/in/chethan-nanjangudu-57a67925b" target="_blank" class="text-gray-400 hover:text-[#58a6ff] transition-transform hover:scale-110">
        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.529-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
    </a>
    <a href="https://www.instagram.com/chethann.og/" target="_blank" class="text-gray-400 hover:text-[#E4405F] transition-transform hover:scale-110">
        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/>
        </svg>
    </a>
</div>
        </nav>
    </header>

    <main>
        <section id="home" class="min-h-screen flex items-center justify-center relative overflow-hidden">
            <div class="max-w-5xl mx-auto px-6 text-center section-content">
                <span class="inline-block py-1 px-3 rounded-full bg-blue-500/10 border border-blue-500/20 text-blue-400 text-xs font-bold uppercase tracking-widest mb-6">Available for Projects</span>
                <h1 class="text-5xl md:text-8xl font-extrabold mb-8 tracking-tighter leading-none">
                    <span class="text-white">Hello, I'm</span><br/>
                    <span class="text-gradient">Chethan Nanjangudu</span>
                </h1>
                <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed">
                    I craft creative visuals, video editings, and strong brand identities. Passionate about design, technology, and teaching AI to the next generation.
                </p>
       
        </section>

        <section id="about" class="section-padding relative">
            <div class="max-w-7xl mx-auto px-6 section-content">
                <div class="grid lg:grid-cols-2 gap-16 items-center">
                    <div class="relative group">
                        <div class="absolute -inset-1 bg-gradient-to-r from-[#58a6ff] to-blue-900 rounded-2xl blur opacity-25 group-hover:opacity-50 transition duration-1000"></div>
                        <img src="about.png" alt="Chethan Nanjangudu" class="relative rounded-2xl grayscale hover:grayscale-0 transition duration-500 shadow-2xl bg-gray-900">
                    </div>
                    <div>
                        <h2 class="text-4xl font-bold mb-8 text-white">About Me</h2>
                        <p class="text-gray-400 text-lg leading-relaxed mb-8">
                            I’m a 16-year-old professional Graphic Designer, Video Editor, and Web Developer with a strong passion for creativity and technology. 
                            I specialize in illustrations, logo design, branding, and website development, combining artistic vision with modern digital tools to bring ideas to life.
                        </p>
                        <p class="text-gray-400 text-lg leading-relaxed mb-10">
                            Alongside my design and development work, I also teach Artificial Intelligence, helping others explore the limitless possibilities of AI in creative and technical fields.
                        </p>
                        <a href="#contact" class="inline-flex items-center text-[#58a6ff] font-bold hover:underline">
                            Get In Touch 
                            <svg class="w-5 h-5 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <section id="skills" class="section-padding">
            <div class="max-w-7xl mx-auto px-6 section-content text-center">
                <h2 class="text-4xl font-bold mb-16 text-white">My Expertise</h2>
                <div class="flex flex-wrap justify-center gap-4 max-w-4xl mx-auto">
                    <span class="px-6 py-3 glass-card text-gray-300 font-medium">Graphic Design</span>
                    <span class="px-6 py-3 glass-card text-gray-300 font-medium">Video Editing</span>
                    <span class="px-6 py-3 glass-card text-gray-300 font-medium">Branding & Logo Design</span>
                    <span class="px-6 py-3 glass-card text-gray-300 font-medium">Web Development</span>
                    <span class="px-6 py-3 glass-card text-gray-300 font-medium">AI Education</span>
                    <span class="px-6 py-3 glass-card text-gray-300 font-medium">Illustrator</span>
                    <span class="px-6 py-3 glass-card text-gray-300 font-medium">HTML / CSS / JS</span>
                </div>
            </div>
        </section>

        <section class="py-20 bg-blue-600/5">
            <div class="max-w-7xl mx-auto px-6 section-content">
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-8">
                    <div class="text-center">
                        <div class="text-5xl font-extrabold text-[#58a6ff] mb-2" data-count-target="100">0</div>
                        <div class="text-gray-500 uppercase tracking-widest text-xs font-bold">Projects Done</div>
                    </div>
                    <div class="text-center">
                        <div class="text-5xl font-extrabold text-[#58a6ff] mb-2" data-count-target="28">0</div>
                        <div class="text-gray-500 uppercase tracking-widest text-xs font-bold">Happy Clients</div>
                    </div>
                    <div class="text-center">
                        <div class="text-5xl font-extrabold text-[#58a6ff] mb-2" data-count-target="5">0</div>
                        <div class="text-gray-500 uppercase tracking-widest text-xs font-bold">Years Exp</div>
                    </div>
                    <div class="text-center">
                        <div class="text-5xl font-extrabold text-[#58a6ff] mb-2" data-count-target="6">0</div>
                        <div class="text-gray-500 uppercase tracking-widest text-xs font-bold">Commerical Clients</div>
                    </div>
                </div>
            </div>
        </section>

        <section id="services" class="section-padding">
            <div class="max-w-7xl mx-auto px-6 section-content">
                <h2 class="text-4xl font-bold mb-16 text-center text-white">What I Offer</h2>
                <div class="grid md:grid-cols-3 gap-8">
                    <div class="p-10 glass-card">
                        <div class="w-12 h-12 bg-[#58a6ff]/10 rounded-xl flex items-center justify-center text-[#58a6ff] mb-6">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1v-3M13 10V4.5a2.5 2.5 0 00-5 0V10M17 14h2a2 2 0 002-2v-2a2 2 0 00-2-2h-2M7 14h-2a2 2 0 01-2-2v-2a2 2 0 012-2h2"></path></svg>
                        </div>
                        <h3 class="text-xl font-bold text-white mb-4">E-Service</h3>
                        <p class="text-gray-400 leading-relaxed">Delivering quality E-Services that bring your ideas to life.</p>
                    </div>

                    <div class="p-10 glass-card">
                        <div class="w-12 h-12 bg-[#58a6ff]/10 rounded-xl flex items-center justify-center text-[#58a6ff] mb-6">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 9l3 3-3 3m5 0h-2m4-10H5a2 2 0 00-2 2v10a2 2 0 002 2h14a2 2 0 002-2V5a2 2 0 00-2-2z"></path></svg>
                        </div>
                        <h3 class="text-xl font-bold text-white mb-4">Develop Illustrations & Websites</h3>
                        <p class="text-gray-400 leading-relaxed">Crafting stunning Illustrations and professional Websites with a creative touch.</p>
                    </div>

                    <div class="p-10 glass-card">
                        <div class="w-12 h-12 bg-[#58a6ff]/10 rounded-xl flex items-center justify-center text-[#58a6ff] mb-6">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V4L8 4.5M4 7v10c0 2.2 3.5 4 8 4s8-1.7 8-4V7"></path></svg>
                        </div>
                        <h3 class="text-xl font-bold text-white mb-4">Mastercourses</h3>
                        <p class="text-gray-400 leading-relaxed">I teach Graphic Designing, Video Editing, and AI Mastercourses to help learners turn creativity into professional skills.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="portfolio" class="section-padding bg-black/20">
            <div class="max-w-7xl mx-auto px-6 section-content">
                <div class="flex justify-between items-end mb-16">
                    <h2 class="text-4xl font-bold text-white">Featured Work</h2>
                    <a href="#" class="text-[#58a6ff] font-bold hidden md:block">View All Projects &rarr;</a>
                </div>
                
                <div class="grid md:grid-cols-3 gap-8">
                    <div class="group glass-card overflow-hidden">
                        <div class="overflow-hidden">
                            <img src="https://placehold.co/600x400/161b22/79c0ff?text=Project+A" alt="Project A" class="w-full h-56 object-cover transition duration-500 group-hover:scale-110 grayscale group-hover:grayscale-0">
                        </div>
                        <div class="p-8">
                            <h3 class="text-xl font-bold text-white mb-3">E-Commerce Platform</h3>
                            <p class="text-gray-400 mb-6 text-sm">A scalable shopping solution built with React and Firestore for real-time inventory management.</p>
                            <a href="#" class="inline-block py-3 px-6 rounded-xl bg-white/5 border border-white/10 text-white text-xs font-bold uppercase hover:bg-[#58a6ff] transition-colors">Case Study</a>
                        </div>
                    </div>

                    <div class="group glass-card overflow-hidden">
                        <div class="overflow-hidden">
                            <img src="https://placehold.co/600x400/161b22/58a6ff?text=Project+B" alt="Project B" class="w-full h-56 object-cover transition duration-500 group-hover:scale-110 grayscale group-hover:grayscale-0">
                        </div>
                        <div class="p-8">
                            <h3 class="text-xl font-bold text-white mb-3">Data Visualization Dashboard</h3>
                            <p class="text-gray-400 mb-6 text-sm">Interactive dashboard using D3.js to display complex financial data simply.</p>
                            <a href="#" class="inline-block py-3 px-6 rounded-xl bg-white/5 border border-white/10 text-white text-xs font-bold uppercase hover:bg-[#58a6ff] transition-colors">Case Study</a>
                        </div>
                    </div>

                    <div class="group glass-card overflow-hidden">
                        <div class="overflow-hidden">
                            <img src="https://placehold.co/600x400/161b22/c9d1d9?text=Project+C" alt="Project C" class="w-full h-56 object-cover transition duration-500 group-hover:scale-110 grayscale group-hover:grayscale-0">
                        </div>
                        <div class="p-8">
                            <h3 class="text-xl font-bold text-white mb-3">Mobile PWA</h3>
                            <p class="text-gray-400 mb-6 text-sm">A Progressive Web App for fitness tracking, offering offline capability.</p>
                            <a href="#" class="inline-block py-3 px-6 rounded-xl bg-white/5 border border-white/10 text-white text-xs font-bold uppercase hover:bg-[#58a6ff] transition-colors">Case Study</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="testimonials" class="section-padding">
            <div class="max-w-7xl mx-auto px-6 section-content">
                <h2 class="text-4xl font-bold mb-16 text-center text-white">What Clients Say</h2>
                <div class="relative">
                    <div id="testimonial-slider-container" class="flex overflow-x-auto snap-x snap-mandatory gap-6 pb-10">
                        <div class="testimonial-card flex-shrink-0 w-full md:w-[calc(33.333%-16px)] snap-center p-8 glass-card">
                            <div class="flex text-[#58a6ff] mb-4">★★★★★</div>
                            <p class="text-gray-300 italic mb-6">"The level of detail and responsiveness was outstanding. The project was delivered ahead of schedule."</p>
                            <div class="text-white font-bold">Jamie K.</div>
                            <div class="text-xs text-[#58a6ff] uppercase font-bold tracking-widest">Tech Startup Founder</div>
                        </div>
                        <div class="testimonial-card flex-shrink-0 w-full md:w-[calc(33.333%-16px)] snap-center p-8 glass-card">
                            <div class="flex text-[#58a6ff] mb-4">★★★★★</div>
                            <p class="text-gray-300 italic mb-6">"Our new site is faster and much more user-friendly. Smooth collaboration from start to finish."</p>
                            <div class="text-white font-bold">Devin M.</div>
                            <div class="text-xs text-[#58a6ff] uppercase font-bold tracking-widest">Non-Profit Director</div>
                        </div>
                        <div class="testimonial-card flex-shrink-0 w-full md:w-[calc(33.333%-16px)] snap-center p-8 glass-card">
                            <div class="flex text-[#58a6ff] mb-4">★★★★★</div>
                            <p class="text-gray-300 italic mb-6">"Innovative solutions and clean code! The professional you want on your team for web tasks."</p>
                            <div class="text-white font-bold">Alex C.</div>
                            <div class="text-xs text-[#58a6ff] uppercase font-bold tracking-widest">Senior Product Manager</div>
                        </div>
                    </div>
                    
                    <div class="flex justify-center space-x-4 mt-8">
                        <button id="prev-testimonial" class="p-4 rounded-full glass-card hover:bg-[#58a6ff] text-white">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M15 19l-7-7 7-7"></path></svg>
                        </button>
                        <button id="next-testimonial" class="p-4 rounded-full glass-card hover:bg-[#58a6ff] text-white">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M9 5l7 7-7 7"></path></svg>
                        </button>
                    </div>
                </div>
            </div>
        </section>

        <section id="contact" class="section-padding relative">
            
    <div class="max-w-4xl mx-auto px-6 section-content">
        <div class="text-center mb-16">
            <h2 class="text-4xl font-bold text-white mb-4">Get in Touch</h2>
            <p class="text-gray-400">Have a project in mind? I typically respond within 24 hours.</p>
        </div>
        
        <div class="glass-card p-10">
            <form action="https://formsubmit.co/chethan.nanjangudu@gmail.com" method="POST" class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="space-y-2">
                    <label class="text-xs font-bold uppercase text-gray-500 ml-1">Name</label>
                    <input type="text" name="name" placeholder="Your Name" required class="w-full p-4 rounded-xl bg-white/5 border border-white/10 focus:border-[#58a6ff] outline-none text-white transition-all">
                </div>
                <div class="space-y-2">
                    <label class="text-xs font-bold uppercase text-gray-500 ml-1">Email</label>
                    <input type="email" name="email" placeholder="you@example.com" required class="w-full p-4 rounded-xl bg-white/5 border border-white/10 focus:border-[#58a6ff] outline-none text-white transition-all">
                </div>
                <div class="md:col-span-2 space-y-2">
                    <label class="text-xs font-bold uppercase text-gray-500 ml-1">Message</label>
                    <textarea name="message" rows="5" placeholder="How can I help you?" required class="w-full p-4 rounded-xl bg-white/5 border border-white/10 focus:border-[#58a6ff] outline-none text-white transition-all"></textarea>
                </div>
                <div class="md:col-span-2">
                    <button type="submit" class="w-full py-4 btn-primary text-white font-bold rounded-xl shadow-lg">
                        Send Message
                    </button>
                </div>
            </form>
        </div>
    </div>
</section>
                

    <footer class="py-12 border-t border-white/5 text-center">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-white font-bold mb-4 tracking-widest text-sm">CHETHAN NANJANGUDU</div>
            <div class="text-gray-500 text-sm">
                &copy; <span id="current-year">2025</span> CheLite Corporation Pvt. Ltd.
                <br/>All rights reserved.
            </div>
        </div>
    </footer>

    <script>
        // Copy Year Logic
        document.getElementById('current-year').textContent = new Date().getFullYear();

        // Counters
        const counterObserver = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    const target = parseInt(entry.target.getAttribute('data-count-target'));
                    let count = 0;
                    const speed = target / 50;
                    const timer = setInterval(() => {
                        count += speed;
                        if (count >= target) {
                            entry.target.innerText = target;
                            clearInterval(timer);
                        } else {
                            entry.target.innerText = Math.floor(count);
                        }
                    }, 30);
                    counterObserver.unobserve(entry.target);
                }
            });
        }, { threshold: 0.5 });

        document.querySelectorAll('[data-count-target]').forEach(el => counterObserver.observe(el));

        // Section Observer for Reveal effect
        const sectionObserver = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) entry.target.classList.add('is-visible');
            });
        }, { threshold: 0.1 });

        document.querySelectorAll('.section-content').forEach(el => sectionObserver.observe(el));

        // Slider Logic
        const slider = document.getElementById('testimonial-slider-container');
        document.getElementById('next-testimonial').addEventListener('click', () => {
            slider.scrollBy({ left: 350, behavior: 'smooth' });
        });
        document.getElementById('prev-testimonial').addEventListener('click', () => {
            slider.scrollBy({ left: -350, behavior: 'smooth' });
        });
    </script>
</body>
</html>
