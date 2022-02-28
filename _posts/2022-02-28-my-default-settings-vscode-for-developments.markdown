---
title: My Default settings VSCode for Developments
layout: post
date: '2022-02-28 22:56:02'
categories:
- vscode
---

`settings.json`

{% highlight json %}
{
    // "customizeUI.font.regular": "Droid Sans Mono",
    // "customizeUI.titleBar": "inline",
    "files.insertFinalNewline": true,
    "vsicons.dontShowNewVersionMessage": true,
    "window.titleBarStyle": "native",

    "customizeUI.fontSizeMap": {
        "13px": "15px",
        "12px": "14px",
        "tab-title": "17px",
        "monospace": "15px",
    },
    "customizeUI.listRowHeight": 23,
    "customizeUI.font.monospace": "SF Mono",
    "customizeUI.stylesheet": {
        ".search-view .search-widgets-container": "padding-top: 0px !important",
        ".suggest-input-container": "padding: 3px 4px 3px !important;"
    },
    "window.zoomLevel": -0.6,
    "editor.fontSize": 16,
    "git.confirmSync": false,
    "editor.cursorStyle": "line-thin",
    "workbench.editor.tabSizing": "fit",
    "workbench.iconTheme": "file-icons-colourless-mac",
    "editor.fontWeight": "550",
    "editor.minimap.renderCharacters": false,
    "editor.overviewRulerBorder": false,
    "editor.renderLineHighlight": "all",
    "editor.fontFamily": "SF Mono, Monaco",
    "editor.fontLigatures": true,
    // "terminal.integrated.fontFamily": "Hack Nerd Font",
    "terminal.integrated.fontSize": 16,
    "editor.tabSize": 4,
    "better-comments.multilineComments": true,
    "better-comments.highlightPlainText": false,
    "better-comments.tags": [
        {
            "tag": "!",
            "color": "#FF2D00",
            "strikethrough": false,
            "backgroundColor": "transparent"
        },
        {
            "tag": "?",
            "color": "#3498DB",
            "strikethrough": false,
            "backgroundColor": "transparent"
        },
        {
            "tag": "//",
            "color": "#474747",
            "strikethrough": true,
            "backgroundColor": "transparent"
        },
        {
            "tag": "todo",
            "color": "#FF8C00",
            "strikethrough": false,
            "backgroundColor": "transparent"
        },
        {
            "tag": "*",
            "color": "#98C379",
            "strikethrough": false,
            "backgroundColor": "transparent"
        }
    ],
    "editor.largeFileOptimizations": false,
    "explorer.openEditors.visible": 0,
    "workbench.editor.showTabs": true,
    "[json]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "explorer.confirmDragAndDrop": false,
    "javascript.updateImportsOnFileMove.enabled": "never",
    "plantuml.diagramsRoot": "docs/diagrams/src",
    "plantuml.exportOutDir": "docs/diagrams/out",
    "plantuml.commandArgs": [
        "-Djdk.module.illegalAccess=deny"
    ],
    "workbench.tree.renderIndentGuides": "always",
    "workbench.tree.indent": 15,
    "workbench.editor.showIcons": true,
    "customizeUI.activityBar": "bottom",
    "workbench.colorTheme": "MacOS Modern Dark - Xcode Catalina",
    "editor.inlineSuggest.enabled": true,
    "github.copilot.enable": {
        "*": true,
        "yaml": false,
        "plaintext": false,
        "markdown": false,
        "python": false
    },
    "bracket-pair-colorizer-2.depreciation-notice": false,
}
{% endhighlight %}
