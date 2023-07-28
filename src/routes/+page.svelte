<script>
  import { eng } from "$lib";
  import ramMemory from "$lib/assets/RamMemory.png";
  import masterJustLogo from "$lib/assets/masterJustLogo.svg";
</script>

<div class="w-screen">
  <div class="hero my-24">
    <div class="hero-content flex-col lg:flex-row-reverse">
      <img
        src={masterJustLogo}
        alt="alt"
        class="max-sm:max-h-40 filter drop-shadow-2xl max-w-md"
      />
      <div>
        <h1
          class="m-auto max-w-xl p-2 text-7xl text-transparent bg-clip-text font-bold bg-gradient-to-br from-[hsl(var(--bc))] to-yellow-600 text-center"
        >
          DEVELOPING ELETRONICS TOGETHER
        </h1>
      </div>
    </div>
  </div>
  <div class="hero my-24">
    <div class="hero-content flex-col lg:flex-row">
      <iframe
        title="placeholder"
        width="500"
        height="315"
        src="https://www.youtube.com/embed/tgbNymZ7vqY"
      />
      <div class="flex flex-col place-items-center">
        <h1
          class="m-auto max-w-xl p-2 text-4xl text-transparent bg-clip-text font-bold bg-gradient-to-br from-[hsl(var(--bc))] to-yellow-600 text-center"
        >
          Conheça nosso conteúdo no Youtube
        </h1>
        <div class="m-auto max-w-xl p-2">
          Em parceria com a <a href="https://www.nuvoton.com/" class="link-hover link-info">Nuvoton</a>, a Mastertronics traz alg algo placeholder plac eholder placeho lderplacehol derplaceholderplaceholderp laceholderplaceholderplaceholderplaceholderplaceholderplaceholder placeholderplaceholderplaceholder placeholderplaceholder
        </div> 
        <a href="google.com">
          <button class="m-auto btn btn-secondary">
            acesse o site
          </button>
        </a>
      </div>
    </div>
  </div>
  <!-- <div class="hero my-24">
    <div class="hero-content flex-col lg:flex-row-reverse">
      <img src={masterJustLogo} alt="alt" class="max-sm:max-h-40" />
      <div>
        <h1
          class="m-auto max-w-xl p-2 text-7xl text-transparent bg-clip-text font-bold bg-gradient-to-br from-[hsl(var(--bc))] to-yellow-600 text-center"
        >
          DEVELOPING ELETRONICS TOGETHER
        </h1>
      </div>
    </div>
  </div> -->
</div>
