# FraCaS-AMR
This is a very provisional draft annotation of the FraCaS test suite with AMR graphs.  FraCaS is a set of entailment pairs specifically designed to exemplify many of the more difficult problems handled in formal semantics, and therefore a dramatically different class of problems than entailment sets such as RTE or SNLI.  The hope behind this is to encourage people to implement more logically-focused approaches to AMR.  I hope to eventually add multi-sentence AMR links to this as well. 

For background as to where these come from:
- The original test suite and related conclusions are great, and can be seen at ftp://ftp.cogsci.ed.ac.uk/pub/FRACAS/del16.ps.gz
- This is made possible by the valiant work of Bill McCartney converting that to XML, and these AMRs are based upon that cleaned version:  http://www-nlp.stanford.edu/~wcmac/downloads/fracas.xml
- It is generated as part of the (LENLS 13 Unshared task)[http://www.compling.jp/fracas_task/index.html], and credit goes to the organizers of that task for inspiring this!

This is not an official AMR dataset, and all errors are my own.  Some annotations also contain components that will be utilized in AMR phase 3, as with the expanded comparative and degree semantics (have-degree-91).  Four "degenerate" problems with no hypothesis -- 276, 305, 309 and 310 -- are also simply omitted.  (This is also not recieving the attention and quality control that we're putting towards our actual AMR release data, so definite post an issue if you see an error ...)


