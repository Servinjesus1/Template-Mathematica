Mathematica-Student-Template
============================

Template for Mathematica that makes Homework and printed PDF documents look very pretty, and uses LaTeX font!

Installation
------------

Simply install Latin Modern font before running Mathematica/opening the document. Some Mathematica settings may be prudent to set for yourself to make it render as nicely as possible... [TODO] will update this.


Mathematica General Settings
----------------------------
_Modify Mathematica's options via the Option Inspector (Format>Option Inspector)_
_Make sure to change to Global Options before modifying these to ensure they apply to Mathematica globally_


### Trusted Location
  - In order to use the Magnification tool, be sure to set where this template (and other Mathematica files) exist as trusted locations. This can be done via the TrustedPath variable (_Global Options>NotebookSecurityOptions>TrustedPath_). When adding a new location, the window will prompt for ``FrontEnd`FileName[{$RootDirectory},"x"]`` where the `x` specifies the path to a trusted location.
  
### Hide Cell Labels
  - Cell Options > Cell Labels > ShowCellLabel=False
  - Hides `In[]` and `Out[]` markers which disrupt the Input/Output formatting

