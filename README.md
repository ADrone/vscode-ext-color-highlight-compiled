# [vscode-ext-color-highlight](https://github.com/naumovs/vscode-ext-color-highlight)

This extension styles css/web colors found in your document.

## Install

In VSC press Ctrl+Shift+P (Cmd+Shift+P on Mac) then type ">ext install", hit enter, search "Color Highlight". As of this upload, it is version 1.3.0. I have added a scroll bar color toggle and corresponding user setting.

You can download this and install this pre-compiled folder into your .vscode\extensions\ folder. Usually in the user\ directory.
the full location is C:\users\yourname\.vscode\extensions\naumovs.color-highlight-1.3.0

the important files are dist\extension.js, package.json, .vsixmanifest, that's all. I installed 1.3.0 from the vscode extension menu, then overwrote the files with my changes. (1.3.1) have fun.



## Changelist

### 1.3.1
  - Feat: Toggle colors in the ruler (scroll bar)

### 1.3.0
  - Feat: Support hex alpha
  - Fix: Accidental highlighting of strings like "#1234567890"
  - Fix: Highlights non-color array keys in Drupal PHP code

### 1.2.1
  - Added new option to disable color words highlight.

### 1.2
  - New styling modes for the marker: background, underline. Default is "background" now

### 1.1
  - Refactored code to prevent memory leaks.
  - Added configuration for the extension.
  - Added command highlight current file (if it's not configured to be highlighted automatically)

## Contributors

  - [lochstar](https://github.com/lochstar) - Styling modes for the marker
  - [ADrone](https://github.com/ADrone/vscode-ext-color-highlight-compiled) - Toggle colors in the ruler (scroll bar)

Feel free to contribute!
