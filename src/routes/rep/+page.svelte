<script lang="ts">
    import CompanyRow from "./CompanyRow.svelte";

    import siwardLogo from "$lib/assets/siward.png";
    import phisonLogo from "$lib/assets/Phison-logo.svg.png";
    import nuvotonLogo from "$lib/assets/Nuvoton.png";
    import zilogLogo from '$lib/assets/zilog.png';
    import jensenLogo from '$lib/assets/jenson.png';

    const companies = {
        siward: {
            logo: siwardLogo,
            description:
                "A SIWARD CRYSTAL TECHNOLOGY (TW) desenvolve e fabrica componentes baseados em cristais de quartzo que são largamente utilizados em produtos para telecomunicação, radio frequência, celulares e GPS",
            dists: [nuvotonLogo, nuvotonLogo, nuvotonLogo],
            site: "https://www.siward.com.tw/en"
        },
        phison: {
            logo: phisonLogo,
            description:
                "A Phison é uma empresa especializada no desenvolvimento de controladores para memórias flash, tanto para aplicações comerciais quanto industriais. Com a grande expansão deste tipo de armazenamento, a Phison atualmente oferece também de soluções de armazenamento em diversas configurações.",
            dists: [nuvotonLogo, nuvotonLogo],
            site: 'https://www.phison.com/en/'
        },
        nuvoton: {
            logo: nuvotonLogo,
            description:
                "Formada em 2008 a partir do “spin-off” da divisão de dispositivos de sinal misto da WINBOND, a taiwanesa NUVOTON é especializada em microcontroladores core ARM®7, ARM®9, Cortex™ M0, M23 e M4, MCUs baseadas em 8051, além de oferecer uma gama completa de produtos dedicados a gravação e reprodução de voz em alta fidelidade.",
            dists: [nuvotonLogo],
            site: 'https://www.nuvoton.com/'
        },
        zilog: {
            logo: zilogLogo,
            description:
                "Tradicional fabricante Americano de Microcontroladores de 8, 16 de 32bits (Cortex M3) para o mercado Industrial, a Zilog também oferece soluções SoC (System-on-chip) incluindo softwares dedicados para sensor de presença e controle de motor uma vez que essas aplicações requerem dos conversores Analógicos Digitais de alta confiabilidade/performance.",
            dists: [nuvotonLogo, nuvotonLogo, nuvotonLogo, nuvotonLogo],
            site: 'https://www.zilog.com/'
        },
        jensen: {
            logo: jensenLogo,
            description:
                'A Jenson Display Technology Limited foi fundada em 2002 na China Continental com o objetivo de desenvolver e fabricar displays LCD monocromáticos e coloridos "customizados", sejam estes LCDs simples ou módulos completos com backlight e controle integrado.',
            dists: [nuvotonLogo, nuvotonLogo],
            site: 'http://www.jensondisplay.com/'
        }

    };
</script>

<div class="flex flex-col w-full">
    <CompanyRow companyData={companies.siward} />
    <div class="mx-32 divider" />
    <CompanyRow companyData={companies.phison} />
    <div class="mx-32 divider" />
    <CompanyRow companyData={companies.nuvoton} />
    <div class="mx-32 divider" />
    <CompanyRow companyData={companies.zilog} />
    <div class="mx-32 divider" />
    <CompanyRow companyData={companies.jensen} />
</div>
