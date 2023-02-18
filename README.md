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
    /**
     * VSC Essentials Config
     */
    "editor.tabCompletion": "on",
    "editor.showDeprecated": true,
    "editor.rulers": [
        80
    ],
    "editor.guides.bracketPairs": "active",
    "editor.bracketPairColorization.independentColorPoolPerBracketType": true,
    "workbench.tree.expandMode": "singleClick",
    "workbench.tree.renderIndentGuides": "always",
    "workbench.tree.indent": 6,
    "editor.formatOnType": false,
    "editor.formatOnSave": true,
    "editor.formatOnPaste": true,
    "[markdown]": {
        "editor.defaultFormatter": "yzhang.markdown-all-in-one"
    },
    "[json]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "[jsonc]": {
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
    "todo-tree.tree.showCountsInTree": true,
    "todo-tree.general.statusBar": "top three",
    "todo-tree.general.showIconsInsteadOfTagsInStatusBar": true,
    "todo-tree.general.tags": [
        "TODO",
        "FIXME",
        "FIXIT",
        "FIX",
        "BUG"
    ],
    "todo-tree.general.tagGroups": {
        "FIXME": [
            "FIXME",
            "FIXIT",
            "FIX",
            "BUG",
        ]
    },
    "todo-tree.highlights.customHighlight": {
        "TODO": {
            "gutterIcon": true,
            "icon": "tasklist",
            "iconColour": "#FF8C00",
            "type": "tag",
            "background": "#CF7200",
            "foreground": "#FFFFFF",
            "fontWeight": "bold"
        },
        "FIXME": {
            "gutterIcon": true,
            "icon": "tools",
            "iconColour": "#00FF00",
            "type": "tag",
            "background": "#008000",
            "foreground": "#FFFF00",
            "fontWeight": "bold"
        }
    },
    "better-comments.multilineComments": true,
    "better-comments.tags": [
        {
            "tag": "!",
            "color": "#FF2D00",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": true,
            "italic": false
        },
        {
            "tag": "?",
            "color": "#3498DB",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        },
        {
            "tag": "//",
            "color": "#474747",
            "strikethrough": true,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        },
        {
            "tag": "todo",
            "color": "#FF8C00",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        },
        {
            "tag": "fixme",
            "color": "#008000",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        },
        {
            "tag": "fixit",
            "color": "#008000",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        },
        {
            "tag": "fix",
            "color": "#008000",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        },
        {
            "tag": "bug",
            "color": "#008000",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        },
        {
            "tag": "*",
            "color": "#98C379",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": true,
            "italic": false
        }
    ],
    "editor.stickyScroll.enabled": true,
    "svg.preview.autoOpen": false,
    "emojisense.languages": {
        "plaintext": false,
        "markdown": true,
        "json": true,
        "scminput": true
    },
    "terminal-in-status-bar.statusBarAlignment": "right",
    "terminal-in-status-bar.statusBarPriority": 10000,
    "indentRainbow.ignoreErrorLanguages": [
        "haskell"
    ],
    "bookmarks.saveBookmarksInProject": false,
    "bookmarks.showCommandsInContextMenu": true,
    "git-graph.commitDetailsView.location": "Docked to Bottom",
    "git-graph.contextMenuActionsVisibility": {
        "remoteBranch": {
            "checkout": false,
            "cherrypick": false,
            "createBranch": false,
            "createPullRequest": false,
            "delete": false,
            "drop": false,
            "merge": false,
            "pull": false,
            "rebase": false,
            "reset": false,
            "revert": false,
        },
        "branch": {
            "checkout": false,
            "cherrypick": false,
            "createBranch": false,
            "createPullRequest": false,
            "delete": false,
            "drop": false,
            "merge": false,
            "push": false,
            "rename": false,
            "rebase": false,
            "reset": false,
            "revert": false,
        },
        "commit": {
            "checkout": false,
            "cherrypick": false,
            "createBranch": false,
            "drop": false,
            "merge": false,
            "rebase": false,
            "reset": false,
            "revert": false,
        }
    },
    "gitlens.statusBar.enabled": true,
    "gitlens.statusBar.command": "gitlens.openCommitOnRemote",
    "gitlens.blame.avatars": true,
    "gitlens.hovers.avatars": true,
    "gitlens.hovers.avatarSize": 64,
    "gitlens.hovers.changesDiff": "hunk",
    "codesnap.roundedCorners": true,
    "codesnap.containerPadding": "2em",
    "codesnap.showWindowTitle": true,
    "codesnap.realLineNumbers": true,
}

