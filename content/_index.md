---
title: Get Strategiq
layout: hextra-home
---
<div style="position: fixed; inset: 0; z-index: -1; pointer-events: none;">
    <svg width="100vw" height="100vh" style="width:100vw; height:100vh; display:block;" xmlns="http://www.w3.org/2000/svg">
        <defs>
            <radialGradient id="sphere-gradient" cx="50%" cy="50%" r="50%">
                <stop offset="0%" stop-color="#FFD166" stop-opacity="0.25"/>
                <stop offset="40%" stop-color="#06D6A0" stop-opacity="0.18"/>
                <stop offset="70%" stop-color="#118AB2" stop-opacity="0.10"/>
                <stop offset="100%" stop-color="#073B4C" stop-opacity="0"/>
            </radialGradient>
            <filter id="sphere-glow" x="-50%" y="-50%" width="200%" height="200%">
                <feGaussianBlur stdDeviation="80" result="blur"/>
                <feMerge>
                    <feMergeNode in="blur"/>
                    <feMergeNode in="SourceGraphic"/>
                </feMerge>
            </filter>
        </defs>
        <g>
            <animateTransform attributeName="transform"
                type="translate"
                from="0 0"
                to="180 80"
                dur="20s"
                repeatCount="indefinite"
                keyTimes="0;0.5;1"
                values="0 0; 200 500; 0 0"/>
            <circle cx="50%" cy="50%" r="500" fill="url(#sphere-gradient)" filter="url(#sphere-glow)"/>
        </g>
    </svg>
</div>




<div class="hx:mt-6 hx:mb-6">
{{< hextra/hero-headline >}}
<span style="background: linear-gradient(90deg, #118AB2 0%, #06D6A0 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; color: transparent;">
    B2B Marketing Consulting &nbsp;<br class="hx:sm:block hx:hidden" />for IT founders and tech teams.
{{< /hextra/hero-headline >}}
</span>
</div>

<div class="hx:mb-12">
{{< hextra/hero-subtitle >}}
  Start building awareness and generating leads.<br class="hx:sm:block hx:hidden" /> 
{{< /hextra/hero-subtitle >}}
</div>

<div class="hx:mb-12">
{{< hextra/hero-button text="Let's Talk" link="contact" >}}
</div>




{{< hextra/feature-grid >}}
  {{< hextra/feature-card
    icon="puzzle"
    title="Marketing Strategy"
    subtitle="Precise, no BS strategy to define your target audience, and to build a crystal clear marketing plan to drive awareness and leads."
    class="hx:aspect-auto"
    style="background: radial-gradient(ellipse at 30% 80%,rgba(194,97,254,0.15),hsla(0,0%,100%,0));"
  >}}

  {{< hextra/feature-card
    icon="document-text"
    title="Content Strategy"
    subtitle="Build confidence at your target accounts with content designed to educate and inform everyone in the buying process."
    style="background: radial-gradient(ellipse at 50% 50%,rgba(194,97,254,0.15),hsla(0,0%,100%,0));"
  >}}

  {{< hextra/feature-card
    icon="at-symbol"
    title="Advanced Email Marketing"
    subtitle="Deep email audit, advanced setup and execution so your emails land in your contact's inbox for conversations."
    class="hx:aspect-auto"
    style="background: radial-gradient(ellipse at 80% 50%,rgba(194,97,254,0.15),hsla(0,0%,100%,0));"
  >}}

  {{< hextra/feature-card
    icon="lightning-bolt"
    title="Marketing Execution"
    subtitle="Highly organized and transparent execution of your marketing projects with end-to-end project management and weekly reporting."
    class="hx:aspect-auto"
    style="background: radial-gradient(ellipse at 30% 80%,rgba(194,97,254,0.15),hsla(0,0%,100%,0));"
  >}}


  {{< hextra/feature-card
    icon="terminal"
    title="Martech Consulting"
    subtitle="Selecting, evaluating and deploying the best marketing technology for your needs."
    class="hx:aspect-auto"
    style="background: radial-gradient(ellipse at 50% 50%,rgba(194,97,254,0.15),hsla(0,0%,100%,0));"
  >}}

  {{< hextra/feature-card
    icon="filter"
    title="Sales Enablement"
    subtitle="Supporting your sales by building sales funnels, emails, assets and content for all stages of your lead's journey."
    class="hx:aspect-auto"
    style="background: radial-gradient(ellipse at 80% 50%,rgba(194,97,254,0.15),hsla(0,0%,100%,0));"
  >}}

  {{< hextra/feature-card
    icon="sparkles"
    title="LinkedIn Personal Branding"
    subtitle="Positioning you as a leader in your space on LinkedIn to attract the right opportunities via our proprietary methodology."
    class="hx:aspect-auto hx:md:aspect-[1.1/1] hx:max-md:min-h-[340px]"
    image="images/linkedin-personal-branding.webp"
    imageClass="hx:top-[40%] hx:left-[36px] hx:w-[110%] hx:sm:w-[110%] hx:dark:opacity-80"
    style="background: radial-gradient(ellipse at 50% 80%,rgba(221,210,59,0.15),hsla(0,0%,100%,0));"
  >}}

  {{< hextra/feature-card
    icon="play"
    title="Full-service YouTube"
    subtitle="Engage, discover and hook your audience with long and short videos backed by years of storyboarding and editing."
    class="hx:aspect-auto hx:md:aspect-[1.1/1] hx:max-md:min-h-[340px]"
    image="images/youtube-users.webp"
    imageClass="hx:top-[40%] hx:left-[36px] hx:w-[110%] hx:sm:w-[110%] hx:dark:opacity-80"
    style="background: radial-gradient(ellipse at 50% 80%,rgba(221,210,59,0.15),hsla(0,0%,100%,0));"
  >}}

    {{< hextra/feature-card
    icon="academic-cap"
    title="Marketing Coaching"
    subtitle="Fast-track, intensive marketing coaching for B2B marketers who are responsible for your success."
    class="hx:aspect-auto hx:md:aspect-[1.1/1] hx:max-md:min-h-[340px]"
    image="images/marketing-coaching.webp"
    imageClass="hx:top-[40%] hx:left-[36px] hx:w-[110%] hx:sm:w-[110%] hx:dark:opacity-80"
    style="background: radial-gradient(ellipse at 50% 80%,rgba(221,210,59,0.15),hsla(0,0%,100%,0));"
  >}}
{{< /hextra/feature-grid >}}




