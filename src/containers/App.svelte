<script context="module">
  import Header from "../components/Header.svelte";
  import Main from "../components/Main.svelte";
  import Sidebar from "../components/Sidebar.svelte";
  import TimeLine from "../components/TimeLine.svelte";
</script>

<Header />
<Main>
  <TimeLine />
  <Sidebar />
</Main>

<style>
  @import url("https://fonts.googleapis.com/css?family=Pacifico&display=swap");
  :global(body) {
    background-color: #fafafa;
    color: #383838f0;
    font-family: "Lato", sans-serif;
    margin: 0;
    padding: 0;
  }

  :global(h1, h2, h3) {
    margin: 0;
    padding: 0;
  }
</style>
