[![JetBrains Marketplace](https://img.shields.io/jetbrains/plugin/v/31745?label=Marketplace)](https://plugins.jetbrains.com/plugin/31745)
[![JetBrains Marketplace Downloads](https://img.shields.io/jetbrains/plugin/d/31745)](https://plugins.jetbrains.com/plugin/31745)
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/nahoj/jetbrains-collapse-markdown-details/total)](https://github.com/nahoj/jetbrains-collapse-markdown-details/releases)
[![GitHub commits since latest release](https://img.shields.io/github/commits-since/nahoj/jetbrains-collapse-markdown-details/latest)](https://github.com/nahoj/jetbrains-collapse-markdown-details/commits)

A simple, hacky plugin for JetBrains IDEs that makes `<details></details>` sections in Markdown files collapsed by default.

You can install it directly from your IDE, from [the Marketplace](https://plugins.jetbrains.com/plugin/31745), or from source.

**Status:** Works better than nothing. Expect only minimal maintenance. Discussion is nevertheless welcome!

## Installing From Source

Create `local.properties` from the example if you want Gradle to use your local JetBrains IDE and save the 10+ GB of cache storage.

`./gradlew buildPlugin` creates the zip in `build/distributions`.

`./gradlew runIde` runs the sandbox IDE with the plugin installed.
