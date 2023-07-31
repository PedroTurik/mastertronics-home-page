<script>
  import MainSection from './MainSection.svelte';

  import ArticlesSection from './ArticlesSection.svelte';

  import YoutubeSection from './YoutubeSection.svelte';

</script>

<div class="w-screen">
  <MainSection></MainSection>
  <YoutubeSection></YoutubeSection>
  <div class="spacer" />
  <ArticlesSection></ArticlesSection>
</div>

<style>
  .spacer {
    aspect-ratio: 960/200;
    width: 100%;
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    background-image: url("$lib/assets/layer-waves-yellow-gray.svg");
  }
</style>
