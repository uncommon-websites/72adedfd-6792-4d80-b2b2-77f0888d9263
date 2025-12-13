<script lang="ts">
  const photos = [
    {
      title: "Deep Nourishment",
      desc: "Grass-fed tallow penetrates deeply, delivering vitamins and nutrients where your skin needs them most.",
      img: "/generated/image-raw-grass-fed-beef-tallow-in-natural-bow-1765586912917-8.webp"
    },
    {
      title: "Botanical Harmony",
      desc: "Spanish botanicals work synergistically with tallow, creating balanced formulations that respect your skin's natural rhythms.",
      img: "/generated/image-collection-of-botanical-oils-in-glass-bo-1765586915732-9.webp"
    },
    {
      title: "Radiant Results",
      desc: "Experience skin that feels fluid, nourished, and alive—the natural outcome of ancestral ingredients working in harmony.",
      img: "/generated/image-woman-with-natural-glowing-skin-touching-1765586918782-10.webp"
    }
  ];
</script>

<section class="py-24 px-6 md:px-12 bg-white">
  <div class="max-w-xl mb-16">
    <h3 class="text-lg font-bold mb-2">Why tallow works where synthetics fail.</h3>
    <p class="text-gray-500 text-sm leading-relaxed">
      Modern skincare often relies on synthetic ingredients that sit on the surface. TALLOE returns to what actually works—biocompatible fats that your skin recognizes and absorbs, paired with botanicals that have nourished skin for centuries.
    </p>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
    {#each photos as photo}
      <div>
        <div class="aspect-[3/4] rounded-lg overflow-hidden mb-4 bg-gray-100">
          <img src={photo.img} alt={photo.title} class="w-full h-full object-cover" />
        </div>
        <h4 class="text-xs font-bold mb-1">{photo.title}</h4>
        <p class="text-[10px] text-gray-500 leading-relaxed">{photo.desc}</p>
      </div>
    {/each}
  </div>
</section>