```

## Note

This extension pack was made possible by this [article] by [Sanik Bajracharya] on Medium.  
[This extension] can be found at [open-vsx.org] as well.

## Included

This extension pack includes the following extensions:

| Extension                  | Stats                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Markdown All in One        | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/yzhang.markdown-all-in-one?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) [![Installs](https://flat.badgen.net/vs-marketplace/i/yzhang.markdown-all-in-one?color=blue)](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) [![Rating](https://flat.badgen.net/vs-marketplace/rating/yzhang.markdown-all-in-one?color=blue)](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)                               |
| markdownlint               | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/DavidAnson.vscode-markdownlint?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) [![Installs](https://flat.badgen.net/vs-marketplace/i/DavidAnson.vscode-markdownlint?color=blue)](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) [![Rating](https://flat.badgen.net/vs-marketplace/rating/DavidAnson.vscode-markdownlint?color=blue)](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)       |
| XML Tools                  | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/DotJoshJohnson.xml?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml) [![Installs](https://flat.badgen.net/vs-marketplace/i/DotJoshJohnson.xml?color=blue)](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml) [![Rating](https://flat.badgen.net/vs-marketplace/rating/DotJoshJohnson.xml?color=blue)](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)                                                                               |
| Rainbow CSV                | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/mechatroner.rainbow-csv?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv) [![Installs](https://flat.badgen.net/vs-marketplace/i/mechatroner.rainbow-csv?color=blue)](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv) [![Rating](https://flat.badgen.net/vs-marketplace/rating/mechatroner.rainbow-csv?color=blue)](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)                                                 |
| SVG Previewer              | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/vitaliymaz.vscode-svg-previewer?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=vitaliymaz.vscode-svg-previewer) [![Installs](https://flat.badgen.net/vs-marketplace/i/vitaliymaz.vscode-svg-previewer?color=blue)](https://marketplace.visualstudio.com/items?itemName=vitaliymaz.vscode-svg-previewer) [![Rating](https://flat.badgen.net/vs-marketplace/rating/vitaliymaz.vscode-svg-previewer?color=blue)](https://marketplace.visualstudio.com/items?itemName=vitaliymaz.vscode-svg-previewer) |
| Color Highlight            | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/naumovs.color-highlight?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) [![Installs](https://flat.badgen.net/vs-marketplace/i/naumovs.color-highlight?color=blue)](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) [![Rating](https://flat.badgen.net/vs-marketplace/rating/naumovs.color-highlight?color=blue)](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)                                                 |  |
| Todo Tree                  | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/Gruntfuggly.todo-tree?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree) [![Installs](https://flat.badgen.net/vs-marketplace/i/Gruntfuggly.todo-tree?color=blue)](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree) [![Rating](https://flat.badgen.net/vs-marketplace/rating/Gruntfuggly.todo-tree?color=blue)](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)                                                             |
| Terminal in Status Bar     | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/flyfly6.terminal-in-status-bar?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=flyfly6.terminal-in-status-bar) [![Installs](https://flat.badgen.net/vs-marketplace/i/flyfly6.terminal-in-status-bar?color=blue)](https://marketplace.visualstudio.com/items?itemName=flyfly6.terminal-in-status-bar) [![Rating](https://flat.badgen.net/vs-marketplace/rating/flyfly6.terminal-in-status-bar?color=blue)](https://marketplace.visualstudio.com/items?itemName=flyfly6.terminal-in-status-bar)       |
| indent-rainbow             | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/oderwat.indent-rainbow?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow) [![Installs](https://flat.badgen.net/vs-marketplace/i/oderwat.indent-rainbow?color=blue)](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow) [![Rating](https://flat.badgen.net/vs-marketplace/rating/oderwat.indent-rainbow?color=blue)](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)                                                       |
| Better Comments            | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/aaron-bond.better-comments?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) [![Installs](https://flat.badgen.net/vs-marketplace/i/aaron-bond.better-comments?color=blue)](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) [![Rating](https://flat.badgen.net/vs-marketplace/rating/aaron-bond.better-comments?color=blue)](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)                               |
| Bookmarks                  | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/alefragnani.Bookmarks?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) [![Installs](https://flat.badgen.net/vs-marketplace/i/alefragnani.Bookmarks?color=blue)](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) [![Rating](https://flat.badgen.net/vs-marketplace/rating/alefragnani.Bookmarks?color=blue)](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)                                                             |
| Git Graph                  | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/mhutchie.git-graph?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph) [![Installs](https://flat.badgen.net/vs-marketplace/i/mhutchie.git-graph?color=blue)](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph) [![Rating](https://flat.badgen.net/vs-marketplace/rating/mhutchie.git-graph?color=blue)](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)                                                                               |
| GitLens — Git supercharged | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/eamodio.gitlens?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) [![Installs](https://flat.badgen.net/vs-marketplace/i/eamodio.gitlens?color=blue)](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) [![Rating](https://flat.badgen.net/vs-marketplace/rating/eamodio.gitlens?color=blue)](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)                                                                                                 |
| Git History                | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/donjayamanne.githistory?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) [![Installs](https://flat.badgen.net/vs-marketplace/i/donjayamanne.githistory?color=blue)](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) [![Rating](https://flat.badgen.net/vs-marketplace/rating/donjayamanne.githistory?color=blue)](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)                                                 |
| gitignore                  | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/codezombiech.gitignore?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore) [![Installs](https://flat.badgen.net/vs-marketplace/i/codezombiech.gitignore?color=blue)](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore) [![Rating](https://flat.badgen.net/vs-marketplace/rating/codezombiech.gitignore?color=blue)](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)                                                       |
| Material Icon Theme        | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/PKief.material-icon-theme?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) [![Installs](https://flat.badgen.net/vs-marketplace/i/PKief.material-icon-theme?color=blue)](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) [![Rating](https://flat.badgen.net/vs-marketplace/rating/PKief.material-icon-theme?color=blue)](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)                                     |
| CodeSnap                   | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/adpyke.codesnap?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap) [![Installs](https://flat.badgen.net/vs-marketplace/i/adpyke.codesnap?color=blue)](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap) [![Rating](https://flat.badgen.net/vs-marketplace/rating/adpyke.codesnap?color=blue)](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap)                                                                                                 |
| :emojisense:               | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/bierner.emojisense?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=bierner.emojisense) [![Installs](https://flat.badgen.net/vs-marketplace/i/bierner.emojisense?color=blue)](https://marketplace.visualstudio.com/items?itemName=bierner.emojisense) [![Rating](https://flat.badgen.net/vs-marketplace/rating/bierner.emojisense?color=blue)](https://marketplace.visualstudio.com/items?itemName=bierner.emojisense)                                                                               |

[vsc essentials extension pack]: https://marketplace.visualstudio.com/items?itemName=Gydunhn.vsc-essentials
[sanik bajracharya]: https://medium.com/@sanik.bajracharya
[article]: https://medium.com/@sanik.bajracharya/vscode-how-to-create-your-own-extension-pack-483385644c29
[This extension]: https://open-vsx.org/extension/Gydunhn/vsc-essentials
[open-vsx.org]: https://open-vsx.org/
