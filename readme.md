# Dev Tools Workshop

This is a brief workshop developed for Ritu Ghiya's Class, collage poetics, at Graphic Design Department, Yale School of Art.

## Overview

This workshop has been designed to provide an overview of the browser developer tools for participants. The program is divided into two sections, each serving a distinct purpose. The first section will provide a brief introduction to the tools and their functions, while the second section will comprise a series of exercises aimed at helping participants learn how to use the tools to debug and inspect web pages.

## Part 1: Introduction to the Developer Tools

### What are the developer tools?

The developer tools are a set of web authoring and debugging tools built into most modern browsers. The tools allow web developers to inspect and edit the HTML, CSS, and JavaScript on any web page. The tools also allow developers to debug JavaScript code and to profile the performance of web pages.

### How to open the developer tools?

The developer tools can be opened in most modern browsers by pressing `F12` or `Ctrl+Shift+I` (or `Cmd+Opt+I` on Mac). The tools will open in a separate window. The tools can also be opened by right clicking on any web page and selecting `Inspect Element` from the context menu.

### The developer tools window

The developer tools window is comprised of three key sections: the toolbar, the sidebar, and the main panel. The toolbar provides buttons to switch between tools, while the sidebar lists tools that can be opened in the main panel. The main panel displays the currently selected tool. For this workshop, we will focus on the following tools:

* The Elements tool
* The Console tool
* The Sources tool

### The Elements tool

The Elements tool allows inspection and modification of a web page's HTML and CSS. The tool is divided into two sections: the markup view, which displays the HTML of the selected element, and the styles view, which displays the CSS styles applied to the selected element.

### The Console tool

The Console tool provides the ability to execute JavaScript code and view the code's output. The Console tool is separated into the command line for entering code and the output section for displaying results.

### The Sources tool

The Sources tool enables inspection and editing of a web page's JavaScript code. It has three main components: the file tree, which displays loaded JavaScript files, the editor for modifying code, and the debugger for setting breakpoints and stepping through the code.

## Part 2: Exercises

### Exercise 1: Inspecting the HTML and CSS of a web page

1. Open the developer tools by pressing `F12` or `Ctrl+Shift+I` (or `Cmd+Opt+I` on Mac).
2. Select the Elements tool from the toolbar.
3. Load a web page in the browser that you would like to inspect.
4. Use the "Elements" tool to inspect the HTML and CSS of the web page.
5. In the "Markup" view, click on different elements on the page to see their HTML structure.
6. In the "Styles" view, see the CSS styles applied to the selected element.
7. Experiment with modifying the HTML and CSS using the "Elements" tool to see the changes in real-time on the web page.
8. Save your changes by right-clicking the page and selecting "Save as...", or refresh the page to discard the changes.

### Exercise 2: Using the Console tool to execute JavaScript code

1. Open the developer tools by pressing `F12` or `Ctrl+Shift+I` (or `Cmd+Opt+I` on Mac).
2. Go to the "Console" tool.
3. Load a web page that has JavaScript.
4. Use the "Console" tool to execute JavaScript code.
5. Try some simple JavaScript commands like `[...document.querySelectorAll("a")].forEach(a => a.style.color = "hotpink");`.
6. Use the "Console" tool to debug JavaScript code.
7. Observe the output of the code in the "Output" section.

### Exercise 3: Using the Sources tool to debug JavaScript code

1. Open the developer tools by pressing `F12` or `Ctrl+Shift+I` (or `Cmd+Opt+I` on Mac).
2. Go to the "Sources" tool.
3. Find and select the JavaScript file you want to debug from the file tree on the left side.
4. Set a breakpoint by clicking on the line number where you want to pause the execution of the code.
5. Refresh the web page to trigger the JavaScript code.
6. The code execution will stop at the breakpoint you set, and you can inspect the values of variables and the call stack in the "Scope" section.
7. You can step through the code using the "Step over" and "Step into" buttons, or by using the keyboard shortcuts `F10` (step over) and `F11` (step into).
8. When you have finished debugging, you can resume the code execution by clicking the "Resume" button or using the keyboard shortcut `F8`.
9. You can also make changes to the code in the editor and see the results in real-time by hitting "Save" or Ctrl+S (or `Cmd+S` on Mac).

## Resources

### Developer Tools Documentation

* [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Tools)
* [Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools/)
* [Safari Web Inspector](https://developer.apple.com/safari/tools/)

### Youtube Tutorials

* [21+ Browser Dev Tools & Tips You Need To Know](https://www.youtube.com/watch?v=TcTSqhpm80Y&ab_channel=Fireship)
* [Debugging JavaScript - Chrome DevTools 101](https://www.youtube.com/watch?v=H0XScE08hy8&ab_channel=GoogleChromeDevelopers)
* [DevTools Tip](https://www.youtube.com/playlist?list=PLNYkxOF6rcIAcezfL8q0rjt13ufKseL5X)
* [Chrome DevTools for designers](https://www.youtube.com/watch?v=yNwwEu3Kcbs&ab_channel=GoogleChromeDevelopers)

### Extensions

* [Visbug](https://chrome.google.com/webstore/detail/visbug/cdockenadnadldjbbgcallicgledbeoc)
* [ColorZilla](https://www.colorzilla.com/)
* [FontFace Ninja](https://chrome.google.com/webstore/detail/fontface-ninja/eljapbgkmlngdpckoiiibecpemleclhh)
* [Responsive viewer](https://chrome.google.com/webstore/detail/responsive-viewer/inmopeiepgfljkpkidclfgbgbmfcennb)

### Other

* [Awesome Developer Tools](https://github.com/moimikey/awesome-devtools)
* [BuiltWith](https://builtwith.com/****)
