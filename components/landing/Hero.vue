<template>
  <main class="grid lg:grid-cols-2 place-items-center pt-16 pb-8 md:pt-8">
    <div class="p-24 md:order-1 hidden md:block">
      <img
        class="rounded-full transition-transform transform hover:scale-125"
        src="~/assets/img/hero.jpg"
        alt="Starship starts the engine"
        loading="eager"
        format="avif"
        width="512"
        height="512"
      />
    </div>

    <div>
      <h1 class="text-5xl lg:text-6xl xl:text-7xl font-bold lg:tracking-tight">
        Content creation done Right 
      </h1>
      <p class="text-lg mt-4 text-slate-600 max-w-xl">
        "startupname" is a tool for content creation assistance based on intelligent models that keep up with the trends
        .<wbr /> Built by professionnels in the field. You can quickly
        optimise your work and create a large impact on the internet.
      </p>
      <div class="mt-6 flex flex-col sm:flex-row gap-3">
        <LandingLink
          href="/video"
          rel="noopener"
          >Get Started</LandingLink
        >
       
      </div>
    </div>
  </main>
</template>
