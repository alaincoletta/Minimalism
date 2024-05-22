---
title: index
layout: page.njk
keyword: test
permalink: "{{ title | slugify }}.html"
eleventyNavigation:
  key: "{{ title | slugify }}"
  title: Home
  order: 1
---

# Genes of Thrones

![Genes of Thrones Avatar](img/logo.webp)

Welcome to **Genes of Thrones**, an epic saga where ancient power struggles meet cutting-edge genetics. Dive into the captivating world of Genoria, a kingdom where the fate of noble houses is determined not only by their lineage but by their unique genetic traits.

## Explore the Kingdom of Genoria

### The Story
In the ancient kingdom of Genoria, power is inherited not just through bloodlines but through remarkable genetic traits passed down from generation to generation. The kingdom, once stable under the rule of the Genetic Monarchs, faces unprecedented turmoil after the sudden death of the king. As a fierce battle for the throne ensues, the quest for the legendary Genetic Codex—a manuscript that holds the secrets to enhancing and manipulating genetic traits—becomes paramount.

### The Houses of Genoria

- **House Helix**: Renowned for their unparalleled physical strength and endurance, members of House Helix are the kingdom’s warriors and protectors.
- **House Mendel**: Masters of bioengineering and genetic manipulation, House Mendel’s innovations have shaped the very fabric of Genoria’s society.
- **House Genome**: Known for their intellectual brilliance and strategic minds, House Genome excels in diplomacy and governance.
- **House Cytos**: Possessing extraordinary regenerative and healing abilities, House Cytos members are the healers and nurturers of the realm.

### The Conflict
With the monarchy in disarray, the noble houses vie for supremacy. Each house seeks to demonstrate their genetic superiority and secure the Genetic Codex, believing it holds the key to unlocking the ultimate power. Amidst this chaos, a young member of House Helix uncovers a hidden trait that could change the fate of Genoria. This protagonist must navigate a treacherous landscape filled with alliances, betrayals, and deep-seated family secrets.

## Themes and Inspirations

**Genes of Thrones** explores profound themes such as identity, heritage, ethical dilemmas in genetic manipulation, and the corrupting nature of power. Inspired by the complex characters and intricate plots of *Game of Thrones*, combined with contemporary discussions on personal genomics and biotechnology, this story offers a fresh and thought-provoking narrative.

## Personal Genomics

In this world, personal genomics is at the heart of the story. The characters’ abilities and social standings are intrinsically tied to their genetic makeup, echoing real-world debates about genetic privacy, the potential of CRISPR technology, and the future of human enhancement.

## Join the Saga

Immerse yourself in the world of Genoria, where ancient legacies and futuristic science collide. Follow the epic tale of power, genetics, and destiny in **Genes of Thrones**.

---

**Quote from George R.R. Martin on Complexity of Characters:**
"In real life, people are complicated. People are capable of being good and bad at the same time. And in fantasy, people are often one or the other—villains or heroes. I’ve tried to create people who have not just one side, but many sides, which I think makes for more interesting characters and stories." - George R.R. Martin

---

Explore the world, meet the houses, and discover the secrets of the Genetic Codex. Your adventure in Genoria awaits!

