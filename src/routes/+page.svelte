<script lang="ts">
    import AppButtons from "$lib/components/AppButtons.svelte";
    import PhoneMockup from "$lib/components/PhoneMockup.svelte";
</script>

<div class="w-full overflow-hidden">
    <!-- Header -->
    <header class="w-full py-8 flex flex-col items-center justify-center text-center">
        <h1 class="text-4xl font-serif font-medium tracking-tight">HabitStackr</h1>
        <p class="text-xs uppercase tracking-widest text-gray-500 mt-2 font-sans">Daily habits, made inevitable</p>
    </header>

    <!-- Hero Section -->
    <section class="max-w-7xl mx-auto px-6 pt-12 pb-24 grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
        <div class="flex flex-col items-start space-y-8">
            <h2 class="text-6xl md:text-7xl font-serif leading-[1.1]">
                Systems over<br/>
                motivation.
            </h2>
            <p class="text-gray-600 max-w-md leading-relaxed">
                For founders and creators who need daily consistency. Visible streaks, community accountability, and one-minute check-ins make your habits inevitable.
            </p>
            <div class="pt-2">
                <AppButtons />
            </div>
        </div>
        
        <div class="relative flex justify-center items-center">
            <!-- Abstract Background Shapes -->
            <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[500px] h-[500px] opacity-20 pointer-events-none">
                 <svg viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg" class="w-full h-full fill-primary-200">
                    <path d="M44.7,-76.4C58.9,-69.2,71.8,-59.1,81.6,-46.6C91.4,-34.1,98.2,-19.2,95.8,-5.2C93.4,8.8,81.8,21.9,71.2,33.7C60.6,45.4,51,55.8,39.9,64.4C28.8,73,16.2,79.8,2.6,75.3C-11,70.8,-25.6,55,-38.7,42.5C-51.8,30,-63.4,20.8,-69.3,8.7C-75.2,-3.4,-75.4,-18.4,-68.8,-31.6C-62.2,-44.8,-48.8,-56.2,-35.4,-63.8C-22,-71.4,-8.6,-75.2,5.2,-84.2C19,-93.2,30.5,-107.4,44.7,-76.4Z" transform="translate(100 100)" />
                  </svg>
            </div>
            
            <PhoneMockup>
                <!-- Mockup Content -->
                <div class="flex flex-col h-full p-6 pt-16 bg-white">
                    <div class="text-xs uppercase tracking-widest text-gray-500 mb-4">Today</div>
                    <div class="space-y-3 flex-1">
                        <!-- Habit 1 -->
                        <div class="flex items-center gap-3 p-3 bg-gray-50 rounded-lg">
                            <div class="w-6 h-6 bg-primary-500 rounded flex items-center justify-center text-white text-xs font-bold">✓</div>
                            <div class="flex-1">
                                <div class="text-sm font-medium">Morning pages</div>
                                <div class="text-xs text-gray-500">47 day streak</div>
                            </div>
                        </div>
                        <!-- Habit 2 -->
                        <div class="flex items-center gap-3 p-3 bg-gray-50 rounded-lg">
                            <div class="w-6 h-6 border-2 border-gray-300 rounded"></div>
                            <div class="flex-1">
                                <div class="text-sm font-medium">Ship something</div>
                                <div class="text-xs text-gray-500">12 day streak</div>
                            </div>
                        </div>
                        <!-- Habit 3 -->
                        <div class="flex items-center gap-3 p-3 bg-gray-50 rounded-lg">
                            <div class="w-6 h-6 border-2 border-gray-300 rounded"></div>
                            <div class="flex-1">
                                <div class="text-sm font-medium">Exercise</div>
                                <div class="text-xs text-gray-500">31 day streak</div>
                            </div>
                        </div>
                    </div>
                    <div class="text-center text-xs text-gray-400 mt-4">3 people in your group checked in today</div>
                </div>
            </PhoneMockup>
        </div>
    </section>

    <!-- Dark Section (The Consistency Loop) -->
    <section class="bg-[#1C1C1C] text-white py-24 overflow-hidden relative">
        <div class="max-w-7xl mx-auto px-6 mb-16">
            <p class="text-xl md:text-2xl font-serif max-w-lg leading-relaxed text-gray-300">
                The Consistency Loop: How HabitStackr transforms behavior into identity.
            </p>
        </div>

        <div class="relative w-full overflow-x-hidden">
            <div class="flex whitespace-nowrap px-6 gap-4 md:gap-12 items-center">
                 <!-- Item 1 -->
                 <div class="inline-flex items-baseline">
                    <span class="text-[120px] md:text-[180px] font-serif font-light text-primary-500">1.</span>
                    <div class="flex flex-col ml-4">
                        <span class="text-5xl md:text-7xl font-serif font-bold">Visibility</span>
                        <span class="text-5xl md:text-7xl font-serif text-gray-400">creates pressure</span>
                    </div>
                 </div>
                 
                 <!-- Item 2 -->
                 <div class="inline-flex items-baseline ml-12 md:ml-24">
                    <span class="text-[120px] md:text-[180px] font-serif font-light text-primary-400">2.</span>
                    <div class="flex flex-col ml-4">
                        <span class="text-5xl md:text-7xl font-serif font-bold">Pressure</span>
                        <span class="text-5xl md:text-7xl font-serif text-gray-400">creates consistency</span>
                    </div>
                 </div>

                 <!-- Item 3 -->
                   <div class="inline-flex items-baseline ml-12 md:ml-24">
                    <span class="text-[120px] md:text-[180px] font-serif font-light text-primary-300">3.</span>
                    <div class="flex flex-col ml-4">
                        <span class="text-5xl md:text-7xl font-serif font-bold">Consistency</span>
                        <span class="text-5xl md:text-7xl font-serif text-gray-400">creates identity</span>
                    </div>
                 </div>
            </div>
        </div>

        <div class="max-w-7xl mx-auto px-6 mt-12">
            <p class="text-gray-500 text-sm max-w-md">
                Show up once per day. The system carries the rest.
            </p>
        </div>
    </section>

    <!-- Why we're different -->
    <section class="py-32 max-w-5xl mx-auto px-6">
        <div class="text-center mb-24">
            <p class="text-sm uppercase tracking-widest text-gray-500">Built for consistency</p>
        </div>

        <div class="space-y-32">
            <!-- Feature 1 -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center group">
                <div>
                    <h3 class="text-5xl md:text-6xl font-serif mb-6 group-hover:italic transition-all duration-300">Systems<br>over<br>motivation</h3>
                    <p class="text-gray-600 max-w-xs text-sm leading-relaxed">
                        Motivation is unreliable. We build structure and visibility that makes habits automatic, not dependent on how you feel.
                    </p>
                    <div class="mt-4 text-xs text-gray-400">→</div>
                </div>
                <div class="flex justify-center">
                    <!-- Illustration Placeholder: Stacked Rocks -->
                    <div class="w-64 h-64 relative">
                        <svg viewBox="0 0 200 200" class="w-full h-full stroke-black fill-none stroke-[1.5]">
                            <path d="M60,140 Q50,120 70,110 Q90,100 110,110 Q130,120 120,140 Q110,160 90,160 Q70,160 60,140 Z" />
                            <path d="M75,105 Q65,85 85,75 Q105,65 125,75 Q145,85 135,105 Q125,125 105,125 Q85,125 75,105 Z" />
                            <path d="M90,70 Q80,50 100,40 Q120,30 140,40 Q160,50 150,70 Q140,90 120,90 Q100,90 90,70 Z" />
                        </svg>
                        <div class="absolute -z-10 top-10 right-10 w-40 h-40 bg-primary-100 rounded-full opacity-50 blur-xl"></div>
                    </div>
                </div>
            </div>

            <!-- Feature 2 -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center group">
                <div>
                    <h3 class="text-5xl md:text-6xl font-serif mb-6 group-hover:italic transition-all duration-300">Fewer<br>habits,<br>not more</h3>
                    <p class="text-gray-600 max-w-xs text-sm leading-relaxed">
                        Track 1-5 habits maximum. Tracking everything leads to tracking nothing. Focus on what meaningfully moves your life forward.
                    </p>
                    <div class="mt-4 text-xs text-gray-400">→</div>
                </div>
                <div class="flex justify-center">
                    <!-- Illustration Placeholder: Handshake -->
                    <div class="w-64 h-64 relative">
                        <svg viewBox="0 0 200 200" class="w-full h-full stroke-black fill-none stroke-[1.5]">
                            <path d="M40,100 L80,100 L100,80 L120,100 L160,100" />
                            <path d="M40,120 L80,120 L100,140 L120,120 L160,120" />
                             <!-- Simplified abstract representation -->
                             <circle cx="100" cy="110" r="40" class="stroke-black" />
                        </svg>
                         <div class="absolute -z-10 top-10 right-10 w-40 h-40 bg-primary-100 rounded-full opacity-50 blur-xl"></div>
                    </div>
                </div>
            </div>

            <!-- Feature 3 -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center group">
                <div>
                    <h3 class="text-5xl md:text-6xl font-serif mb-6 group-hover:italic transition-all duration-300">Community<br>without<br>noise</h3>
                    <p class="text-gray-600 max-w-xs text-sm leading-relaxed">
                        No algorithmic feed. No vanity posting. No engagement farming. Just curated accountability with people who show up daily.
                    </p>
                    <div class="mt-4 text-xs text-gray-400">→</div>
                </div>
                <div class="flex justify-center">
                    <!-- Illustration Placeholder: Tools -->
                    <div class="w-64 h-64 relative">
                        <svg viewBox="0 0 200 200" class="w-full h-full stroke-black fill-none stroke-[1.5]">
                            <path d="M50,150 L150,50" />
                            <circle cx="150" cy="50" r="10" />
                            <rect x="40" y="140" width="20" height="20" transform="rotate(45 50 150)" />
                        </svg>
                         <div class="absolute -z-10 top-10 right-10 w-40 h-40 bg-primary-100 rounded-full opacity-50 blur-xl"></div>
                    </div>
                </div>
            </div>
            
             <!-- Feature 4 -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center group">
                <div>
                    <h3 class="text-5xl md:text-6xl font-serif mb-6 group-hover:italic transition-all duration-300">Spreadsheet<br>clarity,<br>zero clutter</h3>
                    <p class="text-gray-600 max-w-xs text-sm leading-relaxed">
                        Data-driven design with no-nonsense functionality. See your progress at a glance without overwhelming visuals or excessive celebration.
                    </p>
                    <div class="mt-4 text-xs text-gray-400">→</div>
                </div>
                <div class="flex justify-center">
                    <!-- Illustration Placeholder: Clock -->
                    <div class="w-64 h-64 relative">
                         <svg viewBox="0 0 200 200" class="w-full h-full stroke-black fill-none stroke-[1.5]">
                            <circle cx="100" cy="100" r="50" />
                            <path d="M100,100 L100,70" />
                            <path d="M100,100 L120,110" />
                            <path d="M90,40 L110,40" />
                        </svg>
                         <div class="absolute -z-10 top-10 right-10 w-40 h-40 bg-primary-100 rounded-full opacity-50 blur-xl"></div>
                    </div>
                </div>
            </div>

             <!-- Feature 5 -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center group">
                <div>
                    <h3 class="text-5xl md:text-6xl font-serif mb-6 group-hover:italic transition-all duration-300">Privacy-first<br>accountability</h3>
                    <p class="text-gray-600 max-w-xs text-sm leading-relaxed">
                        Control what others see. Keep habits private, redacted, or visible. Social accountability exists even when details stay hidden.
                    </p>
                    <div class="mt-4 text-xs text-gray-400">→</div>
                </div>
                <div class="flex justify-center">
                    <!-- Illustration Placeholder: Heart -->
                    <div class="w-64 h-64 relative">
                         <svg viewBox="0 0 200 200" class="w-full h-full stroke-black fill-none stroke-[1.5]">
                            <path d="M100,160 C100,160 40,100 40,60 C40,30 70,30 100,60 C130,30 160,30 160,60 C160,100 100,160 100,160 Z" />
                        </svg>
                         <div class="absolute -z-10 top-10 right-10 w-40 h-40 bg-primary-100 rounded-full opacity-50 blur-xl"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Mid CTA -->
    <section class="py-24 bg-[#FCFAF7] border-y border-gray-100">
        <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
            <div>
                <p class="text-2xl md:text-3xl font-serif leading-relaxed mb-8">
                    One-minute check-ins. Visible streaks. Community accountability. Show up once per day, and the system carries the rest.
                </p>
                <AppButtons />
            </div>
            <div class="flex justify-center">
                <!-- Jar Illustration -->
                 <div class="w-64 h-64 relative">
                     <svg viewBox="0 0 200 200" class="w-full h-full stroke-black fill-none stroke-[1.5]">
                        <path d="M60,60 L140,60 L140,160 Q140,180 120,180 L80,180 Q60,180 60,160 Z" />
                        <path d="M55,60 L145,60 L145,40 L55,40 Z" />
                        <path d="M70,100 L130,100" />
                        <path d="M70,140 L130,140" />
                    </svg>
                    <div class="absolute -z-10 bottom-0 left-10 w-40 h-20 bg-primary-200 rounded-full opacity-50 blur-xl"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Dark Cards Section -->
    <section class="py-24">
        <div class="max-w-4xl mx-auto px-6 mb-16">
            <h2 class="text-4xl font-serif">HabitStackr is designed for<br>execution over reflection.</h2>
            <p class="text-gray-500 mt-4 max-w-md">
                Simple tools that prioritize doing over thinking. No endless self-analysis, just consistent action.
            </p>
        </div>

        <div class="max-w-6xl mx-auto px-6 space-y-8">
            <!-- Card 1 -->
            <div class="bg-[#1C1C1C] rounded-[2rem] p-12 md:p-20 text-white relative overflow-hidden flex flex-col md:flex-row items-center gap-12">
                <div class="relative z-10 w-full md:w-1/2 flex justify-center">
                     <PhoneMockup>
                         <div class="p-6 flex flex-col h-full bg-white text-black">
                             <div class="text-xs text-gray-500 uppercase tracking-widest mb-4">Your Streaks</div>
                             <div class="space-y-4">
                                 <div class="flex items-center justify-between">
                                     <span class="text-sm font-medium">Morning pages</span>
                                     <span class="text-2xl font-bold text-primary-600">47</span>
                                 </div>
                                 <div class="flex items-center justify-between">
                                     <span class="text-sm font-medium">Ship something</span>
                                     <span class="text-2xl font-bold text-primary-600">12</span>
                                 </div>
                                 <div class="flex items-center justify-between">
                                     <span class="text-sm font-medium">Exercise</span>
                                     <span class="text-2xl font-bold text-primary-600">31</span>
                                 </div>
                             </div>
                             <div class="mt-8 pt-4 border-t border-gray-100">
                                 <div class="text-xs text-gray-500">Total check-ins: 90 days</div>
                             </div>
                         </div>
                     </PhoneMockup>
                </div>
                <div class="w-full md:w-1/2 relative z-10">
                    <p class="text-xs uppercase tracking-widest text-gray-400 mb-2">Visible progress</p>
                    <h3 class="text-4xl md:text-5xl font-serif mb-6">Streaks that<br>create pressure</h3>
                    <p class="text-gray-400 leading-relaxed">
                        Your streak count is always visible. That visibility creates gentle pressure. The pressure creates consistency. Consistency creates identity.
                    </p>
                </div>
                <!-- Abstract BG -->
                <div class="absolute left-0 bottom-0 w-1/2 h-full bg-white opacity-5 rounded-full blur-3xl translate-y-1/2 -translate-x-1/4"></div>
            </div>

             <!-- Card 2 -->
            <div class="bg-[#1C1C1C] rounded-[2rem] p-12 md:p-20 text-white relative overflow-hidden flex flex-col md:flex-row-reverse items-center gap-12">
                <div class="relative z-10 w-full md:w-1/2 flex justify-center">
                     <PhoneMockup>
                         <div class="p-6 flex flex-col h-full bg-white text-black">
                             <div class="text-xs text-gray-500 uppercase tracking-widest mb-4">Your Group</div>
                             <div class="space-y-3">
                                 <div class="flex items-center gap-3">
                                     <div class="w-8 h-8 bg-gray-200 rounded-full"></div>
                                     <div class="flex-1">
                                         <div class="text-sm font-medium">Alex K.</div>
                                         <div class="text-xs text-gray-500">3/3 today</div>
                                     </div>
                                     <div class="text-xs text-primary-600 font-bold">✓</div>
                                 </div>
                                 <div class="flex items-center gap-3">
                                     <div class="w-8 h-8 bg-gray-200 rounded-full"></div>
                                     <div class="flex-1">
                                         <div class="text-sm font-medium">Jordan M.</div>
                                         <div class="text-xs text-gray-500">2/3 today</div>
                                     </div>
                                 </div>
                                 <div class="flex items-center gap-3">
                                     <div class="w-8 h-8 bg-gray-200 rounded-full"></div>
                                     <div class="flex-1">
                                         <div class="text-sm font-medium">You</div>
                                         <div class="text-xs text-gray-500">1/3 today</div>
                                     </div>
                                 </div>
                             </div>
                         </div>
                     </PhoneMockup>
                </div>
                <div class="w-full md:w-1/2 relative z-10">
                    <p class="text-xs uppercase tracking-widest text-gray-400 mb-2">Invite-driven</p>
                    <h3 class="text-4xl md:text-5xl font-serif mb-6">Curated<br>accountability</h3>
                    <p class="text-gray-400 leading-relaxed">
                        Join invite-only groups of serious practitioners. No vanity posting, no engagement farming. Just ambient awareness of others showing up daily.
                    </p>
                </div>
            </div>

             <!-- Card 3 -->
            <div class="bg-[#1C1C1C] rounded-[2rem] p-12 md:p-20 text-white relative overflow-hidden flex flex-col md:flex-row items-center gap-12">
                <div class="relative z-10 w-full md:w-1/2 flex justify-center">
                     <PhoneMockup>
                         <div class="p-6 flex flex-col h-full bg-white text-black items-center justify-center">
                             <div class="text-center mb-8">
                                 <div class="text-6xl font-serif mb-2">✓</div>
                                 <p class="text-sm text-gray-500">Check-in complete</p>
                             </div>
                             <div class="text-xs text-gray-400">Time taken: 42 seconds</div>
                         </div>
                     </PhoneMockup>
                </div>
                <div class="w-full md:w-1/2 relative z-10">
                    <p class="text-xs uppercase tracking-widest text-gray-400 mb-2">Under 60 seconds</p>
                    <h3 class="text-4xl md:text-5xl font-serif mb-6">Frictionless<br>check-ins</h3>
                    <p class="text-gray-400 leading-relaxed">
                        No long notes. No complex scoring. Just mark completion and move on. The product explicitly respects your time and attention.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Core Principles -->
    <section class="py-24 bg-[#FCFAF7]">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-3xl font-serif mb-12">Core Principles</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Principle 1 -->
                <div class="bg-white p-8 rounded-xl aspect-[4/5] flex flex-col justify-between shadow-sm hover:shadow-md transition-shadow">
                    <div class="w-8 h-8 bg-primary-100 rounded-full flex items-center justify-center text-xs text-primary-700 font-bold">01</div>
                    <h3 class="text-2xl font-serif">Systems Over Motivation</h3>
                    <div class="text-xs text-gray-400 uppercase tracking-widest">Learn More -></div>
                </div>
                 <!-- Principle 2 -->
                <div class="bg-white p-8 rounded-xl aspect-[4/5] flex flex-col justify-between shadow-sm hover:shadow-md transition-shadow">
                    <div class="w-8 h-8 bg-primary-100 rounded-full flex items-center justify-center text-xs text-primary-700 font-bold">02</div>
                    <h3 class="text-2xl font-serif">Execution Over Reflection</h3>
                    <div class="text-xs text-gray-400 uppercase tracking-widest">Learn More -></div>
                </div>
                 <!-- Principle 3 -->
                <div class="bg-white p-8 rounded-xl aspect-[4/5] flex flex-col justify-between shadow-sm hover:shadow-md transition-shadow">
                    <div class="w-8 h-8 bg-primary-100 rounded-full flex items-center justify-center text-xs text-primary-700 font-bold">03</div>
                    <h3 class="text-2xl font-serif">Identity-Based Change</h3>
                    <div class="text-xs text-gray-400 uppercase tracking-widest">Learn More -></div>
                </div>
                 <!-- Principle 4 -->
                <div class="bg-white p-8 rounded-xl aspect-[4/5] flex flex-col justify-between shadow-sm hover:shadow-md transition-shadow">
                    <div class="w-8 h-8 bg-primary-100 rounded-full flex items-center justify-center text-xs text-primary-700 font-bold">04</div>
                    <h3 class="text-2xl font-serif">Calm Confidence</h3>
                    <div class="text-xs text-gray-400 uppercase tracking-widest">Learn More -></div>
                </div>
            </div>
        </div>
    </section>

    <!-- For Founders Section -->
    <section class="py-32 max-w-5xl mx-auto px-6">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
            <div>
                <p class="text-sm uppercase tracking-widest text-gray-500 mb-4">Built for founders</p>
                <h2 class="text-4xl md:text-5xl font-serif leading-tight mb-8">
                    You already know what matters. We help you do it daily.
                </h2>
                <p class="text-gray-600 leading-relaxed mb-8">
                    HabitStackr isn't trying to convince you to become a different person. It provides infrastructure for founders and creators who need consistency, not inspiration.
                </p>
                <AppButtons />
            </div>
            <div class="flex justify-center relative">
                <!-- Stats Card -->
                <div class="w-full max-w-sm bg-white shadow-xl rounded-2xl p-8 border border-gray-100">
                    <div class="space-y-6">
                        <div class="pb-6 border-b border-gray-100">
                            <div class="text-sm text-gray-500 mb-2">Target Market</div>
                            <div class="text-3xl font-serif font-bold">$4.5B</div>
                            <div class="text-xs text-gray-400 mt-1">Wellness market</div>
                        </div>
                        <div class="pb-6 border-b border-gray-100">
                            <div class="text-sm text-gray-500 mb-2">Daily Action</div>
                            <div class="text-3xl font-serif font-bold">&lt;60s</div>
                            <div class="text-xs text-gray-400 mt-1">Check-in time</div>
                        </div>
                        <div>
                            <div class="text-sm text-gray-500 mb-2">Focus</div>
                            <div class="text-3xl font-serif font-bold">1-5</div>
                            <div class="text-xs text-gray-400 mt-1">Habits maximum</div>
                        </div>
                    </div>
                </div>
                 <div class="absolute -z-10 top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-80 h-80 bg-primary-100 rounded-full opacity-30 blur-2xl"></div>
            </div>
        </div>
    </section>

    <!-- Testimonial -->
    <section class="bg-[#1C1C1C] text-white py-32">
        <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 lg:grid-cols-2 gap-16">
            <div>
                <h2 class="text-2xl font-serif mb-12">What founders are saying</h2>
                <h3 class="text-5xl md:text-7xl font-serif leading-tight">Finally,<br>consistency<br>without<br>friction.</h3>
            </div>
            <div class="flex flex-col justify-end">
                <p class="text-gray-400 text-lg leading-relaxed mb-8">
                    "I've tried every habit app. They all wanted me to journal, reflect, and optimize. HabitStackr just lets me check in and move on. The streak visibility keeps me honest, and seeing my group show up daily creates just enough pressure without being annoying. It's the only system that's stuck."
                </p>
                <div>
                    <p class="font-bold">Sarah Chen</p>
                    <p class="text-sm text-gray-500">Founder, indie hacker</p>
                </div>
                <div class="mt-12 flex justify-end">
                    <button class="text-white hover:opacity-70 transition-opacity">
                        <svg width="48" height="24" viewBox="0 0 50 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M0 12H48M48 12L38 2M48 12L38 22" />
                        </svg>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Share Section -->
    <section class="py-32 bg-[#FCFAF7] relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
            <div class="relative z-10">
                <p class="text-3xl font-serif leading-relaxed mb-8 max-w-md">
                    Join the invite-driven community. Find accountability partners who show up daily.
                </p>
                <AppButtons />
            </div>
            <div class="flex justify-center relative z-10">
                 <PhoneMockup>
                     <div class="flex flex-col items-center justify-center h-full bg-white p-6">
                         <h1 class="text-4xl font-serif mb-2">HabitStackr</h1>
                         <p class="text-xs text-gray-500 uppercase tracking-widest">Daily habits, made inevitable</p>
                         <div class="mt-8 w-full max-w-[200px]">
                             <div class="bg-gray-50 rounded-lg p-4 text-center">
                                 <div class="text-sm text-gray-600 mb-2">You've been invited to join</div>
                                 <div class="text-lg font-bold">Founder Circle</div>
                             </div>
                         </div>
                     </div>
                 </PhoneMockup>
            </div>
        </div>
        <!-- Divider Line -->
        <div class="absolute top-1/2 left-0 w-full h-px bg-gray-200 -z-0"></div>
    </section>

    <!-- Footer -->
    <footer class="pt-24 pb-12 px-6">
        <div class="max-w-7xl mx-auto flex flex-col items-center text-center">
            <div class="mb-16">
                <!-- Big Logo -->
                 <div class="relative inline-block">
                    <span class="text-[120px] md:text-[180px] font-serif leading-none">HabitStackr</span>
                 </div>
                 <p class="text-sm text-gray-500 mt-4 uppercase tracking-widest">Daily habits, made inevitable</p>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 mb-16 text-sm text-gray-600">
                <div class="flex flex-col gap-3 text-left md:text-center">
                    <span class="font-bold text-gray-900 uppercase tracking-widest text-xs mb-2">Product</span>
                    <a href="#">How it works</a>
                    <a href="#">Principles</a>
                    <a href="#">Pricing</a>
                </div>
                <div class="flex flex-col gap-3 text-left md:text-center">
                    <span class="font-bold text-gray-900 uppercase tracking-widest text-xs mb-2">Community</span>
                    <a href="#">Join waitlist</a>
                    <a href="#">For founders</a>
                </div>
                 <div class="flex flex-col gap-3 text-left md:text-center">
                    <span class="font-bold text-gray-900 uppercase tracking-widest text-xs mb-2">Company</span>
                    <a href="#">About</a>
                    <a href="#">Contact</a>
                </div>
                 <div class="flex flex-col gap-3 text-left md:text-center">
                    <span class="font-bold text-gray-900 uppercase tracking-widest text-xs mb-2">Legal</span>
                    <a href="#">Terms</a>
                    <a href="#">Privacy</a>
                </div>
            </div>

            <div class="flex flex-col md:flex-row items-center justify-between w-full border-t border-gray-200 pt-12 gap-8">
                <div class="text-xs text-gray-400">
                    © 2024 HabitStackr
                </div>
                <div class="flex gap-6">
                    <!-- Social Icons -->
                    <a href="#" class="w-5 h-5 bg-gray-300 rounded-full"></a>
                    <a href="#" class="w-5 h-5 bg-gray-300 rounded-full"></a>
                    <a href="#" class="w-5 h-5 bg-gray-300 rounded-full"></a>
                </div>
                <div>
                     <AppButtons />
                </div>
            </div>
        </div>
    </footer>
</div>

<style>
    /* Custom stroke text utility */
    .stroke-text {
        -webkit-text-stroke: 1px rgba(255, 255, 255, 0.5);
        color: transparent;
    }
</style>

