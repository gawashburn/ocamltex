OCamlTeX 0.6 
------------

Installation instructions
-------------------------

OCamlTeX requires OCaml 3.08.4 or newer (including the source tree that it was
built), Caml Shell (CASH), OMake, and TeX/LaTeX.  After you have all of these
things installed and configured:    

1. Edit OMakefile to meet your preferences and configuration.  Minimally you
will need to set OCAMLSRC to be the location of your OCaml source tree.

2. Run "omake"

3. Move "ocamltex.sty" to somewhere searched by kpathsea, and move/rename
"ocamltex.run" to be "ocamltex" somewhere that is searched by your PATH
environment variable.
