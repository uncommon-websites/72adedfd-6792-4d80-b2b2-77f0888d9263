<script lang="ts">
  export let title: string = "TALLOE";
</script>

<header class="fixed top-0 left-0 w-full z-50 px-6 py-6 flex justify-between items-start text-white mix-blend-difference">
  <div class="flex items-center gap-3">
    <svg width="24" height="35" viewBox="0 0 59 87" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
      <path d="M56.5713 31.8963L14.8989 81.1963C14.145 82.0882 12.7346 81.1849 13.2294 80.127L28.4752 47.5332C28.8075 46.8228 28.2299 46.0238 27.4511 46.1166L2.56115 49.0829C1.71899 49.1832 1.1421 48.2556 1.60456 47.5446L32.2362 0.454721C32.4207 0.171095 32.7361 0 33.0745 0H52.2062C53.0308 0 53.501 0.941991 53.0054 1.60106L30.5002 31.5251C29.9714 32.2282 30.5428 33.2223 31.4165 33.1193L55.6905 30.2576C56.5915 30.1514 57.157 31.2034 56.5713 31.8963Z" fill="currentColor"/>
    </svg>
    <span class="text-2xl font-bold tracking-tighter">{title}</span>
  </div>
  <div class="text-right text-xs font-medium leading-tight opacity-90">
    <p>Ancestral skincare.</p>
    <p class="opacity-70">Rooted in flamenco heritage.</p>
  </div>
</header>
