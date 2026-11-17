# 🏁 Need for Speed: Most Wanted — The Blacklist Archive

A fan-made digital fanzine and archive celebrating *Need for Speed: Most Wanted* (2005). Explore Rockport, its Blacklist drivers, the BMW M3 GTR, and media inspired by the game through a responsive, multi-page website.

## 🎮 Website features

- 🏠 **Home** — cinematic introduction, featured car gallery, and archive highlights.
- 🗺️ **Rockport** — schematic city map, district notes, and related location links.
- 🚘 **The car** — BMW M3 GTR dossier, image gallery, specifications, and story.
- 🏆 **Blacklist** — all 15 rivals, with driver search and sorting.
- 🎞️ **Media archive** — featured video and archive items with category filters and search.
- 📱 Shared navigation, responsive layouts, and locally bundled images, video, and audio assets.

## 🚀 Run the source project

The editable website source is in `Source Code/`. You need [Node.js](https://nodejs.org/) 22.12.0 or later and npm.

```sh
cd "Source Code"
npm ci
npm run dev
```

Open the local address printed in the terminal (usually `http://localhost:4321`). Stop the development server with `Ctrl+C`.

### 🛠️ Build and preview

Run these commands from `Source Code/`:

```sh
npm run build
npm run preview
```

The production build is written to `Source Code/dist/`. `npm run preview` serves that build locally.

## 🧰 Technology

- [Astro](https://astro.build/) for pages, layouts, and reusable components.
- [Tailwind CSS](https://tailwindcss.com/) and [DaisyUI](https://daisyui.com/) dependencies for styling.
- Custom browser-side JavaScript for galleries, navigation, filtering, search, and sorting.

## 📂 Project contents

| Path | Contents |
| --- | --- |
| `Source Code/` | Astro source, styles, static assets, package scripts, and a source-specific README. |
| `Compiled Code/` | Included compiled website pages and their assets. |
| `Wireframes/` | Website planning and design materials. |
| `Game Plan.txt` | Project concept and assignment workflow notes. |
| `HCI-UX Assignment 1 - 2026 - FINAL.pdf` | Assignment brief. |
| `MY REPORT.docx` | Project report. |
| `Personas.pdf`, `Persona_Template_1.docx`, `Group Work Persona_Template_COMPLETE.docx` | Persona materials and template. |
| `COMPULSORY_CSCU9X5_coversheet_Template_SEPT-2026.docx` | Assignment coversheet template. |
| `Web Design Concept Approval Form 2026.docx` | Concept approval material. |
| `report imports/` | Supporting report materials. |

To work on the website, use `Source Code/`; the compiled export is provided separately in `Compiled Code/`.

## ℹ️ Credits and scope

This is an unofficial, fan-made student project created for an HCI/UI/UX assignment. *Need for Speed: Most Wanted*, related names, and game imagery belong to their respective rights holders. Refer to the project report for the assignment’s detailed sources and acknowledgements.