# hse_hw3_chromhmm

Во 2 дз брали клеточную линию Loucy, но на  UCSC Genome Browser ее не было, так что взяли HeLa-S3. 

№ | метка | имя файла 
--- | --- | --- 
1 | H2A.Z | wgEncodeBroadHistoneHelas3H2azAlnRep1.bam
2 | H3K27ac | wgEncodeBroadHistoneHelas3H3k27acStdAlnRep1.bam 
3 | H3K27me3 | wgEncodeBroadHistoneHelas3H3k27me3StdAlnRep1.bam
4 | H3K36me3 | wgEncodeBroadHistoneHelas3H3k36me3StdAlnRep1.bam
5 | H3K4me1 | wgEncodeBroadHistoneHelas3H3k04me1StdAlnRep1.bam
6 | H3K4me2 |  wgEncodeBroadHistoneHelas3H3k4me2StdAlnRep1.bam
7 | H3K4me3 | wgEncodeBroadHistoneHelas3H3k4me3StdAlnRep1.bam
8 | H3K79me2 | wgEncodeBroadHistoneHelas3H3k79me2StdAlnRep1.bam
9 | H3K9ac | wgEncodeBroadHistoneHelas3H3k9acStdAlnRep1.bam
10 | H3K9me3 | wgEncodeBroadHistoneHelas3H3k09me3AlnRep1.bam  
Control | Control | wgEncodeBroadHistoneHelas3ControlStdAlnRep1.bam

[google colab](https://colab.research.google.com/drive/1IvevredzNjuxWlJY2-PAkYTDKgaAErlw?usp=sharing)

Эпигенетические типы

![](https://github.com/inlkbr/hse_hw3_chromhmm/blob/a3ed5df70eeb3c0e25b31e88028dae60bd53ab93/HeLa-S3_10_overlap%20(1).png)
![](https://github.com/inlkbr/hse_hw3_chromhmm/blob/a3ed5df70eeb3c0e25b31e88028dae60bd53ab93/emissions_10.png)
![](https://github.com/inlkbr/hse_hw3_chromhmm/blob/a3ed5df70eeb3c0e25b31e88028dae60bd53ab93/transitions_10.png)
![](https://github.com/inlkbr/hse_hw3_chromhmm/blob/a3ed5df70eeb3c0e25b31e88028dae60bd53ab93/HeLa-S3_10_RefSeqTES_neighborhood%20(1).png)
![](https://github.com/inlkbr/hse_hw3_chromhmm/blob/a3ed5df70eeb3c0e25b31e88028dae60bd53ab93/HeLa-S3_10_RefSeqTSS_neighborhood%20(1).png)

![](https://github.com/inlkbr/hse_hw3_chromhmm/blob/a3ed5df70eeb3c0e25b31e88028dae60bd53ab93/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-03-24%20211626.png)


№ |  их характерные эпигенетические метки и другие свойства | присвоенные названия 
--- | --- | --- 
1 | Попадает на интроны, между генов. Выражен в  H3K4me1. RefSeqTES, lamina  | Weak enhancer
2 | Попадает в интроны, выражен в H2A.Z, H3K4me1, H3K4me2. (а вообще его очень мало) | Weak enhancer
3 | Попадает в интроны, между генов, выражен в H2A.Z (тоже почти не видно). GpG островки и вообще везде поненмогу | Active Promoter
4 | Попадает в интроны и экзоны, между генов, выражен в H2A.Z, H3K4me1, H3K4me2, H3K4me3, H3K9ac, H3K27ac. GpG островки, RefSeqTES, RefSeqTSS | Active Promoter
5 | Попадает в экзоны и интроны, выражен в  H2A.Z, H3K79me2, H3K4me2. RefSeqTES, RefSeqTSS | Active Promoter
6 | Попадает в экзоны и интроны, выражен в  H3K79me2, H3K36me3. Попадает на RefSeqПуту | Weak transcribed
7 | Попадает в экзоны и интроны, между генов, выражен в H3K79me2. RefSeqTES | Weak enhancer 
8 | Попадает в экзоны и интроны, выражен в H3K36me3. RefSeqGene, RefSeqTES | Weak transcribed
9 | Попадает в интроны, выражен в H3K27me3. Lamina. | Weak enhancer
10 | Попадает в экзоны и интроны, между генов, кажется самым распространенным, но не выражен явно где-то. Genome %, lamina | Weak enhancer
