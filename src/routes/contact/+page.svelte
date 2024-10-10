<script>
  import FacebookSolid from "flowbite-svelte-icons/FacebookSolid.svelte";
  import GithubSolid from "flowbite-svelte-icons/GithubSolid.svelte";
  import EnvelopeSolid from "flowbite-svelte-icons/EnvelopeSolid.svelte";

  const profileImage = "/images/me8.jpg"; // Replace with your image path
  const socialMediaLinks = {
    facebook: "https://www.facebook.com/profile.php?id=100009946865426",
    github: "https://github.com/EliziahPadullon",
    gmail: "mailto:eliziahpadullon7@gmail.com"
  };
</script>

<main class="min-h-screen bg-gray-100 flex justify-center items-center p-4">
<!-- Contact Container -->
<div class="bg-white p-8 sm:p-10 rounded-lg shadow-lg text-center max-w-md sm:max-w-lg w-full">
  <!-- Profile Image -->
  <div class="flex justify-center mb-8">
    <img src={profileImage} alt="Profile" class="rounded-full w-20 h-20 sm:w-28 sm:h-28 object-cover shadow-lg">
  </div>
  
  <p class="text-gray-700 mb-6 sm:mb-8">Feel free to connect with me through my social media profiles below!</p>
  
  <p class="text-gray-700 mb-6 sm:mb-8">eliziahpadullon7@gmail.com</p>
  
  <!-- Social Media Icons -->
  <div class="flex justify-center space-x-4 sm:space-x-6">
    <!-- Facebook -->
    <a href={socialMediaLinks.facebook} target="_blank" rel="noopener noreferrer" aria-label="Facebook" class="hover:scale-110 transition-transform">
      <FacebookSolid class="w-8 h-8 sm:w-10 sm:h-10 hover:text-blue-700" />
    </a>
    
    <!-- GitHub -->
    <a href={socialMediaLinks.github} target="_blank" rel="noopener noreferrer" aria-label="GitHub" class="hover:scale-110 transition-transform">
      <GithubSolid class="w-8 h-8 sm:w-10 sm:h-10 hover:text-gray-800" />
    </a>

    <!-- Gmail -->
    <a href={socialMediaLinks.gmail} target="_blank" rel="noopener noreferrer" aria-label="Gmail" class="hover:scale-110 transition-transform">
      <EnvelopeSolid class="w-8 h-8 sm:w-10 sm:h-10 hover:text-red-500" />
    </a>
  </div>
</div>
</main>

<style>
.min-h-screen {
  min-height: 100vh;
}
</style>
