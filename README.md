# AnkiMindMap

Inspired by [Anki X Markdown X MindMap](https://ankiweb.net/shared/info/728482867).

# How to use

Download and import MindMapCloze.apkg in this repository. A new note type named MindMap Cloze is added.

# Markdown Syntax

[Markmap](https://markmap.js.org/repl)

# Customize

If the mind map is big, it will be zoomed out to fit the window. You can use following setting at the beginning of note to set the size of mindmap. If the last cloze is outside the window, it will be moved into the window automatically.
```
---
markmap:
  width: 1000px
  height: 1000px
  foldExpression: ([^#]+##[^#]+)|(^##[^#]+)
---

# Why use anki

## Multipe OS support
## Addon support
```

## foldExpression

if the mind is big, you can use this setting to fold the branch automatically. This setting is a javascript regular expression. `([^#]+##[^#]+)|(^##[^#]+)` means fold branches start ##.

# Screenshots

Cloze Front

![Cloze Front](https://github.com/ntwo1980/AnkiMindMap/blob/main/Cloze%20Front.png?raw=true)

Cloze Back

![Cloze Back](https://github.com/ntwo1980/AnkiMindMap/blob/main/Cloze%20Back.png?raw=true)

Large Mind Map

![Large Mind Map](https://github.com/ntwo1980/AnkiMindMap/blob/main/Big%20Mind%20Map.png?raw=true)
