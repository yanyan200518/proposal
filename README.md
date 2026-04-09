<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Refugee Archive | Oral Histories</title>
    
    <!-- Google Fonts: Playfair Display (for elegant serif) & Inter (fallback for Helvetica Neue) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=EB+Garamond:ital,wght@0,400;0,500;0,600;1,400&family=Inter:wght@300;400;500;600&family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;1,400&display=swap" rel="stylesheet">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Tailwind Configuration -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'brand-red': '#972D2D',
                        'brand-beige': '#F2EEE3',
                        'brand-black': '#000000',
                        'brand-white': '#FBFBFB'
                    },
                    fontFamily: {
                        'serif': ['"Playfair Display"', 'Georgia', 'serif'],
                        'garamond': ['"EB Garamond"', 'Georgia', 'serif'],
                        'sans': ['"Helvetica Neue"', 'Inter', 'system-ui', 'sans-serif']
                    },
                    backgroundImage: {
                        'gradient-dark': 'linear-gradient(to bottom, #111111, #000000)'
                    }
                }
            }
        }
    </script>

    <style>
        /* Base typography settings */
        body {
            background-color: #FBFBFB;
            color: #000000;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
        }

        /* Smooth Reveal Animations */
        .reveal {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s cubic-bezier(0.5, 0, 0, 1);
        }
        
        .reveal.active {
            opacity: 1;
            transform: translateY(0);
        }

        .reveal-delay-1 { transition-delay: 0.2s; }
        .reveal-delay-2 { transition-delay: 0.4s; }
        .reveal-delay-3 { transition-delay: 0.6s; }

        /* Documentary Vignette Effect */
        .vignette-overlay {
            background: radial-gradient(circle, rgba(0,0,0,0) 40%, rgba(0,0,0,0.6) 100%);
            box-shadow: inset 0 0 100px rgba(0,0,0,0.8);
        }

        /* Clean borders for structural elements only */
        .minimal-separator {
            height: 1px;
            background-color: rgba(0,0,0,0.1);
            width: 100%;
            margin: 2rem 0;
        }
        
        .dark-separator {
            height: 1px;
            background-color: rgba(255,255,255,0.1);
            width: 100%;
            margin: 2rem 0;
        }
    </style>
