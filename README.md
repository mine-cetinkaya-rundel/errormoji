# 😤 ➡️ 🤣

Errors can be frustrating, but could they also be fun?

This repo is inspired by a [random tweet](https://twitter.com/minebocek/status/1035377949036486656) of mine which made me realize that there are others out there who enjoy emoji puzzles.

Deciphering errors can be difficult and frustrating, but maybe seeing them in emoji form would help lighten things a bit?

Note that I'm not suggesting we replace R errors with emojis (that might make them even more frustrating!), but I can see a venue for these in blog posts, class notes, talks, etc.

If you have suggestions for R error/emoji translations to add, please see the [contributing guidelines]().

## Translations

### `verbose = FALSE`

- Package or namespace load failed: 📦/📛🌌 🚚 ☹️

- Exited with status 1: 🚶‍♂️⬅️🚪  🔱  👑  1️⃣

### `verbose = TRUE`

- Operation not allowed without an active reactive context: 👩‍⚕️🔪 🚫 ❌ 🏃‍↔️ 📖
    - 📦: [shiny](http://shiny.rstudio.com/)
    - ❓: You are trying to access a "reactive" element inside the Shiny `server` function, but outside any of the reactive functions such as `renderTable()` or `renderPlot()` etc.
    - ✅: Wrap it inside a `reactive()` or place inside a `render*()` function.
