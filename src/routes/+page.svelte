<script>

    let title = "Learn Svelte";

    const changeTitle = () => {
        title = "Change Title";
    }

    

</script>

<div class="index">
    <h1>{title}</h1>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptates accusantium quisquam fuga neque? Quae illo molestias voluptatem similique repellat necessitatibus veniam quas vero mollitia, sit libero quia totam eveniet maxime nisi doloribus in consequatur ipsa. Nostrum repudiandae libero nam iusto quidem. Quos eum, eius rem libero aliquam, quis totam tenetur fugiat molestiae debitis nemo asperiores incidunt culpa explicabo repudiandae laudantium.</p>

    <button on:click={changeTitle}>
        Change Title
    </button>

    <input type="text" bind:value={title}>
</div>

<style>
    .index{
        text-align: center;
        display: block;
        margin: 20 auto;
    }
</style>