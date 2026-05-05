<script>
  import { Router, Route, links } from "svelte-routing";
  import Home from "./lib/Home.svelte";

  import CountingGame from "./lib/CountingGame.svelte";

  import CountingGameMedium from "./lib/CountingGameMedium.svelte";
  import CountingGameHard from "./lib/CountingGameHard.svelte";

  import FourImageDoraemon from "./lib/FourImageDoraemon.svelte";
  import FourImageTayo from "./lib/FourImageTayo.svelte";
  import SixImageDoraemon from "./lib/SixImageDoraemon.svelte";
  import SixImageTayo from "./lib/SixImageTayo.svelte";
  import FourImageFruit from "./lib/FourImageFruit.svelte";
  import SixImageFruit from "./lib/SixImageFruit.svelte";

  export let url = "";
</script>

<div use:links>
  <Router {url}>
    <main>
      <Route path="/">
        <Home />
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

      <Route path="/four-image-doraemon">
        <FourImageDoraemon />
      </Route>
      <Route path="/four-image-tayo">
        <FourImageTayo />
      </Route>
      <Route path="/four-image-fruit">
        <FourImageFruit />
      </Route>

      <Route path="/six-image-doraemon">
        <SixImageDoraemon />
      </Route>
      <Route path="/six-image-tayo">
        <SixImageTayo />
      </Route>
      <Route path="/six-image-fruit">
        <SixImageFruit />
      </Route>

      <Route path="*">
        <div class="text-center py-20 text-slate-500">
          <h2>Halaman Belum Tersedia</h2>
        </div>
      </Route>
    </main>
  </Router>
</div>
