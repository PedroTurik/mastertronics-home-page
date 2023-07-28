<script>
  import mastertronicsLogo from "$lib/assets/masterFullLogo.svg";
  import brazil from "$lib/assets/usa.svg";
  import usa from "$lib/assets/brazil.svg";
  import { page } from "$app/stores";
  import { eng } from "$lib/index";
</script>

<div class="navbar bg-base-100 w-screen">
  <div class="navbar-start">
    <a href="/">
      <img class="max-h-24" src={mastertronicsLogo} alt="logo" />
    </a>
  </div>
  <div class="navbar-center">
    <a
      href="/"
      class="btn btn-ghost rounded-none normal-case text-lg max-sm:text-sm"
      class:btn-active={$page.route.id === "/"}>Home</a
    >
    <a
      href="/about"
      class="btn btn-ghost rounded-none normal-case text-lg max-sm:text-sm"
      class:btn-active={$page.route.id?.includes("about")}
      >{$eng ? "About Us" : "Quem Somos"}</a
    >
    <a
      href="/rep"
      class="btn btn-ghost rounded-none normal-case text-lg max-sm:text-sm"
      class:btn-active={$page.route.id?.includes("rep")}
      >{$eng ? "Representadas" : "Representadas"}</a
    >
    <a
      href="/dist"
      class="btn btn-ghost rounded-none normal-case text-lg max-sm:text-sm"
      class:btn-active={$page.route.id?.includes("dist")}
      >{$eng ? "Distributors" : "Distribuidores"}</a
    >
    <!-- <a
        href="/contact"
        class="btn btn-ghost rounded-none normal-case text-lg"
        class:btn-active={$page.route.id?.includes("contact")}>{!$eng? "Contacts":"Contatos"}</a
      > -->
  </div>
  <div class="navbar-end">
    <label class="swap swap-flip">
      <!-- this hidden checkbox controls the state -->
      <input
        on:click={() => {
          $eng = !$eng;
        }}
        type="checkbox"
      />

      <div class="swap-on">
        <img class="max-h-4 object-scale-down" src={brazil} alt="brasil" />
      </div>
      <div class="swap-off"><img class="max-h-4" src={usa} alt="usa" /></div>
    </label>
  </div>
</div>
