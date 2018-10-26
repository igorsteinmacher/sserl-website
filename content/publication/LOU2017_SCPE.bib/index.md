+++
title = "A BSPlib-style API for Bulk Synchronous  Parallel ML"
date = 2017-01-01
authors = ["Frédéric Loulergue"]
publication_types = ["2"]
abstract = "Bulk synchronous parallelism (BSP) offers an  abstract and simple model of parallelism yet allows  to take realistically into account the communication  costs of parallel algorithms. BSP has been used in  many application domains. BSPlib and its variants  are programming libraries for the C language that  support the BSP style.  Bulk Synchronous Parallel ML  (BSML) is a library for BSP programming with the  functional language OCaml. It offers parallel  operations on a data structure named parallel  vector. BSML provides a global view of programs,  i.e. BSML programs can be seen as sequential  programs working on a parallel data structure (seq  of par) while a BSPlib program is written in the  SPMD style and understood as a parallel composition  of communicating sequential programs (par of  seq). The communication styles of BSML and BSPlib  are also quite different.  The contribution of this  paper is a BSPlib-style communication API  implemented on top of BSML. It has been designed  without extending BSML, but only using the  imperative features of the underlying function  language OCaml. Programs implemented using this API  are very close to programs implemented using a  BSPlib library for the C language. It therefore  shows that BSML is universal for the BSP model.  "
selected = "false"
publication = "*Scalable Computing: Practice and Experience*"
doi = "10.12694/scpe.v18i3.1306"
+++