<div class="hx:mt-12 hx:mb-12"></div>
<div class="hx:mt-12 hx:mb-12"></div>


<div class="hx:grid hx:grid-cols-1 hx:md:grid-cols-2 hx:gap-8 hx:items-center hx:mb-12">
    <div class="hx:flex hx:justify-center">
        <img src="images/santosh-min.png" alt="About us illustration" class="hx:max-w-xs hx:rounded-lg hx:shadow-md" style="width:50%;" />
    </div>
    <div>
        <h2 class="hx:text-4xl hx:font-semibold hx:mb-4" style="background: linear-gradient(90deg, #118AB2 0%, #06D6A0 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; color: transparent;">About us</h2>    
        <p>
            Hi! I’m Santosh Subramanian and I am the founder of Get Strategiq. I have been a marketing generalist for over a decade with expertise in marketing strategy and deep-hands on in execution.<br/><br/> In my experience, I have seen great IT entrepreneurs and their products held back because of no marketing or poor marketing. As a computer science graduate, I aim to help builders like you go-to-market with a solid strategy backed by solid execution. <br/><br/> We can work with your team in-house or you can choose to work with our team of experts who will manage everything end-to-end.
        </p>
        <div class="hx:mt-16 hx:mb-16 hx:flex hx:flex-col">
        <h2 class="hx:text-2xl hx:font-semibold hx:mb-6">
            Backed by 14 years of experience. Trusted by Leaders.
        </h2>
        <div class="hx:overflow-hidden hx:relative hx:w-full hx:flex hx:justify-center">
            <div class="hx:whitespace-nowrap hx:animate-marquee">
                <img src="images/companies/princeton-blue.png" alt="princeton-blue" class="hx:inline-block hx:h-12 hx:mx-8" style="filter: grayscale(100%) brightness(0) invert(1);" />
                <img src="images/companies/agile-crm.png" alt="agile-crm" class="hx:inline-block hx:h-12 hx:mx-8" style="filter: grayscale(100%) brightness(0) invert(1);" />
                <img src="images/companies/rapidbizapps.png" alt="rapidbizapps" class="hx:inline-block hx:h-12 hx:mx-8" style="filter: grayscale(100%) brightness(0) invert(1);" />
                <img src="images/companies/skymap-global.png" alt="skymap-global" class="hx:inline-block hx:h-12 hx:mx-8" style="filter: grayscale(100%) brightness(0) invert(1);" />
                <!-- Repeat logos for seamless loop -->
                <img src="images/companies/princeton-blue.png" alt="princeton-blue" class="hx:inline-block hx:h-12 hx:mx-8" style="filter: grayscale(100%) brightness(0) invert(1);" />
                <img src="images/companies/agile-crm.png" alt="agile-crm" class="hx:inline-block hx:h-12 hx:mx-8" style="filter: grayscale(100%) brightness(0) invert(1);" />
                <img src="images/companies/rapidbizapps.png" alt="rapidbizapps" class="hx:inline-block hx:h-12 hx:mx-8" style="filter: grayscale(100%) brightness(0) invert(1);" />
                <img src="images/companies/skymap-global.png" alt="skymap-global" class="hx:inline-block hx:h-12 hx:mx-8" style="filter: grayscale(100%) brightness(0) invert(1);" />
            </div>
    </div>
    </div>
    </div>
