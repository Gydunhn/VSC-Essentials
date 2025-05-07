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
    "editor.formatOnSave": true,
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

### Core Package

| Extension           | Stats                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| VSC-Essentials-Core | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/Gydunhn.vsc-essentials-core?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.vsc-essentials-core) [![Installs](https://flat.badgen.net/vs-marketplace/i/Gydunhn.vsc-essentials-core?color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.vsc-essentials-core) [![Rating](https://flat.badgen.net/vs-marketplace/rating/Gydunhn.vsc-essentials-core?color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.vsc-essentials-core) |

### Version Control

| Extension                  | Stats                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Git Graph                  | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/mhutchie.git-graph?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph) [![Installs](https://flat.badgen.net/vs-marketplace/i/mhutchie.git-graph?color=blue)](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph) [![Rating](https://flat.badgen.net/vs-marketplace/rating/mhutchie.git-graph?color=blue)](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)                               |
| GitLens — Git supercharged | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/eamodio.gitlens?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) [![Installs](https://flat.badgen.net/vs-marketplace/i/eamodio.gitlens?color=blue)](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) [![Rating](https://flat.badgen.net/vs-marketplace/rating/eamodio.gitlens?color=blue)](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)                                                 |
| Git History                | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/donjayamanne.githistory?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) [![Installs](https://flat.badgen.net/vs-marketplace/i/donjayamanne.githistory?color=blue)](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) [![Rating](https://flat.badgen.net/vs-marketplace/rating/donjayamanne.githistory?color=blue)](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) |
| gitignore                  | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/codezombiech.gitignore?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore) [![Installs](https://flat.badgen.net/vs-marketplace/i/codezombiech.gitignore?color=blue)](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore) [![Rating](https://flat.badgen.net/vs-marketplace/rating/codezombiech.gitignore?color=blue)](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)       |

### Visualization and Preview

| Extension     | Stats                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Image preview | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/kisstkondoros.vscode-gutter-preview?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview) [![Installs](https://flat.badgen.net/vs-marketplace/i/kisstkondoros.vscode-gutter-preview?color=blue)](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview) [![Rating](https://flat.badgen.net/vs-marketplace/rating/kisstkondoros.vscode-gutter-preview?color=blue)](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview) |
| SVG Previewer | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/vitaliymaz.vscode-svg-previewer?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=vitaliymaz.vscode-svg-previewer) [![Installs](https://flat.badgen.net/vs-marketplace/i/vitaliymaz.vscode-svg-previewer?color=blue)](https://marketplace.visualstudio.com/items?itemName=vitaliymaz.vscode-svg-previewer) [![Rating](https://flat.badgen.net/vs-marketplace/rating/vitaliymaz.vscode-svg-previewer?color=blue)](https://marketplace.visualstudio.com/items?itemName=vitaliymaz.vscode-svg-previewer)                         |
| CodeSnap      | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/adpyke.codesnap?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap) [![Installs](https://flat.badgen.net/vs-marketplace/i/adpyke.codesnap?color=blue)](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap) [![Rating](https://flat.badgen.net/vs-marketplace/rating/adpyke.codesnap?color=blue)](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap)                                                                                                                         |

### File Support

| Extension          | Stats                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| XML Tools          | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/DotJoshJohnson.xml?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml) [![Installs](https://flat.badgen.net/vs-marketplace/i/DotJoshJohnson.xml?color=blue)](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml) [![Rating](https://flat.badgen.net/vs-marketplace/rating/DotJoshJohnson.xml?color=blue)](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)                               |
| Rainbow CSV        | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/mechatroner.rainbow-csv?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv) [![Installs](https://flat.badgen.net/vs-marketplace/i/mechatroner.rainbow-csv?color=blue)](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv) [![Rating](https://flat.badgen.net/vs-marketplace/rating/mechatroner.rainbow-csv?color=blue)](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv) |
| Paste JSON as Code | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/quicktype.quicktype?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype) [![Installs](https://flat.badgen.net/vs-marketplace/i/quicktype.quicktype?color=blue)](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype) [![Rating](https://flat.badgen.net/vs-marketplace/rating/quicktype.quicktype?color=blue)](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)                         |

### Other

| Extension                      | Stats                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Color Highlight                | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/naumovs.color-highlight?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) [![Installs](https://flat.badgen.net/vs-marketplace/i/naumovs.color-highlight?color=blue)](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) [![Rating](https://flat.badgen.net/vs-marketplace/rating/naumovs.color-highlight?color=blue)](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)                                                                                           |
| VSC-Essentials-Themes-Core     | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/Gydunhn.vsc-essentials-themes-core?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.vsc-essentials-themes-core) [![Installs](https://flat.badgen.net/vs-marketplace/i/Gydunhn.vsc-essentials-themes-core?color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.vsc-essentials-themes-core) [![Rating](https://flat.badgen.net/vs-marketplace/rating/Gydunhn.vsc-essentials-themes-core?color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.vsc-essentials-themes-core)                         |
| VSC-Essentials-Material-Themes | [![Badge for version for Visual Studio Code extension](https://flat.badgen.net/vs-marketplace/v/Gydunhn.vsc-essentials-material-themes?icon=visualstudio&color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.vsc-essentials-material-themes) [![Installs](https://flat.badgen.net/vs-marketplace/i/Gydunhn.vsc-essentials-material-themes?color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.vsc-essentials-material-themes) [![Rating](https://flat.badgen.net/vs-marketplace/rating/Gydunhn.vsc-essentials-material-themes?color=blue)](https://marketplace.visualstudio.com/items?itemName=Gydunhn.vsc-essentials-material-themes) |

[vsc essentials extension pack]: <https://marketplace.visualstudio.com/items?itemName=Gydunhn.vsc-essentials>
[sanik bajracharya]: <https://medium.com/@sanik.bajracharya>
[article]: <https://medium.com/@sanik.bajracharya/vscode-how-to-create-your-own-extension-pack-483385644c29>
[This extension]: <https://open-vsx.org/extension/Gydunhn/vsc-essentials>
[open-vsx.org]: <https://open-vsx.org/>
