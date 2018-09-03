# 😤 ➡️ 🤣

Errors can be frustrating, but could they also be fun?

This repo is inspired by a [random tweet](https://twitter.com/minebocek/status/1035377949036486656) of mine which made me realize that there are others out there who enjoy emoji puzzles.

Deciphering errors can be difficult and frustrating, but maybe seeing them in emoji form would help lighten things a bit?

Note that I'm not suggesting we replace R errors with emojis (that might make them even more frustrating!), but I can see a venue for these in blog posts, talks, etc.

## Contribute

If you have suggestions for R error/emoji translations to add, please submit a pull request or add an issue. 

You can submit a translation with or without additional explanation, or add explanation to someone else's submission.

### Without explanation, aka `verbose = FALSE`

Add your translation to the appropriate section, make sure the emojis render properly (and look the way you want them to look) on GitHub, and you're done!

### With explanation, aka `verbose = TRUE`

Everything above, plus

- 📦: indicate the package that the error is specifically associated with (if any),
- ❓: include a brief sentence describing when users might expect to see the error (with the aim of helping those who are unfamiliar with the error), and
- ✅: briefly (and generically) describe how you would debug the error.

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

## Translate

### `verbose = FALSE`

- Package or namespace load failed: 📦/📛🌌 🚚 ☹️

- Exited with status 1: 🚶‍♂️⬅️🚪  🔱  👑  1️⃣

- Execution halted: 💉🛑

### `verbose = TRUE`

- Operation not allowed without an active reactive context: 👩‍⚕️🔪 🚫 ❌ 🏃‍↔️ 📖
    - 📦: [shiny](http://shiny.rstudio.com/)
    - ❓: You are trying to access a "reactive" element inside the Shiny `server` function, but outside any of the reactive functions such as `renderTable()` or `renderPlot()` etc.
    - ✅: Wrap it inside a `reactive()` or place inside a `render*()` function.
