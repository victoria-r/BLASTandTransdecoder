# blastPep.sh

This program aligns proteins from the open reading frame to SwissProt. This is done using BLASTP.

# pfamScan.sh

This program runs hmmscan to find protein domains. This takes the protein sequeces found in the open reading frame's and searches those against the profile-HMM database.

# predictProteins.sh

This program uses the 'TransDecoder. Predict' program to predict the likely coding regions from the open reading frame's that were identifies from Transdecoder.LongOrfs. The homology searhes will aslo be incuded in the open reading frame retention criteria. 

# alignPredicted.sh

This program aligns the output of TransDecoder.Predict against SwissProt, and sets a filter for evaluate < 1e-10 with the output in tabular format.

## Getting Started

### Dependencies

* bash

## Author

Victoria R. Liebsch

## Date Created - All programs

7 November 2021
