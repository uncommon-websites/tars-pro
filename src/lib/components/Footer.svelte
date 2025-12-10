<footer class="relative bg-black text-white">
    <!-- CTA Section -->
    <div class="relative overflow-hidden bg-white text-gray-900 pt-24 pb-48">
         <div class="absolute inset-0 bg-gradient-to-b from-purple-50/50 via-purple-100/50 to-white pointer-events-none"></div>
         <div class="absolute inset-0 bg-grid-pattern opacity-30 pointer-events-none"></div>
         
         <div class="relative z-10 text-center max-w-4xl mx-auto px-4">
             <h2 class="text-5xl md:text-6xl font-medium tracking-tight mb-6">
                 Bring AI to Solana<br/>for 1M+ users
             </h2>
             <p class="text-gray-500 text-lg mb-8">
                 Build, scale, and adopt AI with Tars today.
             </p>
             <button class="bg-gray-900 text-white px-8 py-3 rounded-md text-sm font-medium hover:bg-gray-800 transition-colors inline-flex items-center gap-2">
                Adopt now
                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
            </button>
         </div>

         <!-- 3D Jacks/Shapes Overlay at bottom -->
         <div class="absolute bottom-0 left-0 right-0 h-32 overflow-hidden">
             <!-- Abstract shapes simulation -->
             <div class="w-full h-full flex items-end justify-center gap-4 opacity-50 grayscale">
                 {#each Array(10) as _, i}
                    <div class="w-16 h-16 bg-gradient-to-tr from-gray-300 to-gray-100 transform rotate-45 translate-y-8 rounded-lg shadow-xl"></div>
                 {/each}
             </div>
             <!-- Gradient fade to black -->
             <div class="absolute inset-0 bg-gradient-to-b from-transparent to-black"></div>
         </div>
    </div>

    <!-- Footer Links -->
    <div class="bg-black pt-12 pb-8 border-t border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-12 mb-12">
                <!-- Brand -->
                <div class="col-span-1">
                    <div class="flex items-center gap-2 mb-6">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M12 2L2 7L12 12L22 7L12 2Z" fill="#7c3aed"/>
                            <path d="M2 17L12 22L22 17" stroke="#7c3aed" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            <path d="M2 12L12 17L22 12" stroke="#7c3aed" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                        <span class="font-bold text-xl tracking-tight text-white">TARS</span>
                    </div>
                    <div class="flex gap-4 text-gray-400">
                        <a href="#" class="hover:text-white"><svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.48 2 2 6.48 2 12c0 5.52 4.48 10 10 10s10-4.48 10-10c0-5.52-4.48-10-10-10zm-1 14h-2v-2h2v2zm0-4h-2V7h2v5z"/></svg></a> <!-- Discord placeholder -->
                        <a href="#" class="hover:text-white"><svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor"><path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/></svg></a>
                        <a href="#" class="hover:text-white"><svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor"><path d="M21 2L3 9l9 3 3 9 6-19z"/></svg></a> <!-- Telegram placeholder -->
                    </div>
                </div>

                <!-- Column 1 -->
                <div>
                    <h3 class="text-gray-500 font-medium mb-4">About</h3>
                    <ul class="space-y-3 text-sm text-gray-300">
                        <li><a href="#" class="hover:text-white">Manifesto</a></li>
                        <li><a href="#" class="hover:text-white">Acceleration Program</a></li>
                        <li><a href="#" class="hover:text-white">Ecosystem</a></li>
                        <li><a href="#" class="hover:text-white">Partners</a></li>
                        <li><a href="#" class="hover:text-white">Careers</a></li>
                        <li><a href="#" class="hover:text-white">Brand Guidelines</a></li>
                        <li><a href="#" class="hover:text-white">Tokenomics</a></li>
                    </ul>
                </div>

                <!-- Column 2 -->
                <div>
                    <h3 class="text-gray-500 font-medium mb-4">Products</h3>
                    <ul class="space-y-3 text-sm text-gray-300">
                        <li><a href="#" class="hover:text-white">AI Market</a></li>
                        <li><a href="#" class="hover:text-white">Staking</a></li>
                        <li><a href="#" class="hover:text-white">Sona</a></li>
                        <li><a href="#" class="hover:text-white">Tars Search Engine</a></li>
                    </ul>
                </div>

                <!-- Column 3 -->
                <div>
                    <h3 class="text-gray-500 font-medium mb-4 text-purple-400">Coming soon</h3>
                    <ul class="space-y-3 text-sm text-gray-300">
                        <li><a href="#" class="hover:text-white">Docs</a></li>
                        <li><a href="#" class="hover:text-white">AI Agent Market</a></li>
                    </ul>
                </div>
            </div>

            <div class="border-t border-gray-800 pt-8 flex flex-col md:flex-row justify-between items-center text-xs text-gray-500">
                <div class="flex gap-6 mb-4 md:mb-0">
                    <a href="#" class="hover:text-gray-300">Terms & Conditions</a>
                    <a href="#" class="hover:text-gray-300">Privacy Policy</a>
                </div>
                <div>
                    Tars AI © 2025. All rights reserved.
                </div>
            </div>
        </div>
    </div>
</footer>
