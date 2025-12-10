<script>
    // No script needed for now
</script>

<section class="relative w-full overflow-hidden border-b border-grid bg-white">
    <!-- Top Purple Gradient/Mesh -->
    <div class="absolute top-0 left-0 right-0 h-[500px] bg-gradient-to-b from-purple-100/80 via-purple-50/50 to-white pointer-events-none"></div>
    
    <!-- Grid Pattern Overlay -->
    <div class="absolute inset-0 bg-grid-pattern opacity-30 pointer-events-none"></div>

    <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pt-8 pb-24">
        
        <!-- Top Banner -->
        <div class="flex justify-center mb-12">
            <div class="inline-flex items-center gap-2 px-4 py-2 bg-white/50 backdrop-blur-sm rounded-full border border-gray-200 text-xs font-medium text-gray-600">
                Grant recipient from 
                <span class="font-bold flex items-center gap-1">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M4 16h16v2H4v-2zm0-6h16v2H4v-2zm0-6h16v2H4V4z"/></svg>
                    SOLANA FOUNDATION
                </span>
            </div>
        </div>

        <!-- Main Content Grid -->
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-end relative z-10">
            
            <!-- Left Text -->
            <div class="lg:col-span-4 lg:pb-12 text-center lg:text-left order-2 lg:order-1">
                <h1 class="text-4xl lg:text-5xl font-medium tracking-tight text-gray-900 mb-4">
                    The AI Architecture Protocol On Solana
                </h1>
                <p class="text-gray-500 text-sm leading-relaxed max-w-md mx-auto lg:mx-0">
                    Symbiotic AI app ecosystem dedicated to 1,000,000+ Solana users.
                </p>
            </div>

            <!-- Center Image (The 3D Shape) -->
            <div class="lg:col-span-4 flex flex-col items-center justify-center order-1 lg:order-2 mb-8 lg:mb-0">
                <!-- Abstract 3D Shape Representation -->
                <div class="w-64 h-64 relative">
                    <svg viewBox="0 0 200 200" fill="none" xmlns="http://www.w3.org/2000/svg" class="w-full h-full drop-shadow-2xl">
                        <defs>
                            <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="100%">
                                <stop offset="0%" style="stop-color:#d8b4fe;stop-opacity:1" />
                                <stop offset="100%" style="stop-color:#7c3aed;stop-opacity:1" />
                            </linearGradient>
                            <filter id="glow">
                                <feGaussianBlur stdDeviation="10" result="coloredBlur"/>
                                <feMerge>
                                    <feMergeNode in="coloredBlur"/>
                                    <feMergeNode in="SourceGraphic"/>
                                </feMerge>
                            </filter>
                        </defs>
                        <!-- Y Shape -->
                        <path d="M100 180 C 100 180, 140 100, 180 80 C 160 80, 140 60, 100 100 C 60 60, 40 80, 20 80 C 60 100, 100 180, 100 180" fill="url(#grad1)" filter="url(#glow)"/>
                        <!-- Top details -->
                        <ellipse cx="100" cy="100" rx="10" ry="5" fill="#fff" opacity="0.5"/>
                    </svg>
                </div>

                <!-- CTA Button -->
                <button class="mt-8 bg-gray-900 text-white px-8 py-3 rounded-md text-sm font-medium hover:bg-gray-800 transition-colors flex items-center gap-2 group">
                    Start Now
                    <svg class="w-4 h-4 group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
                </button>
                
                <!-- Small icons below button -->
                <div class="flex gap-4 mt-6 text-gray-300">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1"><rect x="3" y="3" width="18" height="18" rx="2" ry="2"/><line x1="3" y1="9" x2="21" y2="9"/><line x1="9" y1="21" x2="9" y2="9"/></svg>
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1"><circle cx="12" cy="12" r="10"/><path d="M8 14s1.5 2 4 2 4-2 4-2"/><line x1="9" y1="9" x2="9.01" y2="9"/><line x1="15" y1="9" x2="15.01" y2="9"/></svg>
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"/></svg>
                </div>
            </div>

            <!-- Right Text -->
            <div class="lg:col-span-4 lg:pb-12 text-center lg:text-left order-3">
                <h2 class="text-2xl font-medium text-gray-900 mb-2">AI Market</h2>
                <p class="text-gray-500 text-sm leading-relaxed mb-4 max-w-md mx-auto lg:mx-0">
                    Access modular AI app and ecosystem products at a glance in one super-app.
                </p>
                <a href="#" class="inline-flex items-center text-sm font-medium text-gray-900 hover:text-gray-700">
                    More details 
                    <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
                </a>
            </div>
        </div>
    </div>
</section>
