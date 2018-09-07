# article-template
Basic LaTeX article template, using my preferred fonts, macros, and table setup etc. Requires LuaLaTeX.

This is not exactly clean or well designed, just what I like to use for basic LaTeX articles. But please use it if you wish, I welcome suggestions/complaints/hate mail.

It uses Linux Libertine O for roman fonts, Linux Biolinum O for sans, Libertinus Math for math characters, and IBM Plex Mono Light for monospace.

Some other little things are defined; tabularx columns are redefined to be middle aligned, you may want to undo this. Column types `Y` and `D` are defined to give vertical and horizontal centering. `Y` has its width dynamically set like an `X` type column, and `D` has a fixed width set by an argument.

`\codesnip{}` allows you to put some monospace text inline inside a shaded grey box. `\myquote{}` is setup similarly, putting text in a grey box but in a quote style, so that you can make a quote stand out in the middle of the page. The grey colour is set early in the preamble.
