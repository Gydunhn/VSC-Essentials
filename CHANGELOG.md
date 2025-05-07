# Change Log

All notable changes to the VSC Essentials - Extension Pack for Visual Studio Code will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.0.0] - 2025-05-07

***Version 2.0.0 of this extension package marks a significant milestone, introducing a comprehensive reorganization of extensions to better align with our updated development strategy. This major update restructures the entire package to provide clearer organization of tools by function and purpose, enabling more efficient workflows across different project types.***

### Added

* Paste JSON as Code (quicktype) - A powerful tool that allows developers to convert JSON data into strongly typed code in multiple programming languages, including TypeScript, C#, Java, Swift, and many others. This addition enhances productivity when working with APIs and data structures.

### Changed

* Complete reorganization of the extension pack structure to create a more logical and function-based grouping:
  * Moved all language-agnostic core extensions to the VSC-Essentials-Core package
  * Grouped remaining extensions by functionality categories:
    * Core Package
    * Version Control tools
    * Visualization and Preview tools
    * File Support tools
    * Others

### Removed

* The following extensions have been moved to VSC-Essentials-Core package to create a cleaner, more focused base package of truly essential extensions:
  * Better Comments, by Aaron Bond
  * Todo Tree, by Gruntfuggly
  * Terminal in Status Bar, by flyfly6
  * Bookmarks, by Alessandro Fragnani
  * indent-rainbow, by oderwat
  * Error Lens, by usernamehw
  * Output Colorizer, by IBM
  * All Markdown related extensions - Moved to Core as documentation is essential for all projects:
    * Markdown All in One, by Yu Zhang
    * markdownlint, by David Anson
    * :emojisense:, by Matt Bierner
    * Markdown Emoji, by Matt Bierner
    * Markdown Checkboxes, by Matt Bierner

### Restructured

* Version Control tools are now grouped together in the main package:
  * Git Graph, by mhutchie
  * GitLens — Git supercharged, by GitKraken
  * Git History, by Don Jayamanne
  * gitignore, by CodeZombie
* Visualization and Preview tools grouped together:
  * Image preview, by Kiss Tamás
  * SVG Previewer, by Vitalii Mazurenko
  * CodeSnap, by adpyke
* File Support tools grouped for better organization:
  * XML Tools, by Josh Johnson
  * Rainbow CSV, by mechatroner
  * Paste JSON as Code, by quicktype
* Others:
  * Color Highlight, by naumovs
  * VSC-Essentials-Themes-Core, by Gydunhn
  * VSC-Essentials-Material-Themes, by Gydunhn

This major restructuring provides a more intuitive organization of extensions, making it easier for developers to understand what each package provides and ensuring better performance by only loading the extensions relevant to specific workflows.

## [1.0.2] - 2025-03-15

### Removed

* Console Ninja, By Wallaby.js. Because it caused a serious problem with the system console on three different macOS computers in less than a week, altering global variables, which disrupted the development environment.

## [1.0.1] - 2025-03-04

### Added

* Console Ninja, By Wallaby.js.
* Error Lens, By Alexander.
* Image preview, By Kiss Tamás.

## [1.0.0] - 2025-03-04

***Version 1.0.0 of this extension package marks a significant milestone, as it introduces a more organized restructuring of extensions. This reordering is designed to better meet the diverse needs of our development team, ensuring that each component is strategically placed to enhance workflow and productivity. By addressing the specific requirements of developers working on our projects, this update aims to provide a more cohesive and efficient development environment.***

### Added

* VSC-Essentials-Core, By Gydunhn.
* VSC-Essentials-Themes-Core, By Gydunhn.
* VSC-Essentials-Material-Themes, By Gydunhn.

### Removed

* The following list of extensions has been removed from the current package to be included in the Core version. This change is primarily for organizational purposes and ensures a more structured approach to managing essential tools. Rest assured, none of these extensions will be lost, as the Core version is integrated within this package. This reorganization aims to provide a streamlined experience, maintaining accessibility to all necessary extensions while enhancing overall usability.
  * Markdown All in One, By Yu Zhang.
  * markdownlint, By David Anson.
  * :emojisense:, By Matt Bierner.
  * Markdown Emoji, By Matt Bierner.
  * XML Tools, By Josh Johnson.
  * Todo Tree, By Gruntfuggly.
  * Git Graph, By mhutchie.
  * GitLens — Git supercharged, By GitKraken.
  * Git History, By Don Jayamanne.
  * gitignore, By CodeZombie.
  * Terminal in Status Bar, By flyfly6.
  * Better Comments, By Aaron Bond.

* Similar to the previous list, the following extensions have been moved to other packages that are also part of the current suite. This reorganization is aimed at creating a more modular structure, allowing for better management and scalability. You can rest assured that none of these extensions will be lost, as they remain accessible within the broader package ecosystem. This approach ensures that all necessary tools are available while maintaining a clean and efficient extension setup.
  * Material Icon Theme, by Philipp Kief.
  * Output Colorizer, by IBM.

