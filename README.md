# FraCaS-AMR
A draft annotation of the FraCaS test suite with AMR graphs.  The hope behind this is to simplify the task of using AMR for things like formal semantics and entailment, by allowing one to start with gold AMRs. 

- The original test suite and related conclusions are great, and can be seen at ftp://ftp.cogsci.ed.ac.uk/pub/FRACAS/del16.ps.gz
- This is made possible by the valiant work of Bill McCartney converting that to XML, and that version was defaulted to whenever it differed from the original:  http://www-nlp.stanford.edu/~wcmac/downloads/fracas.xml
- It is generated as part of the (LENLS 13 Unshared task)[http://www.compling.jp/fracas_task/index.html]; thanks to its organizers!

This is not an official AMR dataset, and all errors are my own.  Some annotations also contain components that will be utilized in AMR phase 3, as with the expanded comparative and degree semantics (have-degree-91).  Four "degenerate" problems with no hypothesis -- 276, 305, 309 and 310 -- are also simply omitted.


