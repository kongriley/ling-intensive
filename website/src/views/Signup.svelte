<script>

  let isLoaded = false;
  let cannotLoad = false;

  function changeLoad() {
    isLoaded = true;
  }

  function neverLoaded() {
    if (!isLoaded) cannotLoad = true;
    isLoaded = true;
  }

  setTimeout(neverLoaded, 2000)

</script>

<div class="text-center text-3xl md:text-4xl lg:text-5xl font-medium mt-16 mb-16">Sign up here!</div>

{#if !isLoaded}
  <div class="text-center text-xl md:text-2xl lg:text-3xl text-gray-600">
    Loading...
  </div>
{/if}
{#if !cannotLoad}
  <div class="flex justify-center">
    <iframe class="w-full" on:load={changeLoad} height=1500 src="https://docs.google.com/forms/d/e/1FAIpQLSdGerL3Ezot9I5v5GqsaXMt2fan_EKLX1rnq_bfaKDWZpnHsw/viewform?embedded=true" frameborder="0" marginheight="0" marginwidth="0" title="Signup Form">Loading…</iframe>
  </div>
{:else}
  <div class="text-center text-xl md:text-2xl lg:text-3xl text-red-600">
    Sorry, could not load signup form.
  </div>
{/if}