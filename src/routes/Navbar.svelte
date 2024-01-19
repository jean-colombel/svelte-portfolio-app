<script>
  import Icon from "@iconify/svelte";
  import Logo from "$lib/assets/programming.svg";
</script>

<nav
  class="navbar flex items-center justify-between px-8 py-4 w-full sticky top-0"
>
  <img
    src={Logo}
    alt="programming-logo"
    class="h-[60px] w-[60px] cursor-pointer"
  />
  <div class="flex gap-2 items-center">
    <div class="dark-mode-toggle p-2 text-3xl cursor-pointer">
      <Icon icon="mingcute:sun-fill" />
    </div>
    <a
      class="social-icon rounded-lg"
      href="https://github.com/jean-colombel"
      target="_blank"
    >
      <Icon icon="mdi:github" /></a
    >
    <a
      class="social-icon"
      href="https://www.linkedin.com/in/jean-colombel/"
      target="_blank"><Icon icon="mdi:linkedin" /></a
    >
  </div>
</nav>

<style lang="postcss">
  .navbar {
    border-bottom: 1px solid rgba(156, 163, 175, 0.5);
    background-color: #011523;
  }

  .social-icon :global(svg) {
    font-size: 3rem;
    border-radius: 0.5rem;
    padding: 0.5rem;
  }

  .social-icon :global(svg):hover {
    background-color: rgba(255, 255, 255, 0.1);
  }

  .dark-mode-toggle :global(svg) {
    color: #feef89;
  }
</style>
