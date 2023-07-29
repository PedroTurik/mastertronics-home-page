<script>
  import masterJustLogo from "$lib/assets/masterJustLogo.svg";
</script>

<div class="w-screen">
  <section
    class="relative flex flex-col items-center min-h-[400px] py-24 px-[20vw]"
  >
    <div class="z-10 hero-content flex-col lg:flex-row-reverse">
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
    <div class="curve absolute h-[225px] w-[100%] bottom-0" />
  </section>
  <section
    class="bg-[#dede44] relative flex flex-col items-center min-h-[400px] py-24 px-[20vw]"
  >
    <div class="mt-10 hero-content flex-col lg:flex-row translate-y-7">
      <div class="flex flex-col place-items-center">
        <h1
          class="m-auto max-w-xl p-2 text-4xl text-transparent bg-clip-text font-bold bg-gradient-to-br from-[hsl(var(--sc))] to-yellow-600 text-center"
        >
          Conheça nosso conteúdo no Youtube
        </h1>
        <div class="m-auto max-w-xl p-2">
          Em parceria com a <a
            href="https://www.nuvoton.com/"
            class="link-hover link-info">Nuvoton</a
          >, a Mastertronics traz alg algo placeholder plac eholder placeho
          lderplacehol derplaceholderplaceholderp
          laceholderplaceholderplaceholderplaceholderplaceholderplaceholder
          placeholderplaceholderplaceholder placeholderplaceholder
        </div>
        <a href="google.com">
          <button class="m-auto btn btn-secondary"> acesse o site </button>
        </a>
      </div>
      <iframe
        title="placeholder"
        width="500"
        height="315"
        src="https://www.youtube.com/embed/tgbNymZ7vqY"
      />
    </div>
  </section>
  <div class="spacer" />

  <section
    class="bg-[#7f8082] relative flex flex-col items-center min-h-[400px] py-20 px-[20vw]"
  >
    <div class="z-10 flex-col lg:flex-row-reverse">
      <div>
        <h1
          class="m-auto mb-10 max-w-xl p-2 text-4xl text-transparent bg-clip-text font-bold bg-gradient-to-br from-[hsl(var(--nc))] to-yellow-600 text-center"
        >
          Leia Nossos Artigos
        </h1>
      </div>
      <div class="overflow-x-auto">
        <table class="table bg-neutral-focus">
          <tbody>
            <!-- row 1 -->
            <tr>
              <td>something about some thing or some other thing</td>
              <td>00/00/2000</td>
              <td
                ><button
                  class="hover:scale-105 hover:bg-neutral btn bg-neutral-focus"
                  >read</button
                ></td
              >
            </tr>
            <!-- row 2 -->
            <tr>
              <td>something about some thing or some other thing</td>
              <td>00/00/2000</td>
              <td
                ><button
                  class="hover:scale-105 hover:bg-neutral btn bg-neutral-focus"
                  >read</button
                ></td
              >
            </tr>
            <!-- row 3 -->
            <tr>
              <td>something about some thing or some other thing</td>
              <td>00/00/2000</td>
              <td
                ><button
                  class="hover:scale-105 hover:bg-neutral btn bg-neutral-focus"
                  >read</button
                ></td
              >
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </section>
</div>

<style>
  .curve::before {
    content: "";
    display: block;
    position: absolute;
    border-radius: 100% 50%;
    width: 55%;
    height: 100%;
    background-color: #dede44;
    transform: translate(85%, 60%);
  }
  .curve::after {
    content: "";
    display: block;
    position: absolute;
    border-radius: 100% 50%;
    width: 55%;
    height: 100%;
    background-color: hsl(var(--b1));
    transform: translate(-4%, 40%);
    z-index: 1;
  }

  .spacer {
    aspect-ratio: 960/200;
    width: 100%;
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    background-image: url("$lib/assets/layer-waves-yellow-gray.svg");
  }
</style>
