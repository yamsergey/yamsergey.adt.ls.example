## Description

Sample Android project to test [Kotlin's LSP](https://github.com/Kotlin/kotlin-lsp) `workspace.json` feature to setup Android project.

## How it works

Project's root contains predefined `workspace.json` with configured dependencies for an android project.

In best case scenario the LSP server has to be able to succesfully read the `workspace.json` and sucesfuly setup the project. 

> In order to test, build the project first to generate sources: `./gradlew assembleDebug`.
