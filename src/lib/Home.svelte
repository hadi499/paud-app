<script>
  import { Link } from "svelte-routing";
</script>

<div class="font-sans text-slate-800">
  <main class="max-w-3xl mx-auto px-6 space-y-8 mt-8 mb-16">
    <div class="flex flex-col gap-3 justify-center items-center mb-8 px-2">
      <h1
        class="text-4xl font-bold tracking-wider text-slate-600 py-3 px-5 shadow-md rounded-md bg-blue-50 border-blue-300"
        style="font-family: 'Caveat Brush', sans-serif;"
      >
        Game Kognitif Anak
      </h1>
      <h2
        class="text-4xl font-semibold text-indigo-600 tracking-wide mb-2"
        style="font-family: 'Tangerine', sans-serif;"
      >
        Les Balonggarut
      </h2>
    </div>
    <section>
      <h1 class="text-2xl font-bold mb-6">Berhitung</h1>
      <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-4">
        <Link
          to="/counting-game"
          class="flex-col p-3 flex gap-3 items-center  bg-white rounded-2xl border border-slate-200 hover:border-pink-300 hover:shadow-md transition-all group"
        >
          <div
            class="w-12 h-12 bg-green-100 rounded-full flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform"
          >
            🧸
          </div>
          <h4 class="font-bold text-lg text-slate-900 text-center">
            Hitung Benda Level 1
          </h4>
          <p class="text-sm text-center">PAUD / TK</p>
        </Link>
        <Link
          to="/counting-game-medium"
          class="flex flex-col items-center p-3 gap-3 bg-white rounded-2xl border border-slate-200 hover:border-pink-300 hover:shadow-md transition-all group"
        >
          <div
            class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform"
          >
            🧸
          </div>
          <h4 class="font-bold text-lg text-slate-900 text-center">
            Hitung Benda Level 2
          </h4>
          <p class="text-sm text-center">PAUD / TK</p>
        </Link>
        <Link
          to="/counting-game-hard"
          class="flex-col p-3 flex gap-3 items-center bg-white rounded-2xl border border-slate-200 hover:border-pink-300 hover:shadow-md transition-all group"
        >
          <div
            class="w-12 h-12 bg-red-200 rounded-full flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform"
          >
            🧸
          </div>
          <h4 class="font-bold text-lg text-slate-900 mb-1 text-center">
            Hitung Benda Level 3
          </h4>
          <p class="text-sm text-center">PAUD / TK</p>
        </Link>
      </div>
    </section>
    <section>
      <h1 class="text-2xl font-bold mb-4">Game Tebak 4 Gambar</h1>
      <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-4">
        <Link
          to="/four-image-doraemon"
          class="flex-col p-3 flex gap-3 items-center bg-white rounded-2xl border border-slate-200 hover:border-sky-300 hover:shadow-md transition-all group"
        >
          <div
            class="w-14 h-14 bg-sky-100 rounded-full flex items-center justify-center text-2xl mb-1 group-hover:scale-110 transition-transform"
          >
            <img src="/images/doraemon/d5.png" alt="" class="h-12 w-12" />
          </div>
          <h4 class="font-bold text-lg text-slate-900">Doraemon</h4>
          <p class="text-sm text-center">PAUD / TK</p>
        </Link>
        <Link
          to="/four-image-tayo"
          class="flex-col p-3 flex gap-3 items-center bg-white rounded-2xl border border-slate-200 hover:border-sky-300 hover:shadow-md transition-all group"
        >
          <div
            class="w-14 h-14 bg-sky-100 rounded-full flex items-center justify-center text-2xl mb-1 group-hover:scale-110 transition-transform"
          >
            <img src="/images/tayo/t1.png" alt="" class="h-12 w-12" />
          </div>
          <h4 class="font-bold text-lg text-slate-900 mb-1">Tayo</h4>
          <p class="text-sm text-center">PAUD / TK</p>
        </Link>
        <Link
          to="/four-image-fruit"
          class="flex-col p-3 flex gap-3 items-center bg-white rounded-2xl border border-slate-200 hover:border-sky-300 hover:shadow-md transition-all group"
        >
          <div
            class="w-14 h-14 bg-sky-100 rounded-full flex items-center justify-center text-2xl mb-1 group-hover:scale-110 transition-transform"
          >
            <img src="/images/fruits/buah7.png" alt="" class="h-12 w-12" />
          </div>
          <h4 class="font-bold text-lg text-slate-900 mb-1">Buah</h4>
          <p class="text-sm text-center">PAUD / TK</p>
        </Link>
      </div>
    </section>
    <section>
      <h1 class="text-2xl font-bold mb-4">Game Tebak 6 Gambar</h1>
      <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-4">
        <Link
          to="/six-image-doraemon"
          class="flex-col p-3 flex gap-3 items-center bg-white rounded-2xl border border-slate-200 hover:border-green-300 hover:shadow-md transition-all group"
        >
          <div
            class="w-14 h-14 bg-sky-100 rounded-full flex items-center justify-center text-2xl mb-1 group-hover:scale-110 transition-transform"
          >
            <img src="/images/doraemon/d5.png" alt="" class="h-12 w-12" />
          </div>
          <h4 class="font-bold text-lg text-slate-900 mb-1">Doraemon</h4>
          <p class="text-sm text-center">PAUD / TK</p>
        </Link>
        <Link
          to="/six-image-tayo"
          class="flex-col p-3 flex gap-3 items-center bg-white rounded-2xl border border-slate-200 hover:border-green-300 hover:shadow-md transition-all group"
        >
          <div
            class="w-14 h-14 bg-sky-100 rounded-full flex items-center justify-center text-2xl mb-1 group-hover:scale-110 transition-transform"
          >
            <img src="/images/tayo/t1.png" alt="" class="h-12 w-12" />
          </div>
          <h4 class="font-bold text-lg text-slate-900 mb-1">Tayo</h4>
          <p class="text-sm text-center">PAUD / TK</p>
        </Link>
        <Link
          to="/six-image-fruit"
          class="flex-col p-3 flex gap-3 items-center bg-white rounded-2xl border border-slate-200 hover:border-sky-300 hover:shadow-md transition-all group"
        >
          <div
            class="w-14 h-14 bg-sky-100 rounded-full flex items-center justify-center text-2xl mb-1 group-hover:scale-110 transition-transform"
          >
            <img src="/images/fruits/buah7.png" alt="" class="h-12 w-12" />
          </div>
          <h4 class="font-bold text-lg text-slate-900 mb-1">Buah</h4>
          <p class="text-sm text-center">PAUD / TK</p>
        </Link>
      </div>
    </section>
  </main>
</div>
