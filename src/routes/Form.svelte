<script lang="typescript">
  let firstName = "";
  let lastName = "";
  let email = "";
  let message = "";

  const handleSubmit = () => {
    console.log(firstName, lastName, email, message);
  };
</script>

<section class="mt-10 w-2/3 max-w-lg">
  <div class="flex items-center justify-center">
    <h1 class="section-title text-2xl font-bold inline-block">Contact Me:</h1>
  </div>
  <div class="grid grid-cols-2 gap-4 items-center mt-4 w-full pt-5 pb-8">
    <!-- First Name -->
    <div>
      <label for="first-name" class="text-sm font-medium">First name</label>
      <div class="mt-2 w-full">
        <input
          type="text"
          name="first-name"
          id="first-name"
          class="form-input rounded-md border-0 p-2 text-md text-black w-full"
          bind:value={firstName}
        />
      </div>
    </div>
    <!-- Last Name -->
    <div>
      <label for="last-name" class="text-sm font-medium">Last name</label>
      <div class="mt-2 w-full">
        <input
          type="text"
          name="last-name"
          id="last-name"
          autocomplete="family-name"
          class="form-input rounded-md border-0 p-2 mx-auto text-black w-full"
          bind:value={lastName}
        />
      </div>
    </div>
    <!-- Email -->
    <div class="col-span-2">
      <label for="email" class="text-sm font-medium">Email address</label>
      <div class="mt-2 w-full">
        <input
          id="email"
          name="email"
          type="email"
          autocomplete="email"
          class="form-input rounded-md border-0 p-2 mx-auto text-black w-full"
          bind:value={email}
        />
      </div>
    </div>
    <!-- Message -->
    <div class="col-span-2">
      <label for="message" class="text-sm font-medium">Message</label>
      <div class="mt-2 w-full">
        <textarea
          id="message"
          name="message"
          rows="8"
          class="form-input rounded-md border-0 p-2 text-black w-full"
          bind:value={message}
        />
      </div>
    </div>
  </div>
  <div class="flex items-center justify-center">
    <button
      class=" px-10 py-3 rounded-md font-medium cursor-pointer bg-green-500 hover:bg-green-600 ease-in-out transition-all"
      on:click={() => {
        handleSubmit();
      }}>Send</button
    >
  </div>
</section>

<style>
  .section-title {
    border-bottom: 1px solid rgba(156, 163, 175, 0.5);
  }

  .form-input {
    background: rgba(69, 72, 77, 0.172);
    border: 1px solid white;
    color: white;
  }
</style>
