<script>
  import Game from "./components/Game.svelte";
  import GameConsole from "./components/GameConsole.svelte";
  import Instructions from "./components/Instructions.svelte";
</script>

<style>
  .main {
    background: rgb(61, 147, 183);
    min-height: 100vh;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    position: relative;
    margin: 0;
  }
  img {
    position: absolute;
    top: 0;
    right: 0;
  }
</style>

<main class="main">
  <a href="https://github.com/RedEdge967/svelte-tetris" target="_blank">
    <img src="./corner.svg" alt="view and fork this in GitHub" />
  </a>
  <GameConsole />
  <Instructions />
</main>
