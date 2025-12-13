<script lang="ts">
  const stats = [
    {
      label: "Grass-Fed Tallow",
      desc: "Our hero ingredient comes from grass-fed cattle, ensuring the highest quality and nutrient density. Rich in vitamins A, D, E, and K, tallow is biocompatible with human skin, absorbing deeply to restore and nourish from within. This ancestral ingredient has been trusted for generations.",
      img: "/generated/image-raw-grass-fed-beef-tallow-in-natural-bow-1765586912917-8.webp"
    },
    {
      label: "Spanish Botanicals",
      desc: "Each botanical oil is selected from Spain's rich natural heritage. Cold-pressed and minimally processed, these plant-based ingredients work in harmony with tallow to create formulations that honor both tradition and efficacy. No synthetic additives, just pure botanical wisdom.",
      img: "/generated/image-collection-of-botanical-oils-in-glass-bo-1765586915732-9.webp"
    },
    {
      label: "Flamenco Heritage",
      desc: "Based in Spain, TALLOE's identity is deeply rooted in flamenco culture. Our visual language—from terracotta palettes to commissioned botanical illustrations—reflects the passionate movement and authentic emotion of this art form. Every detail honors Spanish heritage.",
      img: "/generated/image-spanish-flamenco-dancers-hands-with-red--1765586903588-5.webp"
    },
    {
      label: "Honest Packaging",
      desc: "Dark ultraviolet-protective vessels preserve ingredient integrity. Linen-wrapped gift boxes and botanical illustration cards reflect our commitment to material simplicity. Each package is designed with intentional imperfection, echoing pressed flowers kept between pages.",
      img: "/generated/image-linen-wrapped-gift-box-with-botanical-il-1765586922464-11.webp"
    }
  ];
</script>

<section class="py-24 px-6 md:px-12 bg-white border-t border-gray-100">
  <div class="mb-16">
    <p class="text-gray-500 max-w-xl">
      What makes TALLOE different? Our commitment to ancestral ingredients, Spanish heritage, and honest formulation.
    </p>
  </div>

  <div class="space-y-16">
    {#each stats as stat}
      <div class="flex flex-col md:flex-row md:items-start justify-between gap-8 border-b border-gray-100 pb-16 last:border-0">
        <h3 class="text-2xl md:text-4xl font-medium w-full md:w-1/3">{stat.label}</h3>
        <div class="w-full md:w-1/3">
           <p class="text-xs leading-relaxed text-gray-500">{stat.desc}</p>
        </div>
        <div class="w-full md:w-1/6 flex justify-end">
           <img src={stat.img} alt={stat.label} class="w-20 h-20 object-cover rounded bg-gray-100" />
        </div>
      </div>
    {/each}
  </div>
</section>
