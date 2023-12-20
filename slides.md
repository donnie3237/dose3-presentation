---
theme : apple-basic
layout : intro
class: text-center
highlighter: shikiji
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
transition: slide-left
title: Welcome to Slidev
mdc: true
---
<h1 class="font-bold"> Welcome to DOSE3</h1>

## Best Starter kit for you
<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-10 py-2 rounded-3xl cursor-pointer font-bold" hover="bg-white bg-opacity-10">
    Get strates <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>
---
layout: image-right
image: >-
  https://img.freepik.com/free-vector/hand-painted-watercolor-pastel-sky-background_23-2148902771.jpg
---

<div class="mt-10"></div>

# Table of content

<Toc maxDepth="1"></Toc>


---
transition: slide-left
---

<div class="mt-6"></div>

# What is dose3

dose3 is best starter kit to make your project faster and basic standardof code
- 📝 **Template** - focus on the content with Markdown, and then style them later
- 🎨 **Frommatter** - theme can be shared and used with npm packages
- 🧑‍💻 **Dev fast** - code highlighting, live coding with autocompletion
- 🤹 **Easy to use** - embedding Vue components to enhance your expressions
- 📤 **Minimize** - export into PDF, PNGs, or even a hostable SPA
- 🛠 **Testing** - anything possible on a webpage

<br>
<br>

Read more about [dose3](https://dose3.dxse)

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: slide-up
---

# Framework and Lib

|     |     |
| --- | --- |
| ReactJS , SolidjS | for react deverloper base |
| VueJS | for vue deverloper |
| ExpressJS | basic api in javascript |
| Fastify | fast api in javascript code  |
| NextJS , Astro | for rendering framework |
| Actix-web | for blazingly fast and low cost api |
| Tauri | for native mobile app and desktop app |

---
transition: slide-left
---

# Integration

|     |     |
| --- | --- |
| Vitest | for react deverloper base |
| Biome | for vue deverloper |
| Prisma | basic api in javascript |
| Mongoose | fast api in javascript code  |
| Sqlx | fast api in javascript code  |
| Zustand | for rendering framework |

---
class: px-20
---

# Document

Slidev comes with powerful theming support. Themes can provide styles, layouts, components, or even configurations for tools. Switching between themes by just **one edit** in your frontmatter:

<div><img src="/dose3.png" class="h-[50vh]"/></div>

read the [docs](https://dose3.dxse.site/).

---
class: px-20
---
# How it work


<div class="h-[70vh] flex w-[100%]">

```plantuml
@startuml

package " Dose3 " {
  [dose3 installation]
  [dose3 cli]
}

cloud {
  [ npm cloud ]
}

node "PC" {
  [Floder]
}

database "Git" {
  [my Template]
}
[vscode]

[dose3 installation] <-- [ npm cloud ] : get data from npm
[dose3 cli] <-- [my Template] : use git clone
[dose3 cli] --> [my Template] : send template required
[Floder] <-right- [dose3 cli] : save it
[Floder] -right-> [vscode]
@enduml
```
</div>

---
layout: center
class: text-center
---

# Learn More

[Documentations](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/showcases.html)
