# VSC Essentials - Extension Pack for Visual Studio Code

[![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/Gydunhn.vsc-essentials?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.vsc-essentials) [![Installs](https://flat.badgen.net/vs-marketplace/i/Gydunhn.vsc-essentials?color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.vsc-essentials) [![Downloads](https://flat.badgen.net/vs-marketplace/d/Gydunhn.vsc-essentials?color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.vsc-essentials) [![Rating](https://flat.badgen.net/vs-marketplace/rating/Gydunhn.vsc-essentials?color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.vsc-essentials)

This extension pack for Visual Studio Code adds extensions that are very useful for any development (Language agnostic). I reserve the right to update the extensions pack contents up to my own discretion. This extension is for my personal use, I think it's great if it works for other people too.

## Reasons

The [VSC Essentials extension pack] was made to automate and standardize the installation phase of the essential extensions for Visual Studio Code every time a new member joins the team, or one of them restores a laptop, or exchanges it for a new one.

See the [CHANGELOG](CHANGELOG.md) for the latest changes

## **settings.json**

It is strongly recommended that these settings be used in your workspace. You must copy and paste them, and if you need to adjust something you will already know where to do it.

``` json
{
    // VSCode Config
    "editor.bracketPairColorization.enabled": true,
    "editor.bracketPairColorization.independentColorPoolPerBracketType": true,
    "editor.guides.bracketPairs": "active",
    "editor.guides.indentation": true,
    "editor.tabCompletion": "on",
    "editor.showDeprecated": true,
    "editor.rulers": [
        80
    ],
    "workbench.tree.expandMode": "singleClick",
    "workbench.tree.renderIndentGuides": "always",
    "workbench.tree.indent": 6,
    "workbench.iconTheme": "material-icon-theme",
    // Extensions Config
    "gitlens.blame.avatars": true,
    "gitlens.views.repositories.avatars": true,
    "gitlens.codeLens.authors.enabled": true,
    "todo-tree.highlights.customHighlight": {
        "TODO": {
            "gutterIcon": true,
            "icon": "checklist",
            "iconColour": "DarkOrange",
            "type": "tag",
            "background": "DarkOrange",
            "foreground": "white",
            "fontWeight": "bold"
        },
        "FIXME": {
            "gutterIcon": true,
            "icon": "tools",
            "iconColour": "Lime",
            "type": "tag",
            "background": "Green",
            "foreground": "Yellow",
            "fontWeight": "bold"
        }
    },
    "emojisense.languages": {
        "markdown": true,
        "plaintext": false,
        "json": true,
        "scminput": true
    },
    "formattingToggle.affects": [
        "editor.formatOnPaste",
        "editor.formatOnSave",
        "editor.formatOnType"
    ],
    "[markdown]": {
        "editor.defaultFormatter": "DavidAnson.vscode-markdownlint"
    },
    "[json]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "[xml]": {
        "editor.defaultFormatter": "DotJoshJohnson.xml"
    },
    "markdownlint.config": {
        "default": true,
        "MD001": false,
        "MD010": false,
        "MD024": false,
        "MD025": false
    },
}
```

## Note

This extension pack was made possible by this [article] by [Sanik Bajracharya] on Medium.

## Included

This extension pack includes the following extensions:

| Extension                  | Stats                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| GitLens — Git supercharged | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/eamodio.gitlens?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) [![Installs](https://flat.badgen.net/vs-marketplace/i/eamodio.gitlens?color=blue)](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) [![Rating](https://flat.badgen.net/vs-marketplace/rating/eamodio.gitlens?color=blue)](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)                                                                                                                                                                   |
| Git History                | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/donjayamanne.githistory?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) [![Installs](https://flat.badgen.net/vs-marketplace/i/donjayamanne.githistory?color=blue)](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) [![Rating](https://flat.badgen.net/vs-marketplace/rating/donjayamanne.githistory?color=blue)](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)                                                                                                                   |
| gitignore                  | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/codezombiech.gitignore?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore) [![Installs](https://flat.badgen.net/vs-marketplace/i/codezombiech.gitignore?color=blue)](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore) [![Rating](https://flat.badgen.net/vs-marketplace/rating/codezombiech.gitignore?color=blue)](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)                                                                                                                         |
| Todo Tree                  | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/Gruntfuggly.todo-tree?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree) [![Installs](https://flat.badgen.net/vs-marketplace/i/Gruntfuggly.todo-tree?color=blue)](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree) [![Rating](https://flat.badgen.net/vs-marketplace/rating/Gruntfuggly.todo-tree?color=blue)](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)                                                                                                                               |
| Color Highlight            | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/naumovs.color-highlight?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) [![Installs](https://flat.badgen.net/vs-marketplace/i/naumovs.color-highlight?color=blue)](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) [![Rating](https://flat.badgen.net/vs-marketplace/rating/naumovs.color-highlight?color=blue)](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)                                                                                                                   |  |
| indent-rainbow             | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/oderwat.indent-rainbow?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow) [![Installs](https://flat.badgen.net/vs-marketplace/i/oderwat.indent-rainbow?color=blue)](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow) [![Rating](https://flat.badgen.net/vs-marketplace/rating/oderwat.indent-rainbow?color=blue)](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)                                                                                                                         |
| Material Icon Theme        | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/PKief.material-icon-theme?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) [![Installs](https://flat.badgen.net/vs-marketplace/i/PKief.material-icon-theme?color=blue)](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) [![Rating](https://flat.badgen.net/vs-marketplace/rating/PKief.material-icon-theme?color=blue)](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)                                                                                                       |
| Bookmarks                  | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/alefragnani.Bookmarks?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) [![Installs](https://flat.badgen.net/vs-marketplace/i/alefragnani.Bookmarks?color=blue)](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) [![Rating](https://flat.badgen.net/vs-marketplace/rating/alefragnani.Bookmarks?color=blue)](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)                                                                                                                               |
| Path Intellisense          | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/christian-kohler.path-intellisense?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) [![Installs](https://flat.badgen.net/vs-marketplace/i/christian-kohler.path-intellisense?color=blue)](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) [![Rating](https://flat.badgen.net/vs-marketplace/rating/christian-kohler.path-intellisense?color=blue)](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)                                                 |
| Formatting Toggle          | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/tombonnike.vscode-status-bar-format-toggle?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=tombonnike.vscode-status-bar-format-toggle) [![Installs](https://flat.badgen.net/vs-marketplace/i/tombonnike.vscode-status-bar-format-toggle?color=blue)](https://marketplace.visualstudio.com/items?itemName=tombonnike.vscode-status-bar-format-toggle) [![Rating](https://flat.badgen.net/vs-marketplace/rating/tombonnike.vscode-status-bar-format-toggle?color=blue)](https://marketplace.visualstudio.com/items?itemName=tombonnike.vscode-status-bar-format-toggle) |
| Markdown All in One        | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/yzhang.markdown-all-in-one?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) [![Installs](https://flat.badgen.net/vs-marketplace/i/yzhang.markdown-all-in-one?color=blue)](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) [![Rating](https://flat.badgen.net/vs-marketplace/rating/yzhang.markdown-all-in-one?color=blue)](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)                                                                                                 |
| Terminal in Status Bar     | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/flyfly6.terminal-in-status-bar?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=flyfly6.terminal-in-status-bar) [![Installs](https://flat.badgen.net/vs-marketplace/i/flyfly6.terminal-in-status-bar?color=blue)](https://marketplace.visualstudio.com/items?itemName=flyfly6.terminal-in-status-bar) [![Rating](https://flat.badgen.net/vs-marketplace/rating/flyfly6.terminal-in-status-bar?color=blue)](https://marketplace.visualstudio.com/items?itemName=flyfly6.terminal-in-status-bar)                                                                         |
| CodeSnap                   | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/adpyke.codesnap?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap) [![Installs](https://flat.badgen.net/vs-marketplace/i/adpyke.codesnap?color=blue)](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap) [![Rating](https://flat.badgen.net/vs-marketplace/rating/adpyke.codesnap?color=blue)](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap)                                                                                                                                                                   |
| Git Graph                  | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/mhutchie.git-graph?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph) [![Installs](https://flat.badgen.net/vs-marketplace/i/mhutchie.git-graph?color=blue)](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph) [![Rating](https://flat.badgen.net/vs-marketplace/rating/mhutchie.git-graph?color=blue)](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)                                                                                                                                                 |
| markdownlint               | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/DavidAnson.vscode-markdownlint?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) [![Installs](https://flat.badgen.net/vs-marketplace/i/DavidAnson.vscode-markdownlint?color=blue)](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) [![Rating](https://flat.badgen.net/vs-marketplace/rating/DavidAnson.vscode-markdownlint?color=blue)](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)                                                                         |
| XML Tools                  | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/DotJoshJohnson.xml?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml) [![Installs](https://flat.badgen.net/vs-marketplace/i/DotJoshJohnson.xml?color=blue)](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml) [![Rating](https://flat.badgen.net/vs-marketplace/rating/DotJoshJohnson.xml?color=blue)](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)                                                                                                                                                 |
| Better Comments            | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/aaron-bond.better-comments?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) [![Installs](https://flat.badgen.net/vs-marketplace/i/aaron-bond.better-comments?color=blue)](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) [![Rating](https://flat.badgen.net/vs-marketplace/rating/aaron-bond.better-comments?color=blue)](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)                                                                                                 |
| Rainbow CSV                | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/mechatroner.rainbow-csv?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv) [![Installs](https://flat.badgen.net/vs-marketplace/i/mechatroner.rainbow-csv?color=blue)](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv) [![Rating](https://flat.badgen.net/vs-marketplace/rating/mechatroner.rainbow-csv?color=blue)](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)                                                                                                                   |
| :emojisense:               | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/bierner.emojisense?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=bierner.emojisense) [![Installs](https://flat.badgen.net/vs-marketplace/i/bierner.emojisense?color=blue)](https://marketplace.visualstudio.com/items?itemName=bierner.emojisense) [![Rating](https://flat.badgen.net/vs-marketplace/rating/bierner.emojisense?color=blue)](https://marketplace.visualstudio.com/items?itemName=bierner.emojisense)                                                                                                                                                 |

[vsc essentials extension pack]: https://marketplace.visualstudio.com/items?itemName=Gydunhn.vsc-essentials
[sanik bajracharya]: https://medium.com/@sanik.bajracharya
[article]: https://medium.com/@sanik.bajracharya/vscode-how-to-create-your-own-extension-pack-483385644c29
