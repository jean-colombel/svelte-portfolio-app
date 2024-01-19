<script>
  import Avatar from "$lib/assets/avatar.jpeg";
</script>

<section
  class="flex flex-col md:flex-row items-center md:items-start my-12 md:px-12"
>
  <img
    src={Avatar}
    alt="avatar"
    class="avatar rounded-full w-[260px] h-[260px]"
  />
  <div class="mt-8 md:mt-0 text-center md:text-left px-16 md:pt-5 max-w-2xl">
    <h1 class="text-3xl font-bold">Hello! I'm Jean.</h1>
    <p class="text-xl mt-4">
      I'm a full stack web developer, passionate about the web and innovative
      technologies. I am always thriving to learn and share my knowledge.
    </p>
    <p class="text-md font-thin mt-4">
      You can contact me using the form below or directly on LinkedIn.
    </p>
  </div>
</section>

<style>
  .avatar {
    border: 1px solid rgba(156, 163, 175, 0.5);
  }
</style>
