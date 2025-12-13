<script lang="ts">
  const products = [
    {
      name: "Tallow Face Balm",
      desc: "Deep nourishment from grass-fed tallow and botanical oils.",
      bg: "bg-gray-50",
      img: "/generated/image-dark-glass-skincare-jar-with-tallow-crea-1765586891214-1.webp",
      dark: false
    },
    {
      name: "Botanical Tallow Cream",
      desc: "Ancestral ingredients meet Spanish botanical tradition.",
      bg: "bg-gray-100",
      img: "/generated/image-grass-fed-tallow-balm-in-ultraviolet-gla-1765586894104-2.webp",
      dark: false
    },
    {
      name: "Nourishing Face Oil",
      desc: "Pure botanical oils in harmony with your skin.",
      bg: "bg-[#f5e6dc]",
      img: "/generated/image-skincare-serum-bottle-with-botanical-oil-1765586897017-3.webp",
      dark: false
    },
    {
      name: "Body Tallow Balm",
      desc: "Fluid, nourished skin from head to toe.",
      bg: "bg-gray-50",
      img: "/generated/image-close-up-of-womans-hands-applying-natura-1765586900658-4.webp",
      dark: false
    }
  ];
</script>

<section class="px-6 md:px-12 py-24 bg-white">
  <div class="max-w-3xl mb-16">
    <h2 class="text-2xl md:text-3xl font-medium leading-tight">
      <span class="font-bold">Material simplicity meets ancestral wisdom.</span> Each product returns to traditional ingredients—grass-fed tallow and botanical oils—for honest skincare that truly nourishes.
    </h2>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-2 gap-x-6 gap-y-12">
    {#each products as product}
      <div class="group cursor-pointer">
        <div class={`aspect-[4/3] w-full rounded-lg overflow-hidden relative ${product.bg} mb-4`}>
          <img src={product.img} alt={product.name} class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" />
        </div>
        <h3 class="text-sm font-bold mb-1">{product.name}</h3>
        <p class="text-sm text-gray-600">{product.desc}</p>
      </div>
    {/each}
  </div>
</section>
