<script>
  import Angular from "$lib/assets/angular.svg";
  import React from "$lib/assets/react.svg";
  import Dotnet from "$lib/assets/dotnet.svg";
  import Svelte from "$lib/assets/svelte.svg";
</script>

<section class="text-center">
  <h1 class="section-title text-2xl font-bold section-title inline-block pb-1">
    Technology Stack:
  </h1>
  <div
    class="grid grid-cols-2 sm:grid-cols-4 gap-8 sm:gap-14 md:gap-28 lg:gap-40 mt-10"
  >
    <div class="flex items-center justify-center group">
      <img
        src={Angular}
        alt="angular"
        class="stack-icon w-[90px] h-[90px] rounded-full p-3"
      />
    </div>
    <div class="flex items-center justify-center group">
      <img src={React} alt="react" class="w-[90px] h-[90px] rounded-full p-3" />
    </div>
    <div class="flex items-center justify-center group">
      <img
        src={Svelte}
        alt="svelte"
        class="w-[90px] h-[90px] rounded-full p-3"
      />
    </div>
    <div class="flex items-center justify-center group">
      <img
        src={Dotnet}
        alt="dotnet"
        class="w-[90px] h-[90px] rounded-full p-3"
      />
    </div>
  </div>
</section>

<style>
  .section-title {
    border-bottom: 1px solid rgba(156, 163, 175, 0.5);
  }
</style>
