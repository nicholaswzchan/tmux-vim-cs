<div class="container">

<div class="grid-block">

<div class="grid-1">

# [Vim Cheat Sheet](/)

</div>

</div>

<div class="commands-container">

<div class="grid-block">

<div class="grid-lg-1-3">

## Global

*   <kbd>:help keyword</kbd> - open help for keyword
*   <kbd>:o file</kbd> - open file
*   <kbd>:saveas file</kbd> - save file as
*   <kbd>:close</kbd> - close current pane

## Cursor movement

*   <kbd>h</kbd> - move cursor left
*   <kbd>j</kbd> - move cursor down
*   <kbd>k</kbd> - move cursor up
*   <kbd>l</kbd> - move cursor right
*   <kbd>H</kbd> - move to top of screen
*   <kbd>M</kbd> - move to middle of screen
*   <kbd>L</kbd> - move to bottom of screen
*   <kbd>w</kbd> - jump forwards to the start of a word
*   <kbd>W</kbd> - jump forwards to the start of a word (words can contain punctuation)
*   <kbd>e</kbd> - jump forwards to the end of a word
*   <kbd>E</kbd> - jump forwards to the end of a word (words can contain punctuation)
*   <kbd>b</kbd> - jump backwards to the start of a word
*   <kbd>B</kbd> - jump backwards to the start of a word (words can contain punctuation)
*   <kbd>0</kbd> - jump to the start of the line
*   <kbd>^</kbd> - jump to the first non-blank character of the line
*   <kbd>$</kbd> - jump to the end of the line
*   <kbd>g_</kbd> - jump to the last non-blank character of the line
*   <kbd>gg</kbd> - go to the first line of the document
*   <kbd>G</kbd> - go to the last line of the document
*   <kbd>5G</kbd> - go to line 5
*   <kbd>fx</kbd> - jump to next occurrence of character x
*   <kbd>tx</kbd> - jump to before next occurrence of character x
*   <kbd>}</kbd> - jump to next paragraph (or function/block, when editing code)
*   <kbd>{</kbd> - jump to previous paragraph (or function/block, when editing code)
*   <kbd>zz</kbd> - center cursor on screen
*   <kbd>Ctrl</kbd> + <kbd>b</kbd> - move back one full screen
*   <kbd>Ctrl</kbd> + <kbd>f</kbd> - move forward one full screen
*   <kbd>Ctrl</kbd> + <kbd>d</kbd> - move forward 1/2 a screen
*   <kbd>Ctrl</kbd> + <kbd>u</kbd> - move back 1/2 a screen

<div class="well">**Tip** Prefix a cursor movement command with a number to repeat it. For example, <kbd>4j</kbd> moves down 4 lines.</div>

## Insert mode - inserting/appending text

*   <kbd>i</kbd> - insert before the cursor
*   <kbd>I</kbd> - insert at the beginning of the line
*   <kbd>a</kbd> - insert (append) after the cursor
*   <kbd>A</kbd> - insert (append) at the end of the line
*   <kbd>o</kbd> - append (open) a new line below the current line
*   <kbd>O</kbd> - append (open) a new line above the current line
*   <kbd>ea</kbd> - insert (append) at the end of the word
*   <kbd>Esc</kbd> - exit insert mode

</div>

<div class="grid-lg-1-3">

## Editing

*   <kbd>r</kbd> - replace a single character
*   <kbd>J</kbd> - join line below to the current one
*   <kbd>cc</kbd> - change (replace) entire line
*   <kbd>cw</kbd> - change (replace) to the end of the word
*   <kbd>c$</kbd> - change (replace) to the end of the line
*   <kbd>s</kbd> - delete character and substitute text
*   <kbd>S</kbd> - delete line and substitute text (same as cc)
*   <kbd>xp</kbd> - transpose two letters (delete and paste)
*   <kbd>u</kbd> - undo
*   <kbd>Ctrl</kbd> + <kbd>r</kbd> - redo
*   <kbd>.</kbd> - repeat last command

## Marking text (visual mode)

*   <kbd>v</kbd> - start visual mode, mark lines, then do a command (like y-yank)
*   <kbd>V</kbd> - start linewise visual mode
*   <kbd>o</kbd> - move to other end of marked area
*   <kbd>Ctrl</kbd> + <kbd>v</kbd> - start visual block mode
*   <kbd>O</kbd> - move to other corner of block
*   <kbd>aw</kbd> - mark a word
*   <kbd>ab</kbd> - a block with ()
*   <kbd>aB</kbd> - a block with {}
*   <kbd>ib</kbd> - inner block with ()
*   <kbd>iB</kbd> - inner block with {}
*   <kbd>Esc</kbd> - exit visual mode

## Visual commands

*   <kbd>></kbd> - shift text right
*   <kbd><</kbd> - shift text left
*   <kbd>y</kbd> - yank (copy) marked text
*   <kbd>d</kbd> - delete marked text
*   <kbd>~</kbd> - switch case

## Registers

*   <kbd>:reg</kbd> - show registers content
*   <kbd>"xy</kbd> - yank into register x
*   <kbd>"xp</kbd> - paste contents of register x

<div class="well">**Tip** Registers are being stored in ~/.viminfo, and will be loaded again on next restart of vim.</div>

<div class="well">**Tip** Register 0 contains always the value of the last yank command.</div>

## Marks

*   <kbd>:marks</kbd> - list of marks
*   <kbd>ma</kbd> - set current position for mark A
*   <kbd>`a</kbd> - jump to position of mark A
*   <kbd>y`a</kbd> - yank text to position of mark A

## Macros

*   <kbd>qa</kbd> - record macro a
*   <kbd>q</kbd> - stop recording macro
*   <kbd>@a</kbd> - run macro a
*   <kbd>@@</kbd> - rerun last run macro

</div>

<div class="grid-lg-1-3">

## Cut and paste

*   <kbd>yy</kbd> - yank (copy) a line
*   <kbd>2yy</kbd> - yank (copy) 2 lines
*   <kbd>yw</kbd> - yank (copy) the characters of the word from the cursor position to the start of the next word
*   <kbd>y$</kbd> - yank (copy) to end of line
*   <kbd>p</kbd> - put (paste) the clipboard after cursor
*   <kbd>P</kbd> - put (paste) before cursor
*   <kbd>dd</kbd> - delete (cut) a line
*   <kbd>2dd</kbd> - delete (cut) 2 lines
*   <kbd>dw</kbd> - delete (cut) the characters of the word from the cursor position to the start of the next word
*   <kbd>D</kbd> - delete (cut) to the end of the line
*   <kbd>d$</kbd> - delete (cut) to the end of the line
*   <kbd>x</kbd> - delete (cut) character

## Exiting

*   <kbd>:w</kbd> - write (save) the file, but don't exit
*   <kbd>:w !sudo tee %</kbd> - write out the current file using sudo
*   <kbd>:wq</kbd> or <kbd>:x</kbd> or <kbd>ZZ</kbd> - write (save) and quit
*   <kbd>:q</kbd> - quit (fails if there are unsaved changes)
*   <kbd>:q!</kbd> or <kbd>ZQ</kbd> - quit and throw away unsaved changes

## Search and replace

*   <kbd>/pattern</kbd> - search for pattern
*   <kbd>?pattern</kbd> - search backward for pattern
*   <kbd>\vpattern</kbd> - 'very magic' pattern: non-alphanumeric characters are interpreted as special regex symbols (no escaping needed)
*   <kbd>n</kbd> - repeat search in same direction
*   <kbd>N</kbd> - repeat search in opposite direction
*   <kbd>:%s/old/new/g</kbd> - replace all old with new throughout file
*   <kbd>:%s/old/new/gc</kbd> - replace all old with new throughout file with confirmations
*   <kbd>:noh</kbd> - remove highlighting of search matches

## Search in multiple files

*   <kbd>:vimgrep /pattern/ {file}</kbd> - search for pattern in multiple files

<div class="well">e.g. <kbd>:vimgrep /foo/ **/*</kbd></div>

*   <kbd>:cn</kbd> - jump to the next match
*   <kbd>:cp</kbd> - jump to the previous match
*   <kbd>:copen</kbd> - open a window containing the list of matches

</div>

</div>

<div class="grid-block">

<div class="grid-lg-1-3">

## Working with multiple files

*   <kbd>:e file</kbd> - edit a file in a new buffer
*   <kbd>:bnext</kbd> or <kbd>:bn</kbd> - go to the next buffer
*   <kbd>:bprev</kbd> or <kbd>:bp</kbd> - go to the previous buffer
*   <kbd>:bd</kbd> - delete a buffer (close a file)
*   <kbd>:ls</kbd> - list all open buffers
*   <kbd>:sp file</kbd> - open a file in a new buffer and split window
*   <kbd>:vsp file</kbd> - open a file in a new buffer and vertically split window
*   <kbd>Ctrl</kbd> + <kbd>ws</kbd> - split window
*   <kbd>Ctrl</kbd> + <kbd>ww</kbd> - switch windows
*   <kbd>Ctrl</kbd> + <kbd>wq</kbd> - quit a window
*   <kbd>Ctrl</kbd> + <kbd>wv</kbd> - split window vertically
*   <kbd>Ctrl</kbd> + <kbd>wh</kbd> - move cursor to the left window (vertical split)
*   <kbd>Ctrl</kbd> + <kbd>wl</kbd> - move cursor to the right window (vertical split)
*   <kbd>Ctrl</kbd> + <kbd>wj</kbd> - move cursor to the window below (horizontal split)
*   <kbd>Ctrl</kbd> + <kbd>wk</kbd> - move cursor to the window above (horizontal split)

</div>

<div class="grid-lg-1-3">

## Tabs

*   <kbd>:tabnew</kbd> or <kbd>:tabnew file</kbd> - open a file in a new tab
*   <kbd>Ctrl</kbd> + <kbd>wT</kbd> - move the current split window into its own tab
*   <kbd>gt</kbd> or <kbd>:tabnext</kbd> or <kbd>:tabn</kbd> - move to the next tab
*   <kbd>gT</kbd> or <kbd>:tabprev</kbd> or <kbd>:tabp</kbd> - move to the previous tab
*   <kbd>#gt</kbd> - move to tab number #
*   <kbd>:tabmove #</kbd> - move current tab to the #th position (indexed from 0)
*   <kbd>:tabclose</kbd> or <kbd>:tabc</kbd> - close the current tab and all its windows
*   <kbd>:tabonly</kbd> or <kbd>:tabo</kbd> - close all tabs except for the current one
*   <kbd>:tabdo</kbd> command - run the `command` on all tabs (e.g. `:tabdo q` - closes all opened tabs)

</div>

</div>

</div>

<div>

<div id="footer" class="grid-block">

<div class="box">

<div class="box-header">

## Additional Resources

</div>

<div class="box-body">

<div class="grid-block">

<div class="grid-lg-1-2">

### Languages

*   [Português - Brasil](/lang/pt_br/)
*   [Deutsch](/lang/de_de/)
*   [Bahasa Indonesia](/lang/id/)
*   [Español](/lang/es_es/)
*   [Türkçe](/lang/tr/)
*   [ภาษาไทย](/lang/th/)
*   [繁體中文](/lang/zh_tw/)
*   [한국어](/lang/ko/)
*   [Русский](/lang/ru/)
*   [Italiano](/lang/it/)
*   [Français](/lang/fr_fr/)
*   [Українська](/lang/uk/)
*   [Nederlands](/lang/nl_nl/)
*   [日本語](/lang/ja/)
*   [Romana](/lang/ro/)
*   [English](/)

</div>

<div class="grid-lg-1-2">

### About the vim cheat sheet

This project aims to be one of the most accessible vim guides available. We made sure to support mobile, desktop, and other [languages](#languages).

You can read about how to contribute (and help improve) by viewing our [README](https://github.com/rtorr/vim-cheat-sheet/blob/master/README.md). There you can see how to set up this project, or how to contribute a new language. Here is a big thank you to our [contributors](https://github.com/rtorr/vim-cheat-sheet/graphs/contributors)!

This project is licensed under [The MIT License (MIT)](https://github.com/rtorr/vim-cheat-sheet/blob/master/License.txt).

### Contributor Code of Conduct

This project strongly believes in having a code of conduct. [Please see the code of conduct page for more information.](/code_of_conduct/)

### Other places to find this document

This document was embedded in [DuckDuckGo](https://duckduckgo.com/?q=vim+cheat+sheet).

</div>

</div>

</div>

</div>

</div>

<div class="grid-block link-to-repo">

Checkout the source on [Github](https://github.com/rtorr/vim-cheat-sheet)

</div>

</div>

</div>

<script type="text/javascript">(function (i, s, o, g, r, a, m) { i['GoogleAnalyticsObject'] = r; i[r] = i[r] || function () { (i[r].q = i[r].q || []).push(arguments) }, i[r].l = 1 * new Date(); a = s.createElement(o), m = s.getElementsByTagName(o)[0]; a.async = 1; a.src = g; m.parentNode.insertBefore(a, m) })(window, document, 'script', '//www.google-analytics.com/analytics.js', 'ga'); ga('create', 'UA-25408695-1', 'auto'); ga('send', 'pageview'); if
('serviceWorker' in navigator) { navigator.serviceWorker.register('/service-worker.js').then(function (reg) { reg.onupdatefound = function () { var installingWorker = reg.installing; installingWorker.onstatechange = function () { switch (installingWorker.state) { case 'installed': if (navigator.serviceWorker.controller) { console.log('New or updated content is available.'); } else { console.log('Content is now available offline!'); } break; case 'redundant':
console.error('The installing service worker became redundant.'); break; } }; }; }).catch(function (e) { console.error('Error during service worker registration:', e); }); }</script>
