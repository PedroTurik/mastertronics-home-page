<script lang="ts">

    export let companyData: {
        logo: string;
        description: string;
        dists: string[];
        site: string;
    };
</script>

<div class="p-2 mx-32 grid grid-cols-1 md:grid-cols-4 rounded-sm bg- place-items-center">
    <a href="https://www.siward.com.tw/en">
        <img class="max-h-28 m-4 p-6 hover:scale-105 transition-all" src={companyData.logo} alt="altLogo" />
    </a>

    <p class="mx-5">
        {companyData.description}
    </p>
    <span class="w-2"/>
    <div class="p-4">
        <h3>Distribuidores:</h3>
        <div class="grid grid-cols-2 gap-x-3">
            {#each companyData.dists as dist}
                <img class="max-h-5 m-3" src={dist} alt="altHolder" />
            {/each}
        </div>
    </div>
</div>
