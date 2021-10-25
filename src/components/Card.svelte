<script>
    import Comments from "./Comments.svelte";
</script>

<div class="Card">
    <div class="Card-container">
        <div class="Card-header">
            <div class="Card-user">
                <img src="https://picsum.photos/400" alt="My pet"/>
                <h2>
                    Random image
                    <span>Mexico City, Mexico</span>
                </h2>
            </div>
            <div class="Card-settings">
                <span class="material-icons">circle</span>
            </div>
        </div>
        <div class="Card-photo">
            <figure>
                <img src="https://picsum.photos/400" alt="My pet"/>
            </figure>
        </div>
        <div class="Card-icons">
            <div class="Card-icons-first">
                <span class="material-icons">favorite</span>
                <span class="material-icons">send</span>
            </div>
            <div class="Card-icons-second">
                <span class="material-icons">bookmark</span>
            </div>
        </div>
    <div class="Card-description">
        <h3>Random image</h3>
        <span>Hola!</span>
    </div>
    <Comments />
    </div>
</div>