[Learn More](#about-genes-of-thrones)
<!-- # Minimalism -->
<!---->
<!-- <a href="https://11ty-minimalism.netlify.app/" target="blank_"> -->
<!--   <img alt="antreprima" src="http://marcomicale.altervista.org/minimalism.webp" width="100%" > -->
<!-- </a> -->
<!---->
<!-- > Simplicity is the ultimate sophistication! -->
<!---->
<!-- ## Cosa voglio ottene? -->
<!---->
<!-- - ✅ Creazione pagine velocemente -->
<!-- - ✅ Favicon personalizzabile (msapplication/apple/safari/chrome) -->
<!-- - ✅ Blog -->
<!-- - ✅ Fedd Rss -->
<!-- - ✅ Sitemap -->
<!-- - ✅ PWA -->
<!-- - ✅ Immagini social dinamiche per ogni pagina/post -->
<!-- - ✅ Ottimizzazione SEO -->
<!-- - ✅ 404 error page -->
<!-- - ✅ Offline page -->
<!-- - ✅ Link social facili - edit /src/_11ty/_data/meta.js -->
<!-- - ✅ Tutti 100 in lighthouse -->
<!-- - ✅ Light/Dark mode -->
<!-- - ✅ [Netifly](https://www.netlify.com/) -->
<!---->
<!-- ## Cosa ho usato: -->
<!---->
<!-- - [Eleventy](https://github.com/11ty/eleventy) -->
<!--   - [Plugin eleventy-img](https://github.com/11ty/eleventy-img) -->
<!--   - [Plugin eleventy-plugin-rss](https://github.com/11ty/eleventy-plugin-rss) -->
<!--   - [Plugin eleventy-navigation](https://github.com/11ty/eleventy-navigation) -->
<!--   - [Plugin-social-images](https://github.com/5t3ph/eleventy-plugin-social-images) -->
<!--   - [Plugin-reading-time](https://github.com/johanbrook/eleventy-plugin-reading-time) -->
<!-- - [Tailwindcss](https://github.com/tailwindlabs/tailwindcss) -->
<!--   - [Tailwindcss typography](https://github.com/tailwindlabs/tailwindcss-typography) -->
<!-- - [Slugify]([https://github.com/simov/slugify) -->
<!-- - [Luxon](https://github.com/moment/luxon) -->
<!-- - [html minifier](https://github.com/kangax/html-minifier) -->
<!-- - [rimraf](https://github.com/isaacs/rimraf) -->
<!-- - [npm-run-all](https://github.com/mysticatea/npm-run-all) -->
<!-- - [Tabler Icon](https://github.com/tabler/tabler-icons) -->
<!---->
<!-- ## Status -->
<!-- ### BETA -->
<!---->
<!-- Usabile ma con qualche correzione da effettuare. -->
<!---->
<!-- ## Folder Tree -->
<!---->
<!-- ```bash -->
<!-- Minimalism -->
<!-- |   .eleventy.js -->
<!-- |   .gitattributes -->
<!-- |   .gitignore -->
<!-- |   LICENSE -->
<!-- |   logo.png                          # Sostituisci questo file con il tuo logo -->
<!-- |   netlify.toml -->
<!-- |   package-lock.json -->
<!-- |   package.json -->
<!-- |   README.md -->
<!-- |   SECURITY.md -->
<!-- |   tailwind.config.js -->
<!-- | -->
<!-- +---.github -->
<!-- |   \---workflows -->
<!-- |           codeql-analysis.yml -->
<!-- | -->
<!-- +---.vscode -->
<!-- |       tasks.json -->
<!-- | -->
<!-- \---src -->
<!--     |   ...                           # Aggiungi le pagine che vuoi -->
<!--     |   blog.md                       # Pagina del tuo Blog (modifica da qui la intro) -->
<!--     |   index.md                      # La Prima pagina del tuo sito (essenziale) -->
<!--     | -->
<!--     +---blog -->
<!--     |       ...                       # Inserisci qui i tuoi post per il blog -->
<!--     | -->
<!--     \---_11ty -->
<!--         +---_data -->
<!--         |       meta.js               # MODIFICA QUESTO FILE! -->
<!--         | -->
<!--         +---_generate -->
<!--         |       404.njk -->
<!--         |       feed.njk -->
<!--         |       manifest.njk -->
<!--         |       offline.njk           # Pagina mostrata dall'app se offline -->
<!--         |       pagesjson.njk -->
<!--         |       robot.njk -->
<!--         |       sitemap.njk -->
<!--         |       socialtemplate.njk    # Modifica se vuoi cambiare l'immagine social -->
<!--         | -->
<!--         +---_includes -->
<!--         |       favicon.njk -->
<!--         |       footer.njk -->
<!--         |       head-article.njk -->
<!--         |       head-website.njk -->
<!--         |       head.njk -->
<!--         |       nav.njk               # Header sito (Titolo e Nav Bar) -->
<!--         | -->
<!--         +---_layouts                  # Layouts: -->
<!--         |       article.njk           # Articoli del Blog -->
<!--         |       blog.njk              # Pagina del Blog -->
<!--         |       page.njk              # Pagine generiche -->
<!--         | -->
<!--         +---_social                   # File generati per l'immagine social -->
<!--         |       pages.json -->
<!--         |       social.css -->
<!--         |       template.html -->
<!--         | -->
<!--         +---_static -->
<!--         |   +---app                   # Risorse statiche -->
<!--         |   |       .htaccess -->
<!--         |   |       sw.js -->
<!--         |   | -->
<!--         |   +---favicon -->
<!--         |   |       ...               # Favicon Generate a partire dal file logo.png -->
<!--         |   | -->
<!--         |   \---img -->
<!--         |           ... -->
<!--         | -->
<!--         \---_tailwindCSS -->
<!--                 raw-social.css        # CSS del tuo sito -->
<!--                 raw-website.css       # Modifica se vuoi cambiare l'immagine social -->
<!-- ``` -->
<!---->