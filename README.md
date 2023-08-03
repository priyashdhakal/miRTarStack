## An Ensemble of Stacking Classifiers for Improved Prediction of miRNA-mRNA Interactions


## Abstract

MicroRNAs (miRNAs) are small non-coding RNA molecules that play a crucial role in regulating gene expression at the post-transcriptional level by binding to
potential target sites of messenger RNAs (mRNAs), facilitated by the Argonaute family of proteins. Selecting the conservative candidate target sites (CTS) is 
a challenging step, considering that most of the existing computational algorithms primarily focus on canonical site types, which is a time-consuming and inefficient
utilization of miRNA target site interactions. We developed a stacking classifier algorithm that addresses the CTS selection criteria using feature-encoding techniques
that generates feature vectors, including k-mer nucleotide composition, dinucleotide composition, pseudo-nucleotide composition, and sequence order coupling. 
This innovative stacking classifier algorithm surpassed previous state-of-the-art algorithms in predicting functional miRNA targets. We evaluated the performance of 
the proposed model on 10 independent test datasets and obtained an average accuracy of 79.77%, which is a significant improvement of 7.26 % over previous models.
This improvement shows that the proposed method has great potential for distinguishing highly functional miRNA targets and can serve as a valuable tool in biomedical
and drug development research.

## Dataset

Please refer to the provided datasets folder for more details.

## citation
```bibtex
@article{dhakal2023ensemble,
  title={An ensemble of stacking classifiers for improved prediction of miRNA-mRNA interactions},
  author={Dhakal, Priyash and Tayara, Hilal and Chong, Kil To},
  journal={Computers in Biology and Medicine},
  pages={107242},
  year={2023},
  publisher={Elsevier}
}