## [0.6.0] - 2024-01-09

### Added

* Markdown Emoji, Matt Bierner.

## [0.5.9] - 2024-01-09

### Added

* Output Colorizer, IBM.

## [0.5.8] - 2023-02-18

### Changed

* Fixed inconsistency in settings.json file.
* Fixed inconsistency in README.md file.

## [0.5.7] - 2023-02-18

### Added

* SVG Previewer, By Vitalii Mazurenko.
* A Hidden Special Edition of this extension. 🙊

### Changed

* Reorder the Extensions List, in order to restructure the extensions package.
* The Readme is reordered too, with the same purpose as before.
* The settings in the settings.json file are updated.

### Removed

* Path Intellisense, By Christian Kohler. It was moved to the Extension Pack Javascript-Essentials.
* Formatting Toggle, By tombonnike.  It was moved to the Extension Pack Javascript-Essentials too.

## ~~0.5.6 - Got lost in Space~~
~~To boldly go where no man has gone before ✨ 🚀 ☄️~~

## [0.5.5] - 2023-02-15

### Added

* :emojisense:, At the request of some developers, so that the rest of the team learns to use it.

### Removed

* Code Spell Checker, due to the invasiveness of the extension, many developers from our team, in different cells, complained about it, so it will be returned to its previous status of recommended and optional and not mandatory.
* Code Runner, due to an incompatibility problem in a layer of the stack, so it will be returned to its previous status of recommended and optional and not mandatory.
* TODO Highlight v2, due to its little use. additionally Todo Tree brings us the same functionalities.

## [0.5.4] - 2023-02-01

### Added

* Code Runner, Run code snippet or code file for multiple languages. This extension is added as a complement to 'Terminal in Status Bar', as together they generate a complete replacement to Jun Han's deprecated Terminal extension.
* Code Spell Checker, A basic spell checker that works well with code and documents.

## [0.5.3] - 2023-01-31

### Added

* Rainbow CSV, Highlight columns in comma (.csv), tab (.tsv), semicolon and pipe - separated files in different colors.

### Changed

* ReadMe Badges

## [0.5.2] - 2022-10-14

### Added

* Terminal in Status Bar, as a (kind of) temporary replacement for Terminal by Jun Han.
* Better Comments, Improve your code commenting by annotating with alert, informational, TODOs, and more!

### Removed

* Terminal by Jun Han, is no longer being maintained (#formulahendry/vscode-terminal).

## [0.5.1] - 2022-03-28

### Removed

* Bracket Pair Colorizer. Bracket Pair Colorizer 2 is no longer being maintained (#CoenraadS/Bracket-Pair-Colorizer-2#475). and is Officialy integrated to VSC.

## [0.5.0] - 2021-04-07

### Removed  

* Polacode. Polacode doesn't work after VSCode 1.47 (#octref/polacode#143).

### Added  

* CodeSnap.

## [0.4.0] - 2021-01-18

### Changed

* Updated "TODO Highlight" to point to its successor, More information can be found in [Issue #187 on the outdated repository](wayou/vscode-todo-highlight#187) and [Issue #16 on the successor repository](jgclark/vscode-todo-highlight#16).

## [0.3.2] - 2020-10-06

### Changed

* Compatibility with vsCode 1.35.0 x32

## [0.3.1] - 2020-08-28

### Changed

* the KeyWords were modified

## [0.3.0] - 2020-06-10

### Added

* XML Tools Extension.
  
## [0.2.0] - 2020-04-27

### Added

* markdownlint Extension.

## [0.1.0] - 2020-04-27

### Added

* Polacode Extension.
* Git Graph.

## [0.0.3] - 2020-04-25

### Added

* Keywords added & reordered.
* Changelog fixed, in order to keep the format.
* A link to the visual studio marketplace in the readme.md.

## [0.0.2] - 2020-04-25

### Fixed

* Changelog repository url's.
  
### Added

* Keywords added.

## [0.0.1] - 2020-04-25

### Added

* Initial release.
  * Created extension pack.

[Unreleased]: https://github.com/Gydunhn/VSC-Essentials/tree/develop
[2.0.0]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/2.0.0
[1.0.2]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/1.0.2
[1.0.1]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/1.0.1
[1.0.0]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/1.0.0
[0.6.0]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.6.0
[0.5.9]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.5.9
[0.5.8]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.5.8
[0.5.7]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.5.7
[0.5.5]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.5.5
[0.5.4]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.5.4
[0.5.3]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.5.3
[0.5.2]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.5.2
[0.5.1]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.5.1
[0.5.0]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.5.0
[0.4.0]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.4.0
[0.3.2]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.3.2
[0.3.1]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.3.1
[0.3.0]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.3.0
[0.2.0]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.2.0
[0.1.0]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.1.0
[0.0.3]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.0.3
[0.0.2]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.0.2
[0.0.1]: https://github.com/Gydunhn/VSC-Essentials/releases/tag/0.0.1
