# Tn-Seq Analysis

## Overview
The Tn-Seq Analysis Service facilitates determination of essential and conditionally essential regions in bacterial genomes from data generated from transposon insertion sequencing (Tn-Seq) experiments. Tn-Seq (in the broad sense used here) refers to a family of related methods that use deep sequencing to survey a transposon insertion library and quantify the abundance of insertions at different sites in the genome.

## About this module

This module is a component of the BV-BRC build system. It is designed to fit into the
`dev_container` infrastructure which manages development and production deployment of
the components of the BV-BRC. More documentation is available [here](https://github.com/BV-BRC/dev_container/tree/master/README.md).

There is one application service specification defined here:
1.  [TnSeq Analysis](app_specs/TnSeq.md): Service that that provides the backend for the BV-BRC web inerface; it takes reads as input.

The code in this module provides the BV-BRC application service wrapper scripts for the genome annotation service as well
as some backend utilities:

| Script name | Purpose |
| ----------- | ------- |
| [App-TnSeq.pl](service-scripts/App-TnSeq.pl) | App script for the [TnSeq Analysis Service](https://www.bv-brc.org/docs/quick_references/services/tn_seq_analysis_service.html) |

## See also 
* [Tn-Seq Analysis Service](https://www.bv-brc.org/app/Tnseq)
* [Quick Reference](https://www.bv-brc.org/docs/quick_references/services/tn_seq_analysis_service.html)
* [Tn-Seq Analysis Service Tutorial](https://www.bv-brc.org/docs/tutorial/tn-seq/tn-seq.html)
