<script>
export default {
  name: "App",
};
</script>

<template>
  <div id="app">
    <div class="reveal">
      <div class="slides">
        <div class="absolute px-3 bottom-0 w-full bg-snowcamp-purple bg-opacity-90 z-50 flex items-center justify-between footer">
          <img
            class="left-4 w-12"
            src="/src/assets/Logo-Kaizen-black.png"
            alt="Kaizen Logo Black"
          />
          <img
            class="rounded-md w-36 snowcamp-logo"
            src="/src/assets/snowcamp-logo.webp"
            alt="Snowcamp Logo"
          />
        </div>
        <Cover />
        <Bio />
        <FromMonolithicToMicroservice />
        <Microfrontends />
        <OurChallenge />
        <Modules />
        <WebPackModuleFederation />
        <AngularDemo />
        <VueDemo />
        <ReactDemo />
        <AngularJsDemo />
        <Thankings />
      </div>
    </div>
  </div>
</template>

<style>
#app,
section {
  @apply w-full h-full;
}

.footer > img{
  @apply m-2 !important;
}
</style>
