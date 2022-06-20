---
title: My Default settings VSCode for Developments
layout: post
date: '2022-02-28 22:56:02 +0700'
categories:
- vscode
---

`settings.json`

{% highlight json %}
{
  "files.insertFinalNewline": true,
  "vsicons.dontShowNewVersionMessage": true,
  "window.titleBarStyle": "native",

  "customizeUI.fontSizeMap": {
    "13px": "15px",
    "12px": "14px",
    "tab-title": "17px",
    "monospace": "15px"
  },
  "customizeUI.listRowHeight": 23,
  "customizeUI.font.monospace": "SF Mono",
  "customizeUI.stylesheet": {
    ".search-view .search-widgets-container": "padding-top: 0px !important",
    ".suggest-input-container": "padding: 3px 4px 3px !important;"
  },
  "window.zoomLevel": -0.5,
  "editor.fontSize": 17,
  "git.confirmSync": false,
  "editor.cursorStyle": "line-thin",
  "workbench.editor.tabSizing": "fit",
  "workbench.iconTheme": "macos-classic-icons",
  "editor.fontWeight": "900",
  "editor.minimap.renderCharacters": false,
  "editor.bracketPairColorization.enabled": false,
  "editor.overviewRulerBorder": false,
  "editor.renderLineHighlight": "all",
  "editor.fontFamily": "SF Mono, Monaco",
  "editor.fontLigatures": true,
  "terminal.integrated.fontFamily": "MesloLGS NF",
  "terminal.integrated.fontSize": 16,
  "editor.tabSize": 4,
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
  "plantuml.commandArgs": ["-Djdk.module.illegalAccess=deny"],
  "workbench.tree.renderIndentGuides": "always",
  "workbench.tree.indent": 15,
  "workbench.editor.showIcons": true,
  "customizeUI.activityBar": "top",
  "workbench.colorTheme": "MacOS Modern Dark - Xcode Catalina",
  "editor.inlineSuggest.enabled": true,
  "editor.guides.indentation": false,
  "todo-tree.highlights.defaultHighlight": {
    "icon": "alert",
    "type": "text-and-comment",
    "foreground": "#000000",
    "background": "#FFFFFF",
    "opacity": 50,
    "iconColour": "#0000FF",
    "gutterIcon": true,
  },
  "todo-tree.highlights.customHighlight": {
    "TODO": {
      "icon": "check",
      "foreground": "#000000",
      "background": "#FFFFFF",
      "iconColour": "#FFFFFF",
    },
    "NOTE": {
      "icon": "note",
      "foreground": "#FFFFFF",
      "background": "#808080",
      "iconColour": "#808080",
    },
    "COMMENT": {
      "icon": "note",
      "foreground": "#FFFFFF",
      "background": "#808080",
      "iconColour": "#808080",
    },
    "FIXME": {
      "foreground": "#000000",
      "background": "#FFFF00",
      "iconColour": "#FFFF00",
    },
    "BUG": {
      "foreground": "#000000",
      "background": "#FF0000",
      "iconColour": "#FF0000",
    },
    "[ ]": {
      "icon": "check",
      "foreground": "#000000",
      "background": "#FFFFFF",
      "iconColour": "#FFFF00",
    },
    "[x]": {
      "icon": "check",
      "foreground": "#FFFFFF",
      "background": "#00FF00",
      "iconColour": "#00FF00",
    }
  },
  "todo-tree.general.tags": [
    "BUG",
    "HACK",
    "FIXME",
    "TODO",
    "NOTE",
    "COMMENT",
    "[ ]",
    "[x]"
  ],
  "todo-tree.regex.regex": "(//|#|<!--|;|/\\*|^|^\\s*(-|\\d+.))\\s*($TAGS).*(\\n\\s*//\\s{2,}.*)*",
  "[html]": {
    "editor.defaultFormatter": "HookyQR.beautify"
  },
  "[css]": {
    "editor.defaultFormatter": "HookyQR.beautify"
  },
  "[django-html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.quickSuggestions": {
      "other": true,
      "comments": true,
      "strings": true
    }
  },
  "[jsonc]": {
    "editor.defaultFormatter": "HookyQR.beautify"
  },
}
{% endhighlight %}
