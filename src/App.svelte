<script>
  import { Router, Route, links } from "svelte-routing";
  import Home from "./lib/Home.svelte";
  import MemoryGame from "./lib/MemoryGame.svelte";
  import CountingGame from "./lib/CountingGame.svelte";
  import OddOneOut from "./lib/OddOneOut.svelte";
  import CountingGameMedium from "./lib/CountingGameMedium.svelte";
  import CountingGameHard from "./lib/CountingGameHard.svelte";

  export let url = "";
</script>

<div use:links>
  <Router {url}>
    <main>
      <Route path="/">
        <Home />
      </Route>

      <Route path="/memory-game">
        <MemoryGame />
      </Route>

      <Route path="/counting-game">
        <CountingGame />
      </Route>

      <Route path="/counting-game-medium">
        <CountingGameMedium />
      </Route>
      <Route path="/counting-game-hard">
        <CountingGameHard />
      </Route>

      <Route path="/odd-one-out">
        <OddOneOut />
      </Route>

      <Route path="*">
        <div class="text-center py-20 text-slate-500">
          <h2>Halaman Belum Tersedia</h2>
        </div>
      </Route>
    </main>
  </Router>
</div>
