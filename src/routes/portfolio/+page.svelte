<script lang="ts">
    const projects = [
        {
            title: "Student Portfolio Profile",
            images: [
                { src: "/images/unfold1.png", title: "Login Page", description: "This is where you login and create accounts" },
                { src: "/images/unfold2.png", title: "Project Dashboard", description: "Here is where students can add, edit, and delete their projects and " },
                { src: "/images/unfold3.png", title: "About", description: "This is the student's profile page 3" },
                { src: "/images/unfold4.png", title: "Portfolio Feed", description: "The newsfeed for finding students" },
                
            ]
        },
        {
            title: "Weather App",
            images: [
                { src: "/images/weather.png", title: "Weather app", description: "Angular project for our assessment" },
            ]
        },
        {
            title: "Online Marketplace for Independent Artists",
            images: [
                { src: "/images/omia1.png", title: "Login Page", description: "" },
                { src: "/images/omia2.png", title: "Home Page", description: "Showcasing independent artists' products" },
            ]
        },
        {
            title: "Philippine Map",
            images: [
                { src: "/images/map1.png", title: "PH Map", description: "This is the home page where you can choose what island to go" },
                { src: "/images/map2.png", title: "Luzon Map", description: "Here are 3 places in the Luzon area" },
                { src: "/images/map3.png", title: "About Zambales", description: "A brief introduction about Zambales" },
                { src: "/images/map4.png", title: "Zambales Info", description: "A gallery of tourist spots in Zambales" },
                { src: "/images/map5.png", title: "About Quirino", description: "A brief introduction about Quirino" },
                { src: "/images/map6.png", title: "Quirino Info", description: "A gallery of tourist spots in Quirino" },
            ]
        }
    ];
</script>

<main class="bg-gray-100 h-full">
    <div class="container mx-auto px-4 py-8">
        {#each projects as project}
            <div class="mb-10">
                <h2 class="text-gray-2xl font-semibold mb-4">{project.title}</h2>
                <div class="grid grid-cols-3 gap-6">
                    {#each project.images as image}
                        <div class="relative group">
                            <img src={image.src} alt={image.title} class="w-full h-56 object-cover rounded-lg shadow-lg" />
                            <div class="absolute inset-0 bg-gray-900 bg-opacity-60 flex justify-center items-center text-white opacity-0 group-hover:opacity-100 transition-opacity duration-300 rounded-lg">
                                <div class="text-center">
                                    <h3 class="text-lg font-bold">{image.title}</h3>
                                    <p class="text-sm">{image.description}</p>
                                </div>
                            </div>
                        </div>
                    {/each}
                </div>
            </div>
        {/each}
    </div>
    
</main>

<style>
  .container {
    max-width: 1500px;
    height: auto;
  }
  
</style>
