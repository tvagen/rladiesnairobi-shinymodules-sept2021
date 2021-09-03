---
theme : "night"
transition: "slide"
highlightTheme: "monokai"
logoImg: "https://www.worldagroforestry.org/sites/agroforestry/files/styles/staff_image_style/public/staff/Tor-Gunnar%20Vagen.jpg?itok=VEMU08UO"
slideNumber: true
title: "satRday Nairobi"
---

# satRday Nairobi

Dr Tor-G. Vågen

04/07/2021

---

## Shiny modules

Allow you to break your Shiny app into smaller, and more manageable pieces

![Modules...](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTwXyNwjluWJ7UgPD5HYN4fI-tVN8EGQzdKSQ&usqp=CAU)

--

### Use cases / Scenarios

- Your app is quite complex and has many "moving" parts
- Your app is becoming difficult to maintain
- You are working in a team developing different components of an app
- Some elements of your app need to be more frequently updated than others
- You would like to reuse elements of a Shiny app somewhere else

...name another one in the chat...

--

_A Shiny module has its own UI and Server logic_

---

Shiny modules are actually not that advanced, but can be used to develop incredibly rich (and advanced) Shiny apps...

... and they will make your life much easier!

![Killer visual strategies](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRGCcnQ3GyrnVGxBBi4qCdEZ1RBY0oGrCDq9A&usqp=CAU)

--

## Let's get started...

- We are going to build a simple **dashboard** of population data in Kenya using _Shel Kariuki's rKenyaCensus_ R library.
- We will develop two modules:
  - A landing page (home) module
  - A map module showing population by county
  - We will use Microsoft's Fluent UI (shiny.fluent & shiny.react from appsilon.com)

--

The github repository containing the code is here:

https://github.com/tvagen/rladiesnairobi-shinymodules-sept2021