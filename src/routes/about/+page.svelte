<script lang="ts">
    import { eng } from "$lib";

    const text_pt =
        "Fundada em 1991 no sul do Brasil, a Mastertronics oferece serviços completos de representação para fabricantes internacionais de componentes eletrônicos (software e hardware) na América Latina. Nosso objetivo é garantir acesso fácil e confiável às soluções mais competitivas e inovadoras em todo o mundo para nossa base de clientes leais e reconhecidos. Com amplo conhecimento dos desafios e da cultura do mercado local, proporcionamos suporte técnico excepcional aos nossos clientes. Ao longo das décadas, a Mastertronics estabeleceu fortes alianças estratégicas com os principais distribuidores globais de insumos eletrônicos produtivos para a indústria, como Arrow Electronics, Future Electronics e Macnica DHW. Essas parcerias garantem o acesso às fontes de suprimento representadas pela Mastertronics através desses distribuidores confiáveis para nossa base de clientes.";
    const text_eng =
        "Mastertronics was founded in South Brazil in 1991 to offer reliable representation services for international manufacturers of electronic components (software & hardware parts) demanded by the Latin America Electronics Industry. Since then, our goal has been to ensure that our loyal and recognized customer base has easy and reliable access to the most competitive and innovative solutions worldwide. We have acquired extensive knowledge of local market challenges and culture, allowing us to adapt and offer exceptional technical support to our customers. Mastertronics employs a non-stocking Manufacturer REP strategy and takes pride in establishing strong strategic alliances with top global distributors, including Arrow Electronics, Future Electronics, and Macnica DHW. These partnerships ensure that our customer base can access our supply sources through these reliable distributors.";

    // import fotoEmpresa from '$lib/assets/fotoEmpresa.png';

    let modal: HTMLDialogElement;
</script>

<div class="hero mt-4">
    <div class="hero-content text-center">
        <div class="max-w-4xl">
            <h1
                class="m-auto max-w-xl p-2 text-5xl text-transparent bg-clip-text font-bold bg-gradient-to-br from-[hsl(var(--bc))] to-yellow-600"
            >
                {$eng
                    ? "Developing Eletronics Together"
                    : "Desenvolvendo Eletrônica Juntos"}
            </h1>
            <p class="m-6 p-6 card rounded-box text-justify">
                {$eng ? text_eng : text_pt}
            </p>

            <p />
            <button class="btn btn-secondary" on:click={() => modal.showModal()}
                >{$eng ? "Contact Us" : "Contate-nos"}</button
            >
            <dialog id="mod" class="modal" bind:this={modal}>
                <form method="dialog" class="modal-box">
                    <form method="POST">
                        <h3 class="font-bold text-lg">
                            {$eng ? "Send us an E-mail" : "Nos envie um E-mail"}
                        </h3>

                        <div class="form-control w-full max-w-xs">
                            <!-- svelte-ignore a11y-label-has-associated-control -->
                            <label class="label">
                                <span class="label-text"
                                    >What is your name?</span
                                >
                            </label>
                            <input
                                type="text"
                                placeholder="Type here"
                                class="input input-bordered w-full max-w-xs"
                            />
                            <!-- svelte-ignore a11y-label-has-associated-control -->
                            <label class="label">
                                <span class="label-text"
                                    >Summary</span
                                >
                            </label>
                            <input
                                type="text"
                                placeholder="Type here"
                                class="input input-bordered"
                            />
                            <div class="form-control">
                                <!-- svelte-ignore a11y-label-has-associated-control -->
                                <label class="label">
                                    <span class="label-text">message</span>
                                    
                                </label>
                                <textarea
                                    class="textarea textarea-bordered h-24"
                                    placeholder="text"
                                />
                            </div>
                        </div>
                    </form>
                </form>
                <form method="dialog" class="modal-backdrop">
                    <button>close</button>
                </form>
            </dialog>
        </div>
    </div>
</div>
