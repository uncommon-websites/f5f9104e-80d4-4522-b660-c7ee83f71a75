<script lang="ts">
  const images = [
    "/generated/image-close-up-of-precision-welded-steel-hairp-1765529039448-1.webp",
    "/generated/image-mid-century-modern-coffee-table-with-cop-1765529041750-2.webp",
    "/generated/image-person-assembling-furniture-with-hairpin-1765529157273-0.webp"
  ];
</script>

<section class="bg-white pb-24 overflow-hidden">
  <div class="flex gap-4 overflow-x-auto px-6 pb-8 snap-x">
    {#each images as img}
      <div class="min-w-[80vw] md:min-w-[60vw] lg:min-w-[45vw] h-[400px] snap-center first:pl-0">
        <img src={img} alt="Hairpin legs and furniture" class="w-full h-full object-cover rounded-lg" />
      </div>
    {/each}
  </div>
  
  <div class="text-center mt-4">
    <p class="text-gray-500 text-sm mb-4">Classic Hairpin Legs <span class="text-gray-400">10mm • 2-rod design</span></p>
    <div class="flex justify-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-gray-800"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
    </div>
  </div>
</section>
