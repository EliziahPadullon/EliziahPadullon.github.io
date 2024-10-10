<script lang="ts">
  import ArrowUpRightFromSquareOutline from "flowbite-svelte-icons/ArrowUpRightFromSquareOutline.svelte";
</script>

<main class="bg-gray-100 flex justify-center items-center min-h-screen">
<div class="max-w-screen-xl mx-auto px-6 lg:px-8 flex flex-col lg:flex-row items-center space-y-10 lg:space-y-0 lg:space-x-16">
  
  <!-- Left Section - Text -->
  <div class="text-center lg:text-left">
    <h2 class="text-xl sm:text-2xl font-extrabold leading-tight mb-2">Hi!</h2>
    <h1 class="text-3xl sm:text-4xl font-extrabold leading-tight mb-4">
      I'm <span class="text-red-500">Eliziah</span> <br>
      a <span class="text-black">student Developer</span>
    </h1>
    <p class="text-gray-500 max-w-md mb-6 text-sm sm:text-base">
      Welcome! I’m glad you stopped by. Here, you’ll discover my projects and the skills I’ve developed as a developer. 
      Explore my work, and if anything catches your eye, I’d love to hear from you. Let’s connect and collaborate!
    </p>
    
    <!-- Buttons -->
    <div class="flex space-x-2 justify-center lg:justify-start">
      <button class="bg-red-500 text-white py-3 px-6 rounded-lg hover:bg-gray-800 flex items-center space-x-2">
        <a href="/about" class="flex items-center space-x-2">
          <span>Learn more</span> 
          <ArrowUpRightFromSquareOutline size="md" />
        </a>
      </button>
    </div>
  </div>

  <!-- Right Section - Image -->
  <div class="w-48 h-48 sm:w-64 sm:h-64 lg:w-80 lg:h-80 rounded-full overflow-hidden shadow-lg">
    <!-- svelte-ignore a11y-img-redundant-alt -->
    <img src="/images/me9.jpg" alt="Profile image" class="w-full h-full object-cover">
  </div>

</div>
</main>
