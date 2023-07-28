<script>
  import { eng } from "$lib";
  import ramMemory from "$lib/assets/RamMemory.png";
  import masterJustLogo from "$lib/assets/masterJustLogo.svg";
</script>

<div class="w-screen">
  <section
    class="relative flex flex-col items-center min-h-[400px] py-24 px-[20vw]"
  >
    <h1>Nice Curves</h1>
    <p class="z-10">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil reiciendis
      dolor fugit a et alias libero quisquam totam aut quibusdam expedita
      distinctio porro quos, explicabo incidunt, neque pariatur quia minima.
    </p>
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
  <section
    class="bg-accent relative flex flex-col items-center min-h-[400px] py-24 px-[20vw]"
  >
    <h1>Nice Curves</h1>
    <p>
      Facere aliquid esse laborum adipisci eaque provident cumque possimus id
      repellendus ratione, amet dolor debitis mollitia. Officia, animi iste
      error perspiciatis eveniet blanditiis. Maiores voluptatem eius incidunt
      impedit! Laudantium, sit!
    </p>
  </section>
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
  <section
    class="bg-info relative flex flex-col items-center min-h-[400px] py-24 px-[20vw]"
  >
    <h1>Nice Curves</h1>
    <p>
      Ex minus repudiandae voluptatum sit deserunt quia natus, nisi magni unde
      suscipit nobis vero veritatis quas dolores omnis nihil dolorem ipsum
      blanditiis dignissimos alias non consequatur quam molestias? Ea, eveniet?
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
</style>
