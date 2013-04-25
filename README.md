trivfloat - Quick floats in LaTeX
===================================================

The `trivfloat` package provides a quick method for defining new
float types in LaTeX. A single command sets up a new float in
the same style as the LaTeX kernel figure and table float types.

Installation
------------

The package is supplied in `.dtx` format and as a pre-extracted
`.zip` file, `trivfloat.tds.zip`. The later is most convenient
for most users: simply unzip this in your local `texmf`
directory. If you want to unpack the `.dtx` yourself, running
`tex trivfloat.dtx` will extract the package whereas `latex
trivfloat.dtx` will extract it and also typeset the
documentation.

Typesetting the documentation requires a number of packages in
addition to those needed to use the package. This is mainly 
because of the number of demonstration items included in the 
text. To compile the documentation without error, you will 
need the packages:
 - `csquotes`
 - `helvet`
 - `hypdoc`
 - `mathpazo`
 - `microtype`
 - `listings`
 - `lmodern`