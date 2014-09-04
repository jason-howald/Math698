Math698
=======

Shared seminar notes for Howald's Fall 2014 Math 698

698Notes.sty 
  is a stylesheet for these notes.  Included packages and global definitions go here.

NotesIndex.tex
  is the main document.  Its job is to include other files which represent content.
  It also sets up comments commands.
  
Content files
  should be named consistently with "01RanieriAlgebraicVarieties.tex".  That is, 
  presentation number, last name, topic, using camelcase.  They get input 
  into NotesIndex.tex, so they have no \begin{document} and \end{document}.
  
Comments
  Are set apart by last name, e.g. \Baral{This is Brabim's comment}.  
  \toggletrue{comments} and \togglefalse{comments} have the obvious result.
  You can compile without comments to make audience notes, and with comments to 
  get your extended personal notes.
