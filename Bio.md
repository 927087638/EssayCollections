# CP Pred

Xiaoxue Tong and Shiyong Liu. CPPred: Coding Potential Prediction based on the global description of RNA sequence. Nucleic Acids Research, 1 February 2019 [[PubMed\]](https://www.ncbi.nlm.nih.gov/pubmed/30753596) [[PDF\]](http://rnabinding.com/pdfs/NAR2019_CPPred.pdf)

## 去重复的阈值——80%

> To improve the ==robustness== of the assessment of accuracy, we reduced redundancy between the testing and training sets with a threshold of 80% (62–64)bythe open-source program cd-hit-est-2d in CD-hit (65), which uses a short word filter to avoid unnecessary alignments and has been widely used as a clustering algorithm, resulting in 8557 coding RNAs and 8241 ncRNAs as Human-testing.
>
> The result shows that ==removing redundant sequences with ≥80%== similarity is enough to ==obtain independence between test and training sets==.
>
> That is because RNA sequences only have four letters, it is easy to get high identity between unrelated sequences. When we run a regular blast search, we often find top hits at very high identities. In general, comparing RNAs at low identity ==<75% may not be very effective==.

## features

> We used four features proposed by CPAT (42), including ==ORF length, ORF coverage, Fickett score and Hexamer Score==. Similarly, ORF ==integrity and isoelectric point== were derived from CPC2 (39). Next, the ==Gravy and Instability== mentioned by CPC2 are also added. In addition, the algorithm of Hexamer score and Fickett score were discussed in detail (42,72,73).

