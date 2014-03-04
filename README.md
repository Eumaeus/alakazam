# "Alakazam", a build system for CITE Audio services #

A fork of "Now You See It", a build system for CITE Image services

`alakazam` generates RDF statements from a collection CITE Images using the RDF vocabulary expected by the `sparqlcts` implementation of CITE Image Services.

Initially, `alakazam` supports data in locally stored `csv` files.  It could easily expand to include Google Fusion Tables and local `tsv` files as data sources.


## Data sources ##


*Audio collections* should be documented with three properties:

1. A unique CITE URN
2. A labelling description
3. A URL (local or remote) to a directory where .mp3 source files are stored.

*Individual images* should be documented with three properties:

1. A unique CITE URN
2. A caption
3. A statement about licensing and rights for reuse


