<script>
  import { Link } from "svelte-routing";
</script>

<div class="font-sans text-slate-800">
  <main class="max-w-3xl mx-auto px-6 space-y-8 mt-8">
    <div class="flex justify-center items-center mb-8 px-2">
      <h3 class="text-2xl font-bold text-blue-700">
        Latihan Kognitif Anak PAUD/TK
      </h3>
    </div>
    <section>
      <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-4">
        <Link
          to="/counting-game"
          class="block p-5 bg-white rounded-2xl border border-slate-200 hover:border-pink-300 hover:shadow-md transition-all group"
        >
          <div
            class="w-12 h-12 bg-green-100 rounded-full flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform"
          >
            🧸
          </div>
          <h4 class="font-bold text-lg text-slate-900 mb-1">
            Hitung Benda Level 1
          </h4>
          <p class="text-sm text-slate-500 leading-relaxed line-clamp-2">
            Latih pengenalan angka dasar (PAUD/TK).
          </p>
        </Link>
        <Link
          to="/counting-game-medium"
          class="block p-5 bg-white rounded-2xl border border-slate-200 hover:border-pink-300 hover:shadow-md transition-all group"
        >
          <div
            class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform"
          >
            🧸
          </div>
          <h4 class="font-bold text-lg text-slate-900 mb-1">
            Hitung Benda Level 2
          </h4>
          <p class="text-sm text-slate-500 leading-relaxed line-clamp-2">
            Latih pengenalan angka dasar (PAUD/TK).
          </p>
        </Link>
        <Link
          to="/counting-game-hard"
          class="block p-5 bg-white rounded-2xl border border-slate-200 hover:border-pink-300 hover:shadow-md transition-all group"
        >
          <div
            class="w-12 h-12 bg-red-200 rounded-full flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform"
          >
            🧸
          </div>
          <h4 class="font-bold text-lg text-slate-900 mb-1">
            Hitung Benda Level 3
          </h4>
          <p class="text-sm text-slate-500 leading-relaxed line-clamp-2">
            Latih pengenalan angka dasar (PAUD/TK).
          </p>
        </Link>
        <Link
          to="/odd-one-out"
          class="block p-5 bg-white rounded-2xl border border-slate-200 hover:border-orange-300 hover:shadow-md transition-all group"
        >
          <div
            class="w-12 h-12 bg-orange-100 rounded-full flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform"
          >
            🦅
          </div>
          <h4 class="font-bold text-lg text-slate-900 mb-1">Cari yang Beda</h4>
          <p class="text-sm text-slate-500 leading-relaxed line-clamp-2">
            Latih ketelitian visual mata (PAUD/TK).
          </p>
        </Link>

        <Link
          to="/memory-game"
          class="block p-5 bg-white rounded-2xl border border-slate-200 hover:border-sky-300 hover:shadow-md transition-all group"
        >
          <div
            class="w-12 h-12 bg-sky-100 rounded-full flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform"
          >
            🧠
          </div>
          <h4 class="font-bold text-lg text-slate-900 mb-1">Memory Match</h4>
          <p class="text-sm text-slate-500 leading-relaxed line-clamp-2">
            Latih daya ingat dan visual (PAUD/TK).
          </p>
        </Link>
      </div>
    </section>
  </main>
</div>
