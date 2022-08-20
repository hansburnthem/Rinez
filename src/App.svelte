<script>
    import Navbar from "./component/Navbar.svelte";
</script>

<main>
    <Navbar/>
    <!-- <div class="flex flex-wrap w-[1200px]">
        {#each movies as movie}
            <div class="p-2 flex flex-col w-[240px]">
                <img src={'https://image.tmdb.org/t/p/original' + movie.poster_path} alt={movie.original_title}>
                <h1 class="font-bold text-3xl text-center py-2">{movie.original_title}</h1>
                <p class="text-justify">{movie.overview}</p>
            </div>
        {/each}
    </div> -->
  
</main>