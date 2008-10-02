OCamlTeX 0.61
-------------

Installation instructions
-------------------------

OCamlTeX requires OCaml 3.08.4 or newer (including the source tree that it was
built), OMake, and TeX/LaTeX.  After you have all of these
things installed and configured:    

1. Edit OMakefile to meet your preferences and configuration.  

2. Run "omake"

3. Move "ocamltex.sty" to somewhere searched by kpathsea, and move/rename
"ocamltex.run" to be "ocamltex" somewhere that is searched by your PATH
environment variable.