</div>



<style>
@keyframes marquee {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
}
.hx\:animate-marquee {
    display: inline-block;
    min-width: 200%;
    animation: marquee 30s linear infinite;
}
</style>


<div class="hx:mt-12 hx:mb-12"></div>


{{< cards cols="3" >}}
  {{< card
    tag="CASE STUDY"
    link="/"
    title="How Princeton Blue achieved a 15x improvement in Email Open Rates"
    subtitle="Princeton Blue’s emails were landing in spam, threatening to end their campaigns. Here’s how we fixed it and restored their email marketing."
    class="hx:aspect-auto hx:md:aspect-[1.1/1] hx:max-md:min-h-[340px]"
    image="images/case-study/princetonblue-email.webp"
    imageClass="hx:top-[40%] hx:left-[36px] hx:w-[110%] hx:sm:w-[110%] hx:dark:opacity-80"
    style="background: radial-gradient(ellipse at 50% 80%,rgba(221,210,59,0.15),hsla(0,0%,100%,0));"
  >}}

  {{< card
    tag="ARTICLE"
    link="https://blog.getstrategiq.com/p/seo-is-dead-but-something-else-is-born"
    title="SEO is dead. But something else is born!"
    subtitle="Search engines are changing to answering engines. Here's how it affects your business."
    class="hx:aspect-auto hx:md:aspect-[1.1/1] hx:max-md:min-h-[340px]"
    image="images/article/seo-is-dead.webp"
    imageClass="hx:top-[40%] hx:left-[36px] hx:w-[110%] hx:sm:w-[110%] hx:dark:opacity-80"
    style="background: radial-gradient(ellipse at 50% 80%,rgba(221,210,59,0.15),hsla(0,0%,100%,0));"
  >}}

  {{< card
    tag="ARTICLE"
    link="https://blog.getstrategiq.com/p/getting-chatgpt-to-talk-about-your-business"
    title="Getting ChatGPT to talk about your business"
    subtitle="Here's how AI chatbots and search engines are reshaping digital visibility. Early strategic techniques to get your business recommended by AI."
    class="hx:aspect-auto hx:md:aspect-[1.1/1] hx:max-md:min-h-[340px]"
    image="images/article/business-chatgpt.webp"
    imageClass="hx:top-[40%] hx:left-[36px] hx:w-[110%] hx:sm:w-[110%] hx:dark:opacity-80"
    style="background: radial-gradient(ellipse at 50% 80%,rgba(221,210,59,0.15),hsla(0,0%,100%,0));"
  >}}
{{< /cards >}}




{{< cards cols="2" >}}
  {{< card
    tag="RESOURCE"
    link="/resources/email-swipe-file-landing/"
    title="The IT Marketer's Email Swipe File"
    subtitle="A collection of constantly updating templates file designed for IT founders, marketers and business development professionals."
    class="hx:aspect-auto hx:md:aspect-[1.1/1] hx:max-md:min-h-[340px]"
    image="images/resources/email-swipe-file.png"
    imageClass="hx:top-[40%] hx:left-[36px] hx:w-[110%] hx:sm:w-[110%] hx:dark:opacity-80"
    style="background: radial-gradient(ellipse at 50% 80%,rgba(221,210,59,0.15),hsla(0,0%,100%,0));"
  >}}

  {{< card
    tag="RESOURCE"
    link="/resources/ai-impact-on-search-landing/"
    title="AI's impact on Search"
    subtitle="A brief infographic for founders and marketing leaders looking to learn AI's impact on search and business discovery."
    class="hx:aspect-auto hx:md:aspect-[1.1/1] hx:max-md:min-h-[340px]"
    image="images/resources/ai-impact-search.webp"
    imageClass="hx:top-[40%] hx:left-[36px] hx:w-[110%] hx:sm:w-[110%] hx:dark:opacity-80"
    style="background: radial-gradient(ellipse at 50% 80%,rgba(221,210,59,0.15),hsla(0,0%,100%,0));"
  >}}

{{< /cards >}}







<div class="hx:mt-12 hx:mb-12"></div>

<div class="hx:mt-12 hx:mb-6">
{{< hextra/hero-headline >}}
<span style="background: linear-gradient(90deg, #118AB2 0%, #06D6A0 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; color: transparent;">
    At your service.
{{< /hextra/hero-headline >}}
</span>
</div>

<div class="hx:mb-12">
{{< hextra/hero-subtitle >}}
  I'd love to know how I can help you.<br class="hx:sm:block hx:hidden" /> Book a 30-min call at a time that's convenient for you. 
{{< /hextra/hero-subtitle >}}
</div>

<div class="hx:mb-12">
{{< hextra/hero-button text="Let's Talk" link="contact" >}}
</div>