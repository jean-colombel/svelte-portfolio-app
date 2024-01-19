<script>
  import "../global.css";
</script>

<main class="mx-4 md:mx-10 flex flex-col items-center">
  <slot />
</main>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

  :global(*) {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  :global(body) {
    background-color: #011523;
    color: #fff;
    font-family: "Poppins", sans-serif;
  }
</style>
