<script lang="ts">
  const steps = [
    {
      num: "01",
      title: "Browse & choose",
      desc: "Select your desired leg height, finish, and rod configuration from our extensive range.",
      img: "/generated/image-collection-of-hairpin-legs-in-various-fi-1765529045532-4.webp"
    },
    {
      num: "02",
      title: "Order online",
      desc: "Place your order through our secure checkout. Orders before 2PM ship same day.",
      img: "/generated/image-various-hairpin-table-legs-in-different--1765529164565-3.webp"
    },
    {
      num: "03",
      title: "Receive & install",
      desc: "Your legs arrive with screws, feet, and installation guide. Only a screwdriver needed.",
      img: "/generated/image-person-assembling-furniture-with-hairpin-1765529157273-0.webp"
    },
    {
      num: "04",
      title: "Enjoy your creation",
      desc: "Transform your space with custom furniture that's built to last. Backed by our 5-year guarantee.",
      img: "/generated/image-modern-minimalist-dining-table-with-slee-1765529036389-0.webp"
    }
  ];
</script>

<section class="bg-white py-24 px-6">
  <div class="max-w-[1200px] mx-auto">
    <h2 class="text-[40px] leading-tight font-light text-gray-900 mb-16 max-w-[600px]">
      Get your hairpin legs in four simple steps. Same-day shipping available.
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-16">
      {#each steps as step}
        <div class="flex flex-col">
          <div class="bg-black text-white text-xs font-bold w-8 h-8 flex items-center justify-center rounded mb-6">
            {step.num}
          </div>
          <h3 class="text-xl font-normal mb-2">{step.title}</h3>
          <p class="text-gray-500 text-sm leading-relaxed mb-6 min-h-[80px]">{step.desc}</p>
          <div class="rounded-xl overflow-hidden h-[200px] bg-gray-100">
            <img src={step.img} alt={step.title} class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-500" />
          </div>
        </div>
      {/each}
    </div>

    <div class="bg-[#f9f9f7] rounded-2xl p-12 flex flex-col md:flex-row items-center justify-between gap-8">
      <div>
        <h3 class="text-2xl font-light mb-2">Need installation help?</h3>
        <p class="text-gray-500 text-sm">View our comprehensive installation guides and tips.</p>
      </div>
      <div class="flex gap-4">
        <button class="px-6 py-3 bg-white border border-gray-200 hover:bg-gray-50 rounded-lg text-sm font-medium transition-colors">
          Installation guide
        </button>
        <button class="px-6 py-3 bg-[oklch(0.696_0.17_162.48)] hover:bg-[oklch(0.596_0.145_163.225)] text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
          Download catalog
        </button>
      </div>
    </div>
  </div>
</section>
