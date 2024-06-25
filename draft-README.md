# Tn-Seq Analysis Service

## Overview

The Tn-Seq Analysis Service facilitates determination of essential and conditionally essential regions in bacterial genomes from data generated from transposon insertion sequencing (Tn-Seq) experiments. Tn-Seq (in the broad sense used here) refers to a family of related methods that use deep sequencing to survey a transposon insertion library and quantify the abundance of insertions at different sites in the genome.

*Note: The BV-BRC Tn-Seq Analysis Service wraps the [TRANSIT](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004401) software.  Please cite this reference when publishing results from this service:*

* DeJesus, M. A., Ambadipudi, C., Baker, R., Sassetti, C., & Ioerger, T. R. (2015). TRANSIT-a software tool for Himar1 TnSeq analysis. *PLoS computational biology*, *11*(10), e1004401.



## About this module

This module is a component of the BV-BRC build system. It is designed to fit into the
`dev_container` infrastructure which manages development and production deployment of
the components of the BV-BRC. More documentation is available [here](https://github.com/BV-BRC/dev_container/tree/master/README.md).

This module provides the following application specfication(s):
* [TnSeq](app_specs/TnSeq.md)


## See also

* [Tn-Seq Analysis Service](https://www.bv-brc.org/docs/https://bv-brc.org/app/Tnseq.html)
* [Tn-Seq Analysis Service Tutorial](https://www.bv-brc.org/docs//tutorial/tn-seq/tn-seq.html)



## References

* Adey A, Morrison HG, Asan, Xun X, Kitzman JO, Turner EH, Stackhouse B, MacKenzie AP, Caruccio NC, Zhang X, et al. 2010. Rapid, low-input, low-bias construction of shotgun fragment libraries by high-density in vitro transposition. Genome Biol 11: R119.
* DeJesus MA, Ambadipudi C, Baker R, Sassetti C, Ioerger TR. TRANSIT - a software tool for Himar1 Tnseq analysis. PLoS Comput Biol. 2015;11: 1004401.
* Lampe DJ, Churchill ME, Robertson HM. A purified mariner transposase is sufficient to mediate transposition in vitro. The European Molecular Biology Organization Journal. 1996;15(19):5470–5479.
