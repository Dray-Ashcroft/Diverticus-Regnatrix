<p align="center">
  <img src="assets/banner.png" alt="Diverticus Regnatrix banner" width="100%" />
</p>

<h1 align="center">Diverticus Regnatrix</h1>

<p align="center"><i>Biological Classification Engine · From Two Kingdoms to Five</i></p>

<p align="center"><b><a href="https://diverticus-regnatrix.stark-kodex.workers.dev">Explore Diverticus</a></b></p>

<p align="center">
  <a href="#about">About</a> ·
  <a href="#screenshots">Screenshots</a> ·
  <a href="#gallery">Gallery</a> ·
  <a href="#views">Views</a> ·
  <a href="#controls">Controls</a> ·
  <a href="#science">Science</a> ·
  <a href="#technology">Technology</a> ·
  <a href="#credits">Credits</a> ·
  <a href="#releases">Releases</a> ·
  <a href="#license">License</a>
</p>

---

## About

Diverticus Regnatrix is an interactive classroom app on biological classification, built for Class 9 science. A single low-poly tree of life stays fixed while each classification system recolours its branches, so students see that organisms do not change, only the way scientists group them.

It covers Linnaeus' two kingdoms, Haeckel's three kingdoms, Copeland's four kingdoms, Whittaker's five kingdoms and Woese's three domains, with a dichotomous key, an organism classifier, side-by-side comparisons and illustrated example organisms, including the four major groups of Archaea.

## Screenshots

<p align="center"><img src="assets/collage.png" alt="Diverticus Regnatrix: six views of the app" width="100%"></p>

## Gallery

<table>
<tr>
<td width="33%" align="center"><img src="assets/illustrations/plant-cell.png" alt="Plant cell"><br><sub><b>Plant Cell</b></sub></td>
<td width="33%" align="center"><img src="assets/illustrations/animal-cell.png" alt="Animal cell"><br><sub><b>Animal Cell</b></sub></td>
<td width="33%" align="center"><img src="assets/illustrations/bacterium.png" alt="Bacterium"><br><sub><b>Bacterium</b></sub></td>
</tr>
<tr>
<td width="33%" align="center"><img src="assets/illustrations/amoeba.png" alt="Amoeba"><br><sub><b>Amoeba</b></sub></td>
<td width="33%" align="center"><img src="assets/illustrations/mushroom.png" alt="Mushroom"><br><sub><b>Mushroom</b></sub></td>
<td width="33%" align="center"><img src="assets/illustrations/methanobacterium.png" alt="Methanobacterium"><br><sub><b>Methanobacterium</b></sub></td>
</tr>
</table>

## Views

| View | What You See | Tap to Explore |
|---|---|---|
| Tree of Life | A tree on a floating island, branches coloured by the chosen system | Tap a branch for its group card; hold to see its organisms |
| Diagram | Box diagram with a feature label on every split | Tap a group to open its card |
| Phylogeny | Two systems side by side with a list of what moved | Pick any two systems and compare |
| Compare | Two organisms checked trait by trait | Choose organisms to see what is the same and what differs |
| Classify | Neon dichotomous key and organism classifier | Answer each character, or trace an organism to its kingdom |
| More | History, tricky cases, backup and references | Save a snapshot or back up your pictures |

**Concepts:** Prokaryote and eukaryote · Unicellular and multicellular · Cell wall · Autotrophic and heterotrophic nutrition · Dichotomous keys · History of classification · Three domains · Archaea

## Controls

| Control | Function |
|---|---|
| Tap | Open a group card, answer a key question or select an organism |
| Hold (0.5 s) | Show the organism pictures of a group |
| Double-tap | Open a picture full size |
| Hold (6 s) | Add or change an example picture |
| Swipe | Move between cards or pictures; swipe down to close |
| Header buttons | Theme, "Where does it go?", edit images, presentation mode |

## Science

<details>
<summary><b>Classification systems covered</b></summary>

| System | Proposed by | Groups |
|---|---|---|
| Two kingdoms | Linnaeus, 18th century | Plantae · Animalia |
| Three kingdoms | Haeckel, 1866 | Protista · Plantae · Animalia |
| Four kingdoms | Copeland, 1956 | Monera · Protista · Plantae · Animalia |
| Five kingdoms | Whittaker, 1969 | Monera · Protista · Fungi · Plantae · Animalia |
| Three domains | Woese and colleagues, 1990 | Bacteria · Archaea · Eukarya |

Groups are separated by cell type (prokaryotic or eukaryotic), body organisation (unicellular or multicellular), cell wall and mode of nutrition (autotrophic, heterotrophic or absorptive). The Archaea examples cover methanogens, extreme halophiles, thermoacidophiles and ammonia-oxidising archaea.

</details>

## Technology

HTML · CSS · JavaScript · Inline SVG · WebP · Cloudflare Pages

<details>
<summary><b>Project files</b></summary>

| File | Contents |
|---|---|
| `index.html` | Page structure and the default picture links |
| `css/style.css` | Layout, themes and kingdom colours |
| `js/app.js` | Classification data, interactions, snapshot export and the tree-of-life image |
| `assets/banner.png` | README banner |
| `assets/screenshots/` | README screenshots, numbered in display order |
| `assets/illustrations/` | Example organisms and cells, one file per organism |

</details>

## Credits

| Contributor | Role |
|---|---|
| Sai Prasad, M.Sc. Agri. Entomology, ASRB NET | Project Designer |
| Claude Opus 5.5 | Development |
| OpenAI Astra 6 | Image Generation |
| Perplexity Sonar 2 | Scientific Reasoning |
| DeepSeek V1 | Assistance |

<details>
<summary><b>3D models</b></summary>

| Asset | Model | Creator | Licence |
|---|---|---|---|
| Tree | Tree (PS1/PSX Style) | Mateusz Woliński | Sketchfab Standard |
| Island | [Floating Island With Roots And Rocks](https://sketchfab.com/3d-models/floating-island-with-roots-and-rocks-4c05ffef4d1c45ab847ac565b8184a5b) | [Dennis](https://sketchfab.com/dennis.hafemann) | [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/) |

Both models were combined and rendered to a single image; the hanging skeleton, bird and ground were removed from the tree model. This work is based on the island model, licensed under CC BY 4.0.

</details>

<details>
<summary><b>Libraries and fonts</b></summary>

| Component | Licence |
|---|---|
| No runtime libraries (vanilla JavaScript) | — |
| Inter, with system font fallback | SIL Open Font License 1.1 |
| three.js (used only to render the tree image) | MIT |

</details>

## Releases

| Release | Title | Date |
|---|---|---|
| RC V | Archaea | 17 Nov 2026 |
| RC IV | Tree of Life | 17 Nov 2026 |
| RC III | Living Tree | 16 Nov 2026 |
| RC II | Neon Flowchart | 14 Nov 2026 |
| RC I | Foundation | 13 Nov 2026 |

## License

Source code is released under the [GNU General Public License v3.0](LICENSE). Third-party 3D models remain under their own licences listed above.

<p align="center"><sub><a href="https://github.com/Dray-Ashcroft/Diverticus-Regnatrix">GitHub</a> · Codeberg | Hosted on Cloudflare Pages</sub></p>
