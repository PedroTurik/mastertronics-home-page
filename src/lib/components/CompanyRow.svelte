<script lang="ts">

    export let companyData: {
        logo: string;
        description: string;
        dists: string[];
        site: string;
    };
</script>

<div class="p-2 mx-auto grid grid-cols-1 rounded-sm place-items-center max-w-4xl">
    <img class="max-h-40 max-w-md m-4 p-6 hover:scale-105 transition-all" src={companyData.logo} alt="altLogo" />
    
    <p class="mx-5">
        {companyData.description}
    </p>
    <a class="mt-10" href="https://www.siward.com.tw/en" target="_blank">
        <button class="btn btn-secondary btn-outline btn-wide"> Visit site </button>
    </a>
    <span class="w-2"/>
    <div class="mt-10 p-4">
        <h3>Distribuidores:</h3>
        <div class="grid grid-cols-2 gap-x-3">
            {#each companyData.dists as dist}
                <img class="max-h-5 m-3" src={dist} alt="altHolder" />
            {/each}
        </div>
    </div>
</div>
