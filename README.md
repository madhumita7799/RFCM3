# RFCM3
Identification of miRNA-mRNA regulatory modules from paired expression profiles.

# Related Articles
S. Paul and Madhumita, RFCM3: Computational Method for Identification of miRNA-mRNA Regulatory Modules in Cervical Cancer, IEEE/ACM Transactions on Computational Biology and Bioinformatics, 17(5), pp.1729-1740,2020.
URL: https://ieeexplore.ieee.org/abstract/document/8691563

S. Paul and Madhumita, Robust Computational Method for Identification of miRNA-mRNA Modules in Cervical Cancer, Proceedings of 18th IEEE International Conference on Data Mining Workshops (ICDMW2018): 6th Workshop on Data Mining in Biomedical Informatics and Healthcare (DMBIH2018), Singapore, pp.740--747, November, 2018.
URL: https://ieeexplore.ieee.org/document/8637570

# Abstract
Cervical cancer is a leading severe malignancy throughout the world. Molecular processes and biomarkers leading to tumor progression in cervical cancer are either unknown or only partially understood. An increasing number of studies have shown that microRNAs play an important role in tumorigenesis so understanding the regulatory mechanism of miRNAs in gene-regulatory network will help elucidate the complex biological processes that occur during malignancy. Functional genomics data provides opportunities to study the aberrant microRNA-messenger RNA (miRNA-mRNA) interaction. Identification of miRNA-mRNA regulatory modules will aid deciphering aberrant transcriptional regulatory network in cervical cancer but is computationally challenging. In this regard, an algorithm, termed as relevant and functionally consistent miRNA-mRNA modules (RFCM3), is proposed. It integrates miRNA and mRNA expression data of cervical cancer for identification of potential miRNA-mRNA modules. It selects set of miRNA-mRNA modules by maximizing relation of mRNAs with miRNA and functional similarity between selected mRNAs. Later, using the knowledge of the miRNA-miRNA synergistic network different modules are fused and finally a set of modules are generated containing several miRNAs as well as mRNAs. This type of module explains the underlying biological pathways containing multiple miRNAs and mRNAs. The effectiveness of the proposed approach over other existing methods has been demonstrated on a miRNA and mRNA expression data of cervical cancer with respect to enrichment analyses and other standard metrices. The prognostic value of the genes in a module with respect to cervical cancer is also demonstrated. The approach was found to generate more robust, integrated, and functionally enriched miRNA-mRNA modules in cervical cancer.

# Instructions 
The source code is written in C language and compiled in LINUX environment having machine configuration iCore i7-6700CPU, 3.6 GHz,6MB cache, and 4GB RAM.
Dowload the compressed executable code and then follow the instructions from terminal/console:
$tar -xvf filename.tar -C extraction_dir/
$chmod 777 filemane
$./filename -h
Follow the README file for further details.