</head>
<body class="font-sans antialiased selection:bg-brand-red selection:text-white">

    <!-- HERO SECTION -->
    <header class="relative min-h-screen flex flex-col justify-center items-center text-center bg-brand-black w-full overflow-hidden px-6">
        <div class="max-w-4xl reveal flex flex-col items-center">
            <p class="text-brand-red uppercase tracking-[0.2em] text-xs font-bold mb-6">
                From the Refugee Archive Oral Histories
            </p>
            
            <h1 class="font-serif text-4xl md:text-5xl lg:text-6xl leading-tight mb-8 text-brand-white">
                "I carried the weight of our history so my children would only have to carry their future."
            </h1>
            
            <p class="font-garamond text-xl md:text-2xl text-gray-400 italic mb-12">
                — Anonymized Mother, Urban Periphery
            </p>

            <a href="#explore" class="inline-flex items-center group">
                <span class="bg-brand-red text-white px-8 py-4 text-sm uppercase tracking-widest font-medium transition-transform group-hover:bg-[#7a2222]">
                    Explore the Archive
                </span>
                <span class="bg-brand-red text-white p-4 ml-[1px] transition-transform group-hover:translate-x-1 group-hover:bg-[#7a2222]">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="square" stroke-linejoin="miter" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
                </span>
            </a>
        </div>
    </header>

    <!-- ABOUT SECTION -->
    <section class="py-24 md:py-32 bg-brand-beige text-brand-black px-6">
        <div class="max-w-4xl mx-auto text-center reveal">
            <h2 class="font-serif text-4xl md:text-5xl mb-8">Why These Voices Matter</h2>
            <div class="minimal-separator max-w-xs mx-auto mb-10 border-brand-black/20"></div>
            <p class="font-sans text-lg md:text-xl font-light leading-relaxed max-w-3xl mx-auto mb-6">
                These are real oral histories. They are lived experiences and documented testimonies of displacement, survival, and resilience. 
            </p>
            <p class="font-sans text-lg md:text-xl font-light leading-relaxed max-w-3xl mx-auto">
                We are not presenting statistics; we are presenting human stories. Grounded. Direct. Humanitarian. This is an archive of truth, devoid of corporate sentimentality, honoring the agency of those who lived it.
            </p>
        </div>
    </section>

    <!-- ARCHIVE GRAPHICS PREVIEW (1:1 Template Previews) -->
    <section id="explore" class="py-24 bg-brand-white px-6">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16 reveal">
                <h2 class="font-serif text-3xl md:text-4xl mb-4">The Campaign Visuals</h2>
                <p class="font-sans text-gray-500 uppercase tracking-widest text-sm mb-6">Official Template References</p>
                
                <a href="https://www.canva.com/design/DAHCVTXfHfg/OL68Y6BCP0ZpP4Zmb5fGPA/edit?utm_content=DAHCVTXfHfg&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 bg-brand-red text-white px-6 py-3 text-sm uppercase tracking-widest font-medium transition-colors hover:bg-[#7a2222]">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path></svg>
                    Edit in Canva
                </a>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Graphic 1 -->
                <div class="aspect-square bg-gray-100 relative group overflow-hidden reveal reveal-delay-1 cursor-pointer lightbox-trigger" data-src="https://i.ibb.co/8vz7nmp/Example-05.png">
                    <img src="https://i.ibb.co/8vz7nmp/Example-05.png" alt="Quote Graphic Reference 1" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105">
                    <div class="absolute inset-0 bg-brand-black/40 opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-center justify-center">
                        <svg class="w-10 h-10 text-brand-white opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0zM10 7v3m0 0v3m0-3h3m-3 0H7"></path></svg>
                    </div>
                </div>
                <!-- Graphic 2 -->
                <div class="aspect-square bg-gray-100 relative group overflow-hidden reveal reveal-delay-2 cursor-pointer lightbox-trigger" data-src="https://i.ibb.co/hR9qgsXZ/Example-04.png">
                    <img src="https://i.ibb.co/hR9qgsXZ/Example-04.png" alt="Quote Graphic Reference 2" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105">
                    <div class="absolute inset-0 bg-brand-black/40 opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-center justify-center">
                        <svg class="w-10 h-10 text-brand-white opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0zM10 7v3m0 0v3m0-3h3m-3 0H7"></path></svg>
                    </div>
                </div>
                <!-- Graphic 3 -->
                <div class="aspect-square bg-gray-100 relative group overflow-hidden reveal reveal-delay-3 cursor-pointer lightbox-trigger" data-src="https://i.ibb.co/Sws8qvHR/Example-02.png">
                    <img src="https://i.ibb.co/Sws8qvHR/Example-02.png" alt="Quote Graphic Reference 3" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105">
                    <div class="absolute inset-0 bg-brand-black/40 opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-center justify-center">
                        <svg class="w-10 h-10 text-brand-white opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0zM10 7v3m0 0v3m0-3h3m-3 0H7"></path></svg>
                    </div>
                </div>
                <!-- Graphic 4 -->
                <div class="aspect-square bg-gray-100 relative group overflow-hidden reveal reveal-delay-1 cursor-pointer lightbox-trigger" data-src="https://i.ibb.co/7df9tBsx/Front.png">
                    <img src="https://i.ibb.co/7df9tBsx/Front.png" alt="Quote Graphic Reference 4" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105">
                    <div class="absolute inset-0 bg-brand-black/40 opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-center justify-center">
                        <svg class="w-10 h-10 text-brand-white opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0zM10 7v3m0 0v3m0-3h3m-3 0H7"></path></svg>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- PROCESS SECTION -->
    <section class="py-24 md:py-32 bg-brand-white border-t border-gray-200 px-6">
        <div class="max-w-6xl mx-auto reveal">
            <h2 class="font-serif text-4xl md:text-5xl text-center mb-20">How the Campaign Works</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-12 lg:gap-24">
                <!-- Step 1 -->
                <div class="relative reveal reveal-delay-1">
                    <span class="text-brand-red font-serif text-6xl opacity-20 absolute -top-8 -left-4">01</span>
                    <h3 class="font-sans font-semibold uppercase tracking-widest text-sm mb-4 relative z-10">Select</h3>
                    <div class="w-8 h-px bg-brand-red mb-6"></div>
                    <p class="font-sans font-light leading-relaxed text-gray-700">
                        You browse our extensive archive of verified oral history transcripts and select a powerful, resonant statement.
                    </p>
                </div>
                
                <!-- Step 2 -->
                <div class="relative reveal reveal-delay-2">
                    <span class="text-brand-red font-serif text-6xl opacity-20 absolute -top-8 -left-4">02</span>
                    <h3 class="font-sans font-semibold uppercase tracking-widest text-sm mb-4 relative z-10">Translate</h3>
                    <div class="w-8 h-px bg-brand-red mb-6"></div>
                    <p class="font-sans font-light leading-relaxed text-gray-700">
                        You translate the selected quote, ensuring the speaker's original voice, tone, and dignity are meticulously preserved.
                    </p>
                </div>
                
                <!-- Step 3 -->
                <div class="relative reveal reveal-delay-3">
                    <span class="text-brand-red font-serif text-6xl opacity-20 absolute -top-8 -left-4">03</span>
                    <h3 class="font-sans font-semibold uppercase tracking-widest text-sm mb-4 relative z-10">Publish</h3>
                    <div class="w-8 h-px bg-brand-red mb-6"></div>
                    <p class="font-sans font-light leading-relaxed text-gray-700">
                        You design the quote graphic using our official template, write contextual copy, tag The Refugee Archive, and publish it to the world.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- IMPACT SECTION -->
    <section class="py-24 md:py-32 bg-brand-black text-brand-white px-6">
        <div class="max-w-5xl mx-auto flex flex-col md:flex-row gap-16 items-center reveal">
            <div class="md:w-1/3">
                <h2 class="font-serif text-4xl md:text-5xl leading-tight">More Than <br/><span class="text-brand-red italic">a Quote.</span></h2>
            </div>
            <div class="md:w-2/3">
                <div class="dark-separator hidden md:block mt-0 mb-8"></div>
                <p class="font-sans text-xl font-light leading-relaxed mb-6 text-gray-300">
                    These quotes are entry points to deeper narratives. They are designed to highlight the devastating realities of displacement, widening education gaps, false promises from institutions, and systemic injustice.
                </p>
                <p class="font-sans text-xl font-light leading-relaxed text-gray-300">
                    By strictly centering mothers and their lived experiences, we keep statements short, undeniable, and exceptionally powerful.
                </p>
            </div>
        </div>
    </section>

    <!-- Lightbox Modal -->
    <div id="lightbox" class="fixed inset-0 z-50 hidden bg-brand-black/95 flex justify-center items-center p-4 md:p-8 opacity-0 transition-opacity duration-300">
        <button id="close-lightbox" class="absolute top-6 right-6 text-white hover:text-brand-red transition-colors z-50">
            <svg class="w-10 h-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M6 18L18 6M6 6l12 12"></path></svg>
        </button>
        <div class="relative w-full h-full flex justify-center items-center">
            <img id="lightbox-img" src="" alt="Expanded Template" class="max-w-full max-h-full object-contain shadow-2xl scale-95 transition-transform duration-300">
        </div>
    </div>

    <!-- Script for Scroll Animations and Lightbox -->
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // Scroll Animations
            const reveals = document.querySelectorAll('.reveal');

            const revealOnScroll = () => {
                const windowHeight = window.innerHeight;
                const elementVisible = 100;

                reveals.forEach((reveal) => {
                    const elementTop = reveal.getBoundingClientRect().top;
                    if (elementTop < windowHeight - elementVisible) {
                        reveal.classList.add('active');
                    }
                });
            };

            window.addEventListener('scroll', revealOnScroll);
            revealOnScroll(); // Trigger once on load

            // Lightbox Functionality
            const lightbox = document.getElementById('lightbox');
            const lightboxImg = document.getElementById('lightbox-img');
            const closeLightboxBtn = document.getElementById('close-lightbox');
            const triggers = document.querySelectorAll('.lightbox-trigger');

            const openLightbox = (src) => {
                lightboxImg.src = src;
                lightbox.classList.remove('hidden');
                // Force reflow
                void lightbox.offsetWidth;
                lightbox.classList.remove('opacity-0');
                lightboxImg.classList.remove('scale-95');
                lightboxImg.classList.add('scale-100');
                document.body.style.overflow = 'hidden';
            };

            const closeLightbox = () => {
                lightbox.classList.add('opacity-0');
                lightboxImg.classList.remove('scale-100');
                lightboxImg.classList.add('scale-95');
                setTimeout(() => {
                    lightbox.classList.add('hidden');
                    lightboxImg.src = '';
                    document.body.style.overflow = '';
                }, 300);
            };

            triggers.forEach(trigger => {
                trigger.addEventListener('click', () => {
                    openLightbox(trigger.dataset.src);
                });
            });

            closeLightboxBtn.addEventListener('click', closeLightbox);
            
            lightbox.addEventListener('click', (e) => {
                if (e.target === lightbox || e.target.parentElement === lightbox) {
                    closeLightbox();
                }
            });

            document.addEventListener('keydown', (e) => {
                if (e.key === 'Escape' && !lightbox.classList.contains('hidden')) {
                    closeLightbox();
                }
            });
        });
    </script>
</body>
</html>
