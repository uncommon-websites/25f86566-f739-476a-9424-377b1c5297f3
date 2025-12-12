<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[var(--color-dark)] min-h-screen flex flex-col">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Notification Pill -->
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-sm border border-white/10 rounded-full px-4 py-1.5 mb-8">
                        <span class="w-2 h-2 rounded-full bg-[var(--color-primary)]"></span>
                        <span class="text-white text-sm font-medium">Apple Certified</span>
                        <span class="text-gray-400 text-sm">UK-based experts</span>
                        <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance">
                        Transform Apple infrastructure chaos into competitive advantage.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        Proactive UK-based expert management and strategic technology leadership for London's Apple-first businesses. No more downtime, no more waiting for support.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="bg-white hover:bg-gray-100 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Get Support Now
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bg-transparent border border-white/20 hover:bg-white/10 text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            See Our Expertise
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Hero Image -->
            <div class="mt-20 relative">
                <div class="container mx-auto px-6">
                    <div class="max-w-5xl mx-auto rounded-2xl overflow-hidden shadow-2xl border border-white/10">
                        <img src="/generated/image-professional-it-support-specialist-worki-1765530217627-0.webp" alt="Professional IT support specialist managing Apple infrastructure" class="w-full h-auto" />
                    </div>
                </div>
            </div>
        </section>

        <!-- Trust Indicators -->
        <section class="py-12 border-y border-white/5 bg-black/20">
            <div class="container mx-auto px-6">
                <p class="text-center text-gray-400 text-sm mb-8">Trusted by London's leading Apple-first businesses</p>
                <div class="flex flex-wrap justify-center items-center gap-12 md:gap-16 opacity-40">
                    <div class="text-white font-semibold text-lg">Apple Consultants Network</div>
                    <div class="text-white font-semibold text-lg">Jamf Certified</div>
                    <div class="text-white font-semibold text-lg">Apple Certified Support</div>
                    <div class="text-white font-semibold text-lg">98% Retention</div>
                </div>
            </div>
        </section>

        <!-- Core Value Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <h2 class="text-[var(--color-primary)] font-mono text-xs tracking-[0.2em] uppercase mb-6">Stabilise Advantage</h2>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">Apple infrastructure management.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">Done right.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Image -->
                    <div class="rounded-3xl overflow-hidden shadow-2xl border border-white/10">
                        <img src="/generated/image-technical-expert-configuring-apple-mac-c-1765530222567-2.webp" alt="Technical expert managing Apple infrastructure" class="w-full h-auto" />
                    </div>

                    <!-- Text Content -->
                    <div class="space-y-8">
                        <h3 class="text-4xl md:text-5xl font-bold text-white tracking-tight">Proactive. Expert. UK-based.</h3>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            Traditional IT providers treat Macs as an afterthought. We're different. With certified Apple expertise and proactive management, we transform your Apple infrastructure from a liability into your competitive advantage.
                        </p>
                        <div class="flex flex-col gap-4">
                            <div class="flex items-center gap-3">
                                <div class="w-10 h-10 rounded-full bg-[var(--color-primary)]/20 flex items-center justify-center flex-shrink-0">
                                    <svg class="w-5 h-5 text-[var(--color-primary)]" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                                </div>
                                <span class="text-white">98% client retention rate</span>
                            </div>
                            <div class="flex items-center gap-3">
                                <div class="w-10 h-10 rounded-full bg-[var(--color-primary)]/20 flex items-center justify-center flex-shrink-0">
                                    <svg class="w-5 h-5 text-[var(--color-primary)]" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                                </div>
                                <span class="text-white">Apple Certified Support Professionals</span>
                            </div>
                            <div class="flex items-center gap-3">
                                <div class="w-10 h-10 rounded-full bg-[var(--color-primary)]/20 flex items-center justify-center flex-shrink-0">
                                    <svg class="w-5 h-5 text-[var(--color-primary)]" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                                </div>
                                <span class="text-white">Based in London, supporting London businesses</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- White Section -->
        <div class="bg-[#F9FAFB] text-black rounded-t-[4rem] relative z-20 mt-[-2rem] pt-32 pb-32">
            <div class="container mx-auto px-6">
                <!-- Header -->
                <div class="max-w-4xl mb-24">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="h-px w-12 bg-gray-300"></div>
                        <span class="text-gray-500 font-mono text-xs tracking-[0.2em] uppercase">Our Services</span>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">Enterprise-grade Apple infrastructure.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">For businesses that can't afford downtime.</h2>
                    
                    <a href="#" class="inline-flex items-center gap-2 text-sm font-semibold border-b border-black pb-0.5 hover:text-gray-600 transition-colors">
                        Explore our services
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>

                <!-- Features Grid -->
                <div class="flex flex-col lg:flex-row gap-12">
                    <!-- Sidebar Navigation (Sticky) -->
                    <div class="hidden lg:block w-64 flex-shrink-0">
                        <div class="sticky top-32 space-y-4">
                            <div class="flex items-center gap-2 text-sm font-semibold text-black border-l-2 border-black pl-4 py-1">
                                <span class="w-1.5 h-1.5 rounded-full bg-[var(--color-primary)]"></span>
                                Device Management
                            </div>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Proactive Support</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Security & Compliance</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Strategic Planning</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Onboarding</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Training</a>
                        </div>
                    </div>

                    <!-- Feature Cards -->
                    <div class="flex-grow space-y-8">
                        <FeatureRow 
                            title="Device Management" 
                            description="Zero-touch deployment and centralized control. We manage your entire Apple fleet with enterprise MDM, ensuring every device is secure, configured, and ready from day one."
                            icon="lock"
                            image="collateral"
                        />
                         <FeatureRow 
                            title="Proactive Support" 
                            description="Problems solved before you notice them. Our UK-based team monitors your infrastructure 24/7, identifying and resolving issues before they impact your business."
                            icon="connect"
                            image="connect"
                        />
                         <FeatureRow 
                            title="Security & Compliance" 
                            description="Enterprise security without the complexity. We implement and maintain security policies that protect your data while keeping your team productive."
                            icon="guard"
                            image="guard"
                        />
                         <FeatureRow 
                            title="Strategic Planning" 
                            description="Technology roadmap aligned with business goals. We help you plan upgrades, expansions, and technology investments that drive competitive advantage."
                            icon="lab"
                            image="lab"
                        />
                         <FeatureRow 
                            title="Seamless Onboarding" 
                            description="New hires productive from day one. Automated provisioning ensures every new team member has the right access, apps, and configuration immediately."
                            icon="preview"
                            image="preview"
                        />
                         <FeatureRow 
                            title="Expert Training" 
                            description="Maximize your Apple investment. We train your team on best practices, productivity tools, and security awareness tailored to your business needs."
                            icon="data"
                            image="data"
                        />
                    </div>
                </div>

                <!-- Why Choose Section -->
                <div class="mt-32 text-center max-w-4xl mx-auto mb-24">
                    <div class="w-24 h-24 mx-auto bg-gradient-to-br from-[var(--color-primary)]/20 to-[var(--color-primary)]/10 rounded-full flex items-center justify-center mb-8 relative">
                        <div class="absolute inset-0 bg-[var(--color-primary)]/10 blur-xl rounded-full"></div>
                        <svg class="w-10 h-10 text-[var(--color-primary)] relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        Built for London businesses who need Apple infrastructure that just works.
                    </h2>
                    <p class="text-gray-600 text-lg mb-8">
                        Traditional IT providers don't understand Macs. We're Apple-first, certified experts who treat your infrastructure with the care it deserves.
                    </p>
                    <button class="bg-white border border-gray-200 hover:border-gray-400 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2 mx-auto">
                        See our certifications
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
                </div>

                <!-- Trusted By Section -->
                <div class="mb-32">
                    <p class="text-xl text-gray-500 mb-12">Trusted by London's Apple-first businesses.</p>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <!-- Main Testimonial Card -->
                        <div class="md:col-span-2 bg-[#0A0A0A] rounded-3xl p-10 relative overflow-hidden group min-h-[400px] flex flex-col justify-between">
                            <div class="absolute inset-0 opacity-30">
                                <img src="/generated/image-confident-business-owner-smiling-in-mode-1765530220572-1.webp" alt="Happy customer" class="w-full h-full object-cover" />
                            </div>
                            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/80 to-black/40"></div>
                            
                            <div class="relative z-10">
                                <svg class="w-12 h-12 text-[var(--color-primary)] mb-6" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M14.017 21v-7.391c0-5.704 3.731-9.57 8.983-10.609l.995 2.151c-2.432.917-3.995 3.638-3.995 5.849h4v10h-9.983zm-14.017 0v-7.391c0-5.704 3.748-9.57 9-10.609l.996 2.151c-2.433.917-3.996 3.638-3.996 5.849h3.983v10h-9.983z"/>
                                </svg>
                                <p class="text-white text-2xl font-medium mb-6 leading-relaxed">
                                    "Before Stabilise, we were constantly dealing with Mac issues. Now our team is productive, and I can focus on growing the business instead of IT problems."
                                </p>
                            </div>
                            <div class="relative z-10">
                                <div class="text-white font-semibold text-lg">Sarah Mitchell</div>
                                <div class="text-gray-400">Operations Director, Creative Agency</div>
                            </div>
                        </div>

                        <!-- Smaller Cards -->
                        <div class="space-y-6">
                            <!-- Card 2 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-[var(--color-primary)]/20 to-black"></div>
                                <div class="relative z-10">
                                    <div class="text-[var(--color-primary)] text-4xl font-bold mb-2">98%</div>
                                    <div class="text-white text-sm">Client retention rate</div>
                                </div>
                            </div>
                            <!-- Card 3 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-blue-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <div class="text-white text-4xl font-bold mb-2">&lt;15min</div>
                                    <div class="text-gray-400 text-sm">Average response time</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Banner -->
                <div class="bg-[#0A0A0A] rounded-3xl p-12 md:p-20 relative overflow-hidden mb-32 text-center">
                    <div class="absolute inset-0 bg-[url('/grid-pattern.svg')] opacity-10"></div>
                    <div class="absolute left-0 top-0 w-64 h-64 bg-[var(--color-primary)]/10 blur-[100px] rounded-full"></div>
                    <div class="absolute right-0 bottom-0 w-64 h-64 bg-blue-500/10 blur-[100px] rounded-full"></div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Ready to stabilise your Apple infrastructure? <span class="text-[var(--color-primary)]">Let's talk.</span>
                        </h2>
                        <p class="text-gray-400 mb-10">
                            Join London's leading businesses who trust Stabilise for their Apple IT infrastructure. Get a free consultation and see how we can transform your technology operations.
                        </p>
                        <button class="bg-white hover:bg-gray-100 text-black px-8 py-3 rounded-full font-medium transition-colors flex items-center gap-2 mx-auto">
                            Schedule Consultation
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>

                <!-- Technology Partners -->
                <div class="text-center mb-32">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                        Apple ecosystem experts.<br>
                        <span class="text-gray-400">Certified in the tools that matter.</span>
                    </h2>
                    <p class="text-gray-600 mb-12">We're certified and partnered with the leading Apple management platforms</p>

                    <div class="grid grid-cols-2 md:grid-cols-4 gap-px bg-gray-200 border border-gray-200 rounded-2xl overflow-hidden">
                        {#each ['Jamf', 'Mosyle', 'Kandji', 'Apple', 'Microsoft 365', 'Google Workspace', 'Okta', 'Slack'] as logo}
                        <div class="bg-[#F9FAFB] p-12 flex items-center justify-center grayscale opacity-60 hover:grayscale-0 hover:opacity-100 transition-all duration-300">
                            <span class="font-bold text-xl uppercase tracking-wider">{logo}</span>
                        </div>
                        {/each}
                    </div>
                </div>

                <!-- Founders Section -->
                <div class="mb-12">
                    <h2 class="text-4xl font-bold text-gray-900 mb-4">Meet the team behind Stabilise.</h2>
                    <p class="text-gray-600 text-lg mb-12">Founded by Apple experts who experienced the frustration of poor Mac support firsthand.</p>
                    
                    <div class="grid md:grid-cols-2 gap-8">
                        <!-- Founder 1 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gray-200 rounded-3xl aspect-[4/3] mb-6 relative overflow-hidden">
                                <img src="/generated/image-two-co-founders-in-casual-business-attir-1765530224616-3.webp" alt="Alan Avins and Dustin Rhodes" class="w-full h-full object-cover" />
                            </div>
                            <div class="mb-2">
                                <h3 class="text-2xl font-bold text-gray-900">Alan Avins</h3>
                                <div class="text-[var(--color-primary)] font-medium">Technical Co-founder</div>
                            </div>
                            <p class="text-gray-600">Alan's deep Apple technical expertise and certifications position him to build enterprise-grade Mac infrastructure that traditional IT providers overlook.</p>
                        </div>
                        <!-- Founder 2 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gray-200 rounded-3xl aspect-[4/3] mb-6 relative overflow-hidden">
                                <img src="/generated/image-happy-small-business-team-working-togeth-1765530226590-4.webp" alt="Dustin Rhodes" class="w-full h-full object-cover" />
                            </div>
                            <div class="mb-2">
                                <h3 class="text-2xl font-bold text-gray-900">Dustin Rhodes</h3>
                                <div class="text-[var(--color-primary)] font-medium">CEO & Co-founder</div>
                            </div>
                            <p class="text-gray-600">Dustin experienced frustration with impersonal IT support, driving his mission to humanize technology partnerships through authentic client relationships.</p>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

