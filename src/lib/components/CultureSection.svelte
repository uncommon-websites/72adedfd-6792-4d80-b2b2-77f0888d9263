<script lang="ts">
  const cards = [
    {
      title: "Movement & Vitality",
      subtitle: "Like Flamenco's Fluid Grace",
      image: "/generated/image-spanish-flamenco-dancers-hands-with-red--1765586903588-5.webp"
    },
    {
      title: "Natural Beauty",
      subtitle: "Wild Spanish Botanicals",
      image: "/generated/image-wild-spanish-flowers-and-botanicals-in-n-1765586906388-6.webp"
    },
    {
      title: "Intentional Imperfection",
      subtitle: "Like Pressed Flowers Between Pages",
      image: "/generated/image-pressed-botanical-flowers-and-herbs-on-l-1765586909530-7.webp"
    }
  ];
</script>

<section class="py-24 px-6 md:px-12 bg-white">
  <div class="max-w-2xl mb-16">
    <p class="text-xl md:text-2xl leading-relaxed text-gray-800">
      Rooted in Spain's flamenco heritage, TALLOE's visual language mirrors the movement of red fabric—a promise of skin that feels fluid, nourished, alive. Our identity celebrates passionate authenticity.
    </p>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
    {#each cards as card}
      <div class="group">
        <div class="aspect-[4/3] overflow-hidden rounded-lg mb-4 bg-gray-100">
          <img src={card.image} alt={card.title} class="w-full h-full object-cover transition-all duration-500 group-hover:scale-105" />
        </div>
        <h3 class="text-sm text-gray-500 mb-1">{card.title}</h3>
        <p class="text-sm font-bold">{card.subtitle}</p>
        
        <div class="flex justify-between mt-4 text-xs text-gray-400">
           <span>Heritage</span>
           <span>→</span>
        </div>
      </div>
    {/each}
  </div>
</section>
