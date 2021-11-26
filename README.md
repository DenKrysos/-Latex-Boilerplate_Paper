# -Latex-Boilerplate_Paper

A quite nice Boilerplate/Template together with some Macros and ready-to-use set up suroundings for LaTeX. Documenttype "Article-Level", i.e. no "Book".

- Layout and Skeleton Setup is well separated from the content
- Set up for Biblatex
- Set up for glossaries (requires external builder, pretty easy to configure)
- All the layout regarding stuff is inside "0organization"
-- There mostly only thing has to be touched: Choose your prefered Author-Format (different Files for different Formats) and also write the correct Authors themselves there
- "2ProjectSetup.tex" has some Makros set-up to unify directory-references. For easy use, just leave it as is and use the Macros when e.g. including files out of the set folders.
- The structuring of your Project Skeleton starts from "3Disposition.tex". The rest happens inside the directory "4chapter".
-- I suggest to just leave "3Disposition.tex" as is and work inside "4chapter". But if you prefer, changing "3Disposition.tex" is fine as well.


## Some Feature:
- Macro to automatically include a "standalone tikz picture" with the best options.
-- Ensures, that the picture does not exceed the page/environment size on any side
-- Allows several options, like rotate, crop, insert as plain-text (render together with main file) or as pre-rendered pdf-picture.
-- If desired the pictures can be included as "buildnew". Means: They are only rendered new, if they changed. Saves a lot of compilation time.
-- Allows explicit scaling and positioning
- tikz:
-- Some 3-Dimensional Graphic Generation done in tikz
-- Flow Graph Toolset

- For sure some more features I can't quite recall. That thing is huge...
