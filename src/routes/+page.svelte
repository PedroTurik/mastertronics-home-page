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
    <div class="curve absolute h-[225px] w-[100%] bottom-0"></div>
  </section>
  <section
    class="bg-secondary relative flex flex-col items-center min-h-[400px] py-24 px-[20vw]"
  >
    <h1>Nice Curves</h1>
    <p>
      Sunt dicta consequatur unde distinctio nihil ea, facere voluptas!
      Accusantium expedita commodi libero? Nisi quibusdam voluptatum asperiores
      pariatur vel animi ea eum excepturi, beatae eos, ut optio iste eaque
      accusamus.
    </p>

  </section>
  <div class="spacer"></div>
  
  <section
    class="bg-neutral relative flex flex-col items-center min-h-[400px] py-24 px-[20vw]"
  >
    <h1>Nice Curves</h1>
    <p>
      Dolorem corporis possimus, dolorum quaerat iusto quae aperiam, amet libero
      asperiores velit voluptas cumque unde sint fugit distinctio dolores
      repellat nam laudantium, a in odio? Dicta at odio accusamus deleniti!
    </p>
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
    background-color: hsl(var(--s));
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
    background-image: url('$lib/assets/layered-waves-haikei.svg');
  }

</style>
