# drug target prediction
https://onlinelibrary.wiley.com/doi/abs/10.1002/pro.4555

The development of efficient computational methods for drug target protein identification can compensate for the high cost of experiments and is therefore of great significance for drug development. However, existing structure-based drug target protein-identification algorithms are limited by the insufficient number of proteins with experimentally resolved structures. Moreover, sequence-based algorithms cannot effectively extract information from protein sequences and thus display insufficient accuracy. Here, we combined the sequence-based self-supervised pre-training protein language model ESM1b with a graph convolutional neural network (GCN) classifier to develop an improved, sequence-based drug target protein identification method. This complete model, named QuoteTarget, efficiently encodes proteins based on sequence information alone and achieves an accuracy of 95% with the non-redundant drug target and non-drug target datasets constructed for this study. When applied to all proteins from Homo sapiens, QuoteTarget identified 1,213 potential undeveloped drug target proteins. We further inferred residue-binding weights from the well-trained network using the gradient-weighted class activation mapping (Grad–Cam) algorithm. Notably, we found that without any binding site information input, significant residues inferred by the model closely match the experimentally confirmed drug molecule-binding sites. Thus, our work provides a highly effective sequence-based identifier for drug target proteins, as well to yield new insights into recognizing drug molecule-binding sites. The entire model is available at https://github.com/Chenjxjx/drug-target-prediction.


## Workflow
![image](https://github.com/Chenjxjx/drug-target-prediction/edit/master/f1.pdf)
## Requirements
## Citation
## References
