<script>
    let imageSrc = '/images/me1.jpg'; // Update with your image path
</script>

<div class="flex justify-center items-center h-screen bg-gray-100">
  <div class="bg-white rounded-lg shadow-lg flex overflow-hidden max-w-4xl w-full">
    <!-- Image Section -->
    <div class="bg-gray-900 w-2/4 flex justify-center items-center">
      <!-- svelte-ignore a11y-img-redundant-alt -->
      <img src={imageSrc} alt="Profile Image" class="object-cover h-full w-full rounded-l-lg">
    </div>
    
    <!-- Text Section -->
    <div class="bg-gray-50 p-8 w-3/4">
      <h2 class="text-2xl font-semibold mb-4">About me</h2>
      <p class="text-gray-700 text-justify">
        As a student, balancing life and academics has been a challenge, but it’s also what keeps me motivated. Between classes, part-time work, and personal commitments, I’ve learned how to manage my time effectively, ensuring I always make space for my love of development. Coding, for me, is more than just a skill—it’s a creative outlet. Whether I'm working on a personal project or tackling a university assignment, it feels like I’m solving puzzles, and that keeps me excited every day.
      </p>

      <br>

      <p class="text-gray-700 text-justify">
        My journey as a student developer really took off when I started experimenting with frontend development. I found joy in creating user interfaces that not only look great but also enhance the user experience. Learning HTML, CSS, JavaScript, and diving into frameworks like React felt like discovering new tools to turn ideas into reality.
      </p>

      <br>

      <p class="text-gray-700 text-justify">
        Through trial and error, late-night coding sessions, and collaborating with fellow students, I’ve grown both in skill and confidence. I’ve also realized that learning never stops, especially in tech, where everything evolves so quickly. This mindset keeps me pushing forward, eager to keep improving.
      </p>

      <br>

      <p class="text-gray-700 text-justify">
        Outside of coding, I love spending time with friends and family, and when I’m not glued to my computer, I enjoy getting outdoors for a breath of fresh air. This balance helps me recharge and come back to my projects with fresh ideas.
      </p>
        

    </div>
  </div>
</div>

<style>
  .h-screen {
    height: 100vh;
  }
</style>
