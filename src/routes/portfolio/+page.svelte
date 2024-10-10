<script lang="ts">
    const projects = [
        {
            title: "Student Portfolio Profile",
            images: [
                { src: "/images/unfold1.png", title: "Title 1", description: "Brief description 1" },
                { src: "/images/unfold2.png", title: "Title 2", description: "Brief description 2" },
                { src: "/images/unfold3.png", title: "Title 3", description: "Brief description 3" },
                { src: "/images/unfold4.png", title: "Title 4", description: "Brief description 4" },
                
            ]
        },
        {
            title: "Weather App",
            images: [
                { src: "/images/weather.png", title: "Title 7", description: "Brief description 7" },
            ]
        },
        {
            title: "Online Marketplace for Independent Artists",
            images: [
                { src: "/images/omia1.png", title: "Title 7", description: "Brief description 7" },
                { src: "/images/omia2.png", title: "Title 7", description: "Brief description 7" },
            ]
        },
        {
            title: "Philippine Map",
            images: [
                { src: "/images/map1.png", title: "Title 7", description: "Brief description 7" },
                { src: "/images/map2.png", title: "Title 7", description: "Brief description 7" },
                { src: "/images/map3.png", title: "Title 7", description: "Brief description 7" },
                { src: "/images/map4.png", title: "Title 7", description: "Brief description 7" },
                { src: "/images/map5.png", title: "Title 7", description: "Brief description 7" },
                { src: "/images/map6.png", title: "Title 7", description: "Brief description 7" },
            ]
        }
    ];
</script>

<div class="container mx-auto px-4 py-8">
    {#each projects as project}
        <div class="mb-10">
            <h2 class="text-3xl font-semibold mb-4">{project.title}</h2>
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

<style>
  .container {
    max-width: 1200px;
  }
</style>
