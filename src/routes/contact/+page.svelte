<script>
    const profileImage = "/images/me8.jpg"; // Replace with your image path
    const socialMediaLinks = {
      facebook: "https://www.facebook.com/profile.php?id=100009946865426",
      github: "https://github.com/EliziahPadullon",
      linkedin: "https://www.linkedin.com/"
    };
  </script>
  
  <main class="h-screen bg-gray-100 flex justify-center items-center">
    <!-- Contact Container -->
    <div class="bg-white p-10 rounded-lg shadow-lg text-center max-w-lg">
      <!-- Profile Image -->
      <div class="flex justify-center mb-8">
        <img src={profileImage} alt="Profile" class="rounded-full w-24 h-24 object-cover shadow-lg">
      </div>
      
      <p class="text-gray-700 mb-8">Feel free to connect with me through my social media profiles below!</p>

      <!-- Social Media Icons -->
      <div class="flex justify-center space-x-6">
        <!-- Facebook -->
        <a href={socialMediaLinks.facebook} target="_blank" rel="noopener noreferrer" aria-label="Facebook" class="hover:scale-110 transition-transform">
            <i class='bx bxl-facebook-circle text-4xl' style='color:#3e7997' ></i>
        </a>
        
        <!-- GitHub -->
        <a href={socialMediaLinks.github} target="_blank" rel="noopener noreferrer" aria-label="GitHub" class="hover:scale-110 transition-transform">
            <i class='bx bxl-github text-4xl'></i>
        </a>
        
        <!-- Gmail -->
        <a href={socialMediaLinks.linkedin} target="_blank" rel="noopener noreferrer" aria-label="Linkedin" class="hover:scale-110 transition-transform">
            <i class='bx bxl-linkedin-square text-4xl' style='color:#47779f' ></i>
        </a>
      </div>
    </div>
  </main>
  
