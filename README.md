<div align="center">

<img src="assets/banner/banner.png" alt="Diverticus Regnatrix banner" width="100%">

# Diverticus Regnatrix

*Biological Classification Engine · From Two Kingdoms to Five*

**[Explore Diverticus](https://YOUR-SITE.pages.dev)**

[About](#about) · [Screenshots](#screenshots) · [Gallery](#gallery) · [Views](#views) · [Controls](#controls) · [Technology](#technology) · [Credits](#credits) · [Releases](#releases) · [License](#license)

</div>

---

## About

Diverticus Regnatrix is an interactive classroom app on biological classification, built for Class 9 science. A single low-poly tree of life stays fixed while each classification system recolours its branches, so students see that organisms do not change, only the way scientists group them.

It covers Linnaeus' two kingdoms, Haeckel's three kingdoms, Copeland's four kingdoms, Whittaker's five kingdoms and Woese's three domains, with a dichotomous key, an organism classifier, side-by-side comparisons and illustrated example organisms, including the four major groups of Archaea.

## Screenshots

<table>
<tr>
<td width="50%"><img src="assets/Screenshots/Bio%20Deverticus%20Regnatrix.png" alt="Home"><br><sub><b>1 · Meet Regnatrix</b></sub></td>
<td width="50%"><img src="assets/Screenshots/Tree%20Of%20Life.png" alt="Tree of life"><br><sub><b>2 · Tree of Life</b></sub></td>
</tr>
<tr>
<td width="50%"><img src="assets/Screenshots/Compare%20%26%20Contrast.png" alt="Phylogeny"><br><sub><b>3 · Easy Comparison</b></sub></td>
<td width="50%"><img src="assets/Screenshots/Explore%20Organism.png" alt="Group card"><br><sub><b>4 · Explore Organisms</b></sub></td>
</tr>
<tr>
<td width="50%"><img src="assets/Screenshots/Memorable%20Flow%20Charts.png" alt="Diagram"><br><sub><b>5 ·
Mind Maps</b></sub></td>
<td width="50%"><img src="assets/Screenshots/Chronological%20Slider.png" alt="Chronological slider"><br><sub><b>6 · Chronological Slider</b></sub></td>
</tr>
</table>

## Gallery

<table>
<tr>
<td width="33%" align="center"><img src="assets/Plant%20cell/file_000000001f6082119c3db959a6de81f3.png" alt="Plant cell"><br><sub><b>Plant Cell</b></sub></td>
<td width="33%" align="center"><img src="assets/Animal%20Cell/file_0000000097b88211bbebc2308b0de35d.png" alt="Animal cell"><br><sub><b>Animal Cell</b></sub></td>
<td width="33%" align="center"><img src="assets/Bacteria/file_00000000ff4c8211b892fab1458af977.png" alt="Bacterium"><br><sub><b>Bacterium</b></sub></td>
</tr>
<tr>
<td width="33%" align="center"><img src="assets/Amoeba/file_0000000072b88211ba2b4181aa79d2da.png" alt="Amoeba"><br><sub><b>Amoeba</b></sub></td>
<td width="33%" align="center"><img src="assets/Mushroom/file_000000002b54821187efa6a194b35f90.png" alt="Mushroom"><br><sub><b>Mushroom</b></sub></td>
<td width="33%" align="center"><img src="assets/Methanobacterium/file_000000001090821186a070efa703fda3.png" alt="Methanobacterium"><br><sub><b>Methanobacterium</b></sub></td>
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

## Technology

HTML · CSS · JavaScript · Inline SVG · WebP · Cloudflare Pages

<details>
<summary><b>Project files</b></summary>

| File | Contents |
|---|---|
| `index.html` | Page structure and the default picture links |
| `style.css` | Layout, themes and kingdom colours |
| `app.js` | Classification data, interactions and the tree-of-life image |
| `assets/` | Banner, screenshots and organism illustrations |

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
| [RC V](RELEASE_NOTES.md#rc-v--archaea) | Archaea | 17 Nov 2026 |
| [RC IV](RELEASE_NOTES.md#rc-iv--tree-of-life) | Tree of Life | 17 Nov 2026 |
| [RC III](RELEASE_NOTES.md#rc-iii--living-tree) | Living Tree | 16 Nov 2026 |
| [RC II](RELEASE_NOTES.md#rc-ii--neon-flowchart) | Neon Flowchart | 14 Nov 2026 |
| [RC I](RELEASE_NOTES.md#rc-i--foundation) | Foundation | 13 Nov 2026 |

## License

Released under the [GNU General Public License v3.0](LICENSE). Third-party 3D models remain under their own licences listed above.

---

<div align="center">
<sub><a href="https://github.com/Dray-Ashcroft/Diverticus-Regnatrix">GitHub</a> · Codeberg | Hosted on Cloudflare Pages</sub>
</div>
