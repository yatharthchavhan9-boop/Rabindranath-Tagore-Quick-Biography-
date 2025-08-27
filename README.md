
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Rabindranath Tagore – Biography</title>
  <meta name="description" content="A clean, responsive one-page biography website for Rabindranath Tagore (1861–1941): life, works, timeline, quotes, and legacy." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: { sans: ['Inter', 'ui-sans-serif', 'system-ui'] },
          colors: {
            primary: {
              50: '#eef2ff', 100: '#e0e7ff', 200: '#c7d2fe', 300: '#a5b4fc',
              400: '#818cf8', 500: '#6366f1', 600: '#4f46e5', 700: '#4338ca', 800: '#3730a3', 900: '#312e81'
            }
          }
        }
      },
      darkMode: 'class'
    }
  </script>
  <style>
    /* Accent underline */
    .underline-accent { box-shadow: inset 0 -0.5em 0 0 rgba(99,102,241,0.15); }
  </style>
</head>
<body class="bg-white text-slate-800 dark:bg-slate-950 dark:text-slate-100">
  <!-- Nav -->
  <header class="sticky top-0 z-40 backdrop-blur supports-[backdrop-filter]:bg-white/60 bg-white/80 dark:supports-[backdrop-filter]:bg-slate-950/60 dark:bg-slate-950/80 border-b border-slate-200 dark:border-slate-800">
    <div class="max-w-6xl mx-auto flex items-center justify-between px-4 py-3">
      <a href="#home" class="flex items-center gap-3 font-extrabold text-lg"><span class="inline-flex h-9 w-9 items-center justify-center rounded-xl bg-primary-600 text-white">RT</span> Tagore Biography</a>
      <nav class="hidden md:flex items-center gap-6 text-sm">
        <a href="#life" class="hover:text-primary-600">Life</a>
        <a href="#works" class="hover:text-primary-600">Works</a>
        <a href="#timeline" class="hover:text-primary-600">Timeline</a>
        <a href="#quotes" class="hover:text-primary-600">Quotes</a>
        <a href="#legacy" class="hover:text-primary-600">Legacy</a>
      </nav>
      <div class="flex items-center gap-2">
        <button id="themeToggle" aria-label="Toggle dark mode" class="rounded-2xl border border-slate-300 dark:border-slate-700 px-3 py-1.5 text-xs md:text-sm hover:bg-slate-50 dark:hover:bg-slate-900">🌙/☀️</button>
        <a href="#download" class="hidden sm:inline-block rounded-2xl bg-primary-600 px-3 py-1.5 text-white text-xs md:text-sm hover:bg-primary-700">Download</a>
      </div>
    </div>
  </header>

  <!-- Hero -->
  <section id="home" class="relative pt-14">
    <div class="max-w-6xl mx-auto px-4 grid md:grid-cols-2 gap-10 items-center py-12">
      <div>
        <h1 class="text-3xl md:text-5xl font-extrabold leading-tight">
          Rabindranath <span class="text-primary-600">Tagore</span>
          <span class="block mt-2 text-lg md:text-2xl font-medium text-slate-500 dark:text-slate-400">(7 May 1861 – 7 Aug 1941)</span>
        </h1>
        <p class="mt-5 text-base md:text-lg text-slate-600 dark:text-slate-300">
          Poet, novelist, playwright, composer, painter, educator, and the first non‑European Nobel laureate in Literature (1913) for <em>Gitanjali</em>. Tagore reshaped modern Bengali literature and music and founded Visva‑Bharati University at Santiniketan.
        </p>
        <div class="mt-6 flex gap-3">
          <a href="#works" class="rounded-2xl bg-primary-600 px-5 py-2 text-white font-medium hover:bg-primary-700">Explore Works</a>
          <a href="#life" class="rounded-2xl border border-slate-300 dark:border-slate-700 px-5 py-2 font-medium hover:bg-slate-50 dark:hover:bg-slate-900">About</a>
        </div>
        <dl class="mt-8 grid grid-cols-2 sm:grid-cols-4 gap-5 text-center">
          <div class="rounded-2xl border border-slate-200 dark:border-slate-800 p-4">
            <dt class="text-xs uppercase tracking-wider text-slate-500">Nobel Prize</dt>
            <dd class="mt-1 text-xl font-bold">1913</dd>
          </div>
          <div class="rounded-2xl border border-slate-200 dark:border-slate-800 p-4">
            <dt class="text-xs uppercase tracking-wider text-slate-500">Founded</dt>
            <dd class="mt-1 text-xl font-bold">Visva‑Bharati (1921)</dd>
          </div>
          <div class="rounded-2xl border border-slate-200 dark:border-slate-800 p-4">
            <dt class="text-xs uppercase tracking-wider text-slate-500">Anthem (India)</dt>
            <dd class="mt-1 text-xl font-bold"><em>Jana Gana Mana</em></dd>
          </div>
          <div class="rounded-2xl border border-slate-200 dark:border-slate-800 p-4">
            <dt class="text-xs uppercase tracking-wider text-slate-500">Anthem (Bangladesh)</dt>
            <dd class="mt-1 text-xl font-bold"><em>Amar Shonar Bangla</em></dd>
          </div>
        </dl>
      </div>
      <div class="relative">
        <div class="aspect-[4/5] w-full overflow-hidden rounded-3xl border border-slate-200 dark:border-slate-800 shadow-lg">
          <!-- Replace the src with a licensed portrait URL if publishing -->
          <img src="https://upload.wikimedia.org/wikipedia/commons/9/9b/Rabindranath_Tagore_unknown_location.jpg" alt="Portrait of Rabindranath Tagore" class="h-full w-full object-cover" />
        </div>
        <p class="mt-3 text-xs text-slate-500">Image credit: Wikimedia Commons (public domain).</p>
      </div>
    </div>
  </section>

  <!-- Life -->
  <section id="life" class="py-14 bg-slate-50 dark:bg-slate-900/40">
    <div class="max-w-6xl mx-auto px-4 grid md:grid-cols-3 gap-10 items-start">
      <div class="md:col-span-2">
        <h2 class="text-2xl md:text-3xl font-extrabold underline-accent">Life & Background</h2>
        <p class="mt-5 leading-7 text-slate-700 dark:text-slate-300">
          Born in Calcutta (now Kolkata) into the influential Tagore family, Rabindranath was educated largely at home and immersed in literature, music, and the arts from an early age. He traveled to England briefly in 1878, absorbing Western literary currents while retaining a deep grounding in Indian philosophies and the Bengali language.
        </p>
        <p class="mt-4 leading-7 text-slate-700 dark:text-slate-300">
          As an adult he managed the family estates in rural Bengal, experiences that shaped his humanism and his sensitivity to the lives of ordinary people. His worldview combined spiritual universalism with a commitment to social reform, education, and cultural exchange.
        </p>
        <ul class="mt-6 grid sm:grid-cols-2 gap-4 text-sm">
          <li class="rounded-2xl border border-slate-200 dark:border-slate-800 p-4"><span class="font-semibold">Born:</span> 7 May 1861, Calcutta, Bengal Presidency</li>
          <li class="rounded-2xl border border-slate-200 dark:border-slate-800 p-4"><span class="font-semibold">Died:</span> 7 August 1941, Calcutta, British India</li>
          <li class="rounded-2xl border border-slate-200 dark:border-slate-800 p-4"><span class="font-semibold">Parents:</span> Debendranath Tagore & Sarada Devi</li>
          <li class="rounded-2xl border border-slate-200 dark:border-slate-800 p-4"><span class="font-semibold">Also known as:</span> Gurudev, Kobiguru</li>
        </ul>
      </div>
      <aside class="space-y-4">
        <div class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5">
          <h3 class="font-semibold">Highlights</h3>
          <ul class="mt-3 list-disc pl-5 text-sm leading-6">
            <li>First Asian Nobel laureate in Literature (1913)</li>
            <li>Founded Visva‑Bharati University (1921)</li>
            <li>Renounced knighthood (1919) after the Jallianwala Bagh massacre</li>
            <li>Prolific composer (~2,000+ songs, <em>Rabindra Sangeet</em>)</li>
            <li>Late‑life painter with a unique modernist style</li>
          </ul>
        </div>
        <div class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5">
          <h3 class="font-semibold">Fields</h3>
          <p class="mt-2 text-sm text-slate-600 dark:text-slate-300">Poetry · Novels · Short stories · Drama · Essays · Music · Painting · Education</p>
        </div>
      </aside>
    </div>
  </section>

  <!-- Works -->
  <section id="works" class="py-14">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-2xl md:text-3xl font-extrabold underline-accent">Major Works</h2>
      <div class="mt-8 grid md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Card -->
        <article class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5 hover:shadow-lg transition">
          <h3 class="font-bold text-lg">Gitanjali (1910/1912)</h3>
          <p class="mt-2 text-sm text-slate-600 dark:text-slate-300">Devotional poems expressing a personal dialogue with the divine; the English selection <em>Gitanjali: Song Offerings</em> earned Tagore the 1913 Nobel Prize.</p>
        </article>
        <article class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5 hover:shadow-lg transition">
          <h3 class="font-bold text-lg">Gora (1909)</h3>
          <p class="mt-2 text-sm text-slate-600 dark:text-slate-300">A panoramic novel exploring identity, nationalism, and social reform in late‑19th‑century Bengal.</p>
        </article>
        <article class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5 hover:shadow-lg transition">
          <h3 class="font-bold text-lg">The Home and the World (1916)</h3>
          <p class="mt-2 text-sm text-slate-600 dark:text-slate-300">A triadic narrative examining Swadeshi politics, love, and moral conflict.</p>
        </article>
        <article class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5 hover:shadow-lg transition">
          <h3 class="font-bold text-lg">Kabuliwala (1892)</h3>
          <p class="mt-2 text-sm text-slate-600 dark:text-slate-300">A beloved short story about a Pashtun fruit seller and his bond with a young girl in Calcutta.</p>
        </article>
        <article class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5 hover:shadow-lg transition">
          <h3 class="font-bold text-lg">Tagore’s Songs (Rabindra Sangeet)</h3>
          <p class="mt-2 text-sm text-slate-600 dark:text-slate-300">Over two thousand compositions blending classical, folk, and modern sensibilities; two became national anthems.</p>
        </article>
        <article class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5 hover:shadow-lg transition">
          <h3 class="font-bold text-lg">Painting & Visual Art</h3>
          <p class="mt-2 text-sm text-slate-600 dark:text-slate-300">From the 1920s, Tagore developed a striking, modernist visual style, exhibiting internationally.</p>
        </article>
      </div>
    </div>
  </section>

  <!-- Education & Ideas -->
  <section class="py-14 bg-slate-50 dark:bg-slate-900/40">
    <div class="max-w-6xl mx-auto px-4 grid md:grid-cols-2 gap-10 items-start">
      <div>
        <h2 class="text-2xl md:text-3xl font-extrabold underline-accent">Education & Ideas</h2>
        <p class="mt-5 leading-7 text-slate-700 dark:text-slate-300">
          Tagore envisioned education that nurtures the whole person—imagination, ethics, and a living relationship with nature. In 1901 he began a school at Santiniketan; this blossomed into Visva‑Bharati University in 1921, dedicated to a meeting of cultures: “Where the world makes a home in a single nest.”
        </p>
        <p class="mt-4 leading-7 text-slate-700 dark:text-slate-300">
          A global traveler and interlocutor with leading thinkers of his time, Tagore advocated internationalism, rural reconstruction at Sriniketan (1922), and a humanist critique of narrow nationalism.
        </p>
      </div>
      <div class="space-y-4">
        <div class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5">
          <h3 class="font-semibold">Key Themes</h3>
          <ul class="mt-3 list-disc pl-5 text-sm leading-6">
            <li>Humanism and universalism</li>
            <li>Nature, freedom, and creativity</li>
            <li>Social reform and rural uplift</li>
            <li>Dialogue across cultures</li>
          </ul>
        </div>
        <div class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5">
          <h3 class="font-semibold">Institutions</h3>
          <p class="mt-2 text-sm">Santiniketan (1901) · Visva‑Bharati (1921) · Sriniketan (1922)</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Timeline -->
  <section id="timeline" class="py-14">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-2xl md:text-3xl font-extrabold underline-accent">Timeline</h2>
      <ol class="mt-8 relative border-s-2 border-slate-200 dark:border-slate-800">
        <li class="ms-6 mb-6">
          <div class="absolute -start-3.5 mt-1 h-3 w-3 rounded-full bg-primary-600"></div>
          <h3 class="font-semibold">1861</h3>
          <p class="text-sm text-slate-600 dark:text-slate-300">Born in Calcutta on 7 May.</p>
        </li>
        <li class="ms-6 mb-6">
          <div class="absolute -start-3.5 mt-1 h-3 w-3 rounded-full bg-primary-600"></div>
          <h3 class="font-semibold">1878</h3>
          <p class="text-sm text-slate-600 dark:text-slate-300">Travels to England; studies briefly.</p>
        </li>
        <li class="ms-6 mb-6">
          <div class="absolute -start-3.5 mt-1 h-3 w-3 rounded-full bg-primary-600"></div>
          <h3 class="font-semibold">1901</h3>
          <p class="text-sm text-slate-600 dark:text-slate-300">Founds school at Santiniketan.</p>
        </li>
        <li class="ms-6 mb-6">
          <div class="absolute -start-3.5 mt-1 h-3 w-3 rounded-full bg-primary-600"></div>
          <h3 class="font-semibold">1912–1913</h3>
          <p class="text-sm text-slate-600 dark:text-slate-300">Publishes English <em>Gitanjali</em>; wins Nobel Prize in Literature (1913).</p>
        </li>
        <li class="ms-6 mb-6">
          <div class="absolute -start-3.5 mt-1 h-3 w-3 rounded-full bg-primary-600"></div>
          <h3 class="font-semibold">1915</h3>
          <p class="text-sm text-slate-600 dark:text-slate-300">Receives knighthood (later renounced in 1919).</p>
        </li>
        <li class="ms-6 mb-6">
          <div class="absolute -start-3.5 mt-1 h-3 w-3 rounded-full bg-primary-600"></div>
          <h3 class="font-semibold">1921–1922</h3>
          <p class="text-sm text-slate-600 dark:text-slate-300">Establishes Visva‑Bharati University and Sriniketan institute.</p>
        </li>
        <li class="ms-6 mb-6">
          <div class="absolute -start-3.5 mt-1 h-3 w-3 rounded-full bg-primary-600"></div>
          <h3 class="font-semibold">1941</h3>
          <p class="text-sm text-slate-600 dark:text-slate-300">Passes away on 7 August in Calcutta.</p>
        </li>
      </ol>
    </div>
  </section>

  <!-- Quotes -->
  <section id="quotes" class="py-14 bg-slate-50 dark:bg-slate-900/40">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-2xl md:text-3xl font-extrabold underline-accent">Quotes</h2>
      <div class="mt-8 grid md:grid-cols-2 lg:grid-cols-3 gap-6">
        <figure class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5">
          <blockquote class="italic">“Let your life lightly dance on the edges of time like dew on the tip of a leaf.”</blockquote>
          <figcaption class="mt-3 text-sm text-slate-500">— Rabindranath Tagore</figcaption>
        </figure>
        <figure class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5">
          <blockquote class="italic">“Faith is the bird that feels the light and sings when the dawn is still dark.”</blockquote>
          <figcaption class="mt-3 text-sm text-slate-500">— Rabindranath Tagore</figcaption>
        </figure>
        <figure class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5">
          <blockquote class="italic">“You can’t cross the sea merely by standing and staring at the water.”</blockquote>
          <figcaption class="mt-3 text-sm text-slate-500">— Rabindranath Tagore</figcaption>
        </figure>
      </div>
    </div>
  </section>

  <!-- Legacy / FAQ -->
  <section id="legacy" class="py-14">
    <div class="max-w-6xl mx-auto px-4 grid md:grid-cols-3 gap-10 items-start">
      <div class="md:col-span-2">
        <h2 class="text-2xl md:text-3xl font-extrabold underline-accent">Legacy</h2>
        <p class="mt-5 leading-7 text-slate-700 dark:text-slate-300">
          Tagore’s impact is woven into South Asian and global culture—from school textbooks and concert halls to university curricula and modern art. He remains a symbol of literary brilliance, intercultural dialogue, and ethical imagination.
        </p>
        <div class="mt-6 grid sm:grid-cols-2 gap-4">
          <div class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5">
            <h3 class="font-semibold">National Anthems</h3>
            <p class="mt-2 text-sm">Lyrics of India’s <em>Jana Gana Mana</em> and Bangladesh’s <em>Amar Shonar Bangla</em> are by Tagore.</p>
          </div>
          <div class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5">
            <h3 class="font-semibold">Global Influence</h3>
            <p class="mt-2 text-sm">Admired by Yeats, Einstein, Romain Rolland, and many others; his music and ideas continue to inspire.</p>
          </div>
        </div>
      </div>
      <aside class="space-y-4">
        <div class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5">
          <h3 class="font-semibold">Quick Facts</h3>
          <ul class="mt-3 text-sm leading-6 list-disc pl-5">
            <li>Languages: Bengali, English</li>
            <li>Genres: Poetry, fiction, drama, essays, songs</li>
            <li>Movements: Bengal Renaissance, Santiniketan School</li>
          </ul>
        </div>
        <div class="rounded-3xl border border-slate-200 dark:border-slate-800 p-5" id="download">
          <h3 class="font-semibold">Download</h3>
          <p class="mt-2 text-sm">Right‑click → “Save as…” to save this page as <code>tagore.html</code>. All styles are embedded via CDN.</p>
        </div>
      </aside>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-10 border-t border-slate-200 dark:border-slate-800">
    <div class="max-w-6xl mx-auto px-4 flex flex-col md:flex-row items-center justify-between gap-4">
      <p class="text-sm text-slate-500">© <span id="year"></span> Rabindranath Tagore Biography • Built for learning.</p>
      <div class="text-xs text-slate-500">Made with Tailwind • Dark‑mode ready</div>
    </div>
  </footer>

  <script>
    // Dark mode toggle
    const themeToggle = document.getElementById('themeToggle');
    const root = document.documentElement;
    const stored = localStorage.getItem('theme');
    if (stored === 'dark' || (!stored && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
      root.classList.add('dark');
    }
    themeToggle.addEventListener('click', () => {
      root.classList.toggle('dark');
      localStorage.setItem('theme', root.classList.contains('dark') ? 'dark' : 'light');
    });
    // Year
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
