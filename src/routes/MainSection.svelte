<script>
import masterJustLogo from "$lib/assets/masterJustLogo.svg";
</script>

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

</style>

