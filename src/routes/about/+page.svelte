<script>
  let imageSrc = '/images/me1.jpg'; // Update with your image path
</script>

<div class="flex justify-center items-center min-h-screen bg-gray-100 p-4">
<div class="bg-white rounded-lg shadow-lg flex flex-col lg:flex-row overflow-hidden max-w-4xl w-full">
  <!-- Image Section -->
  <div class="bg-gray-900 w-full lg:w-2/4 flex justify-center items-center">
    <!-- svelte-ignore a11y-img-redundant-alt -->
    <img src={imageSrc} alt="Profile Image" class="object-cover h-64 lg:h-full w-full rounded-t-lg lg:rounded-l-lg lg:rounded-t-none">
  </div>
  
  <!-- Text Section -->
  <div class="bg-gray-50 p-8 w-full lg:w-3/4">
    <h2 class="text-2xl font-semibold mb-4">About me</h2>
    <p class="text-gray-700 text-justify">
      Hello! My name is Eliziah Alexis Z. Padullon. I am currently studying Information Technology at Gordon College.
      Balancing life and academics as a student has been challenging, but it’s also what drives me. 
      Between classes and personal commitments, I’ve learned to manage my time effectively while making sure there’s always space for my passion—coding. 
      For me, development is more than just a skill it’s a creative outlet where I can solve problems and bring ideas to life.
    </p>

    <br>

    <p class="text-gray-700 text-justify">
      My journey as a developer really took off when I dove into frontend development. 
      Learning HTML, CSS, and JavaScript, along with frameworks like React, opened up a whole new world of possibilities. 
      Creating user interfaces that look great and provide a smooth experience became something I truly enjoy. 
      Each project I work on pushes me to learn more and refine my skills.
    </p>

    <br>

    <p class="text-gray-700 text-justify">
      Outside of coding, I love spending time with family and getting outdoors to clear my mind. 
      This balance helps me stay focused and brings fresh ideas to my projects. 
      Looking ahead, I’m excited for what’s next, knowing that every challenge I face brings me closer to becoming the developer I want to be.
    </p>
  </div>
</div>
</div>

<style>
.min-h-screen {
  min-height: 100vh;
}
</style>
