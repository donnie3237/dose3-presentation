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
  <a href="https://github.com/donnie3237" target="_blank" alt="GitHub" title="Open in GitHub"
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
- 📝 **Template** - yeah we are template with cool framework
- 🎨 **Frommatter** - frommat your code easier with biomejs
- 🧑‍💻 **Dev fast** - make project fast for freelancer
- 🤹 **Easy to use** - dose3 is easy to use with clean documentation
- 📤 **Minimize** - use the lightweight and fast cli in your local storage
- 🛠 **Testing** - testing your app with vitest 

<br>
<br>

Read more about [dose3](https://dose3.dxse.site)

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
| Vitest | unit test framework for your web app |
| Biome | frommatter and lint in one lib |
| Prisma | ORM for your SQL database protect SQL injection |
| Mongoose | easy to manage your database and server  |
| Sqlx | ORM for rust lang  |
| Zustand | Global state in your client side |
| TailwindCSS | write your style in class propities |

---
class: px-20
---

# Document

the document make with astro starlightjs lets read the [docs](https://dose3.dxse.site/).

<div><img src="/dose3.png" class="h-[50vh] mx-auto"/></div>



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

[Documentations](https://dose3.dxse.site) · [GitHub](https://github.com/slidevjs/slidev) 
