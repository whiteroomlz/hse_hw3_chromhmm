# hse_hw3_chromhmm
Ссылка на блокнот: https://colab.research.google.com/drive/106Qv0K_StWcpg8RQl9aws2yQXDWqHPCJ?usp=share_link
# Обязательная часть
## Гистоновые метки
|**Клеточная линия**|**Файл**|**Метка**|**Контроль**|
|-|-|-|-|
|A549|[wgEncodeBroadHistoneA549H2azDex100nmAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549H2azDex100nmAlnRep1.bam)|H2A.Z|[ControlDex100nmAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549ControlDex100nmAlnRep1.bam)|
|A549|[wgEncodeBroadHistoneA549H3k27acDex100nmAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k27acDex100nmAlnRep1.bam)|H3K27ac|[ControlDex100nmAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549ControlDex100nmAlnRep1.bam)|
|A549|[wgEncodeBroadHistoneA549H3k27me3Dex100nmAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k27me3Dex100nmAlnRep1.bam)|H3K27me3|[ControlDex100nmAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549ControlDex100nmAlnRep1.bam)|
|A549|[wgEncodeBroadHistoneA549H3k36me3Dex100nmAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k36me3Dex100nmAlnRep1.bam)|H3K36me3|[ControlDex100nmAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549ControlDex100nmAlnRep1.bam)|
|A549|[wgEncodeBroadHistoneA549H3k04me1Dex100nmAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k04me1Dex100nmAlnRep1.bam)|H3K4me1|[ControlDex100nmAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549ControlDex100nmAlnRep1.bam)|
|A549|[wgEncodeBroadHistoneA549H3k04me2Dex100nmAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k04me2Dex100nmAlnRep1.bam)|H3K4me2|[ControlDex100nmAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549ControlDex100nmAlnRep1.bam)|
|A549|[wgEncodeBroadHistoneA549H3k04me3Dex100nmAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k04me3Dex100nmAlnRep1.bam)|H3K4me3|[ControlDex100nmAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549ControlDex100nmAlnRep1.bam)|
|A549|[wgEncodeBroadHistoneA549H3k79me2Dex100nmAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k79me2Dex100nmAlnRep1.bam)|H3K79me2|[ControlDex100nmAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549ControlDex100nmAlnRep1.bam)|
|A549|[wgEncodeBroadHistoneA549H3k09acEtoh02AlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k09acEtoh02AlnRep1.bam)|H3K9ac|[ControlEtoh02AlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549ControlEtoh02AlnRep1.bam)|
|A549|[wgEncodeBroadHistoneA549H3k09me3Etoh02AlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k09me3Etoh02AlnRep1.bam)|H3K9me3|[ControlEtoh02AlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneA549ControlEtoh02AlnRep1.bam)|
## ChromHMM
### Ссылка на *_dense.bed: https://drive.google.com/file/d/1w6eQZn1DaQe031Se-ZTdmSinozNn-NB6/view?usp=share_link
|**Emission**|**Fold Enrichment**|**Transition**|
|-|-|-|
![image1](https://github.com/whiteroomlz/hse_hw3_chromhmm/blob/8ac4f101842bd7aea5f64338384776c1366a64d5/data/emissions_10.png) | ![image2](https://github.com/whiteroomlz/hse_hw3_chromhmm/blob/8ac4f101842bd7aea5f64338384776c1366a64d5/data/A549_10_overlap.png) | ![image3](https://github.com/whiteroomlz/hse_hw3_chromhmm/blob/8ac4f101842bd7aea5f64338384776c1366a64d5/data/transitions_10.png)

![image4](https://github.com/whiteroomlz/hse_hw3_chromhmm/blob/8ac4f101842bd7aea5f64338384776c1366a64d5/data/A549_10_RefSeqTES_neighborhood.png)
![image5](https://github.com/whiteroomlz/hse_hw3_chromhmm/blob/8ac4f101842bd7aea5f64338384776c1366a64d5/data/A549_10_RefSeqTSS_neighborhood.png)
## UCSC GenomeBrowser
Nikita Borodin, [05.04.2023 19:13]
### Таблица
|Состояние|Название|Анализ|
|-|-|-|
|1|Heterochromatin|Характерен для H3K9me3 и H3K27me3 (в наибольшей мере H3K27me3); не попадает на ген; чаще всего располагается на laminB1lads, т.е. на участке репрессированного гетерохроматима.|
|2|Heterochromatin|Характерен только для H3K9me3; не попадает на ген; чаще всего располагается на laminB1lads, т.е. на участке репрессированного гетерохроматима.|
|3|Heterochromatin|Характерен для H3K9me3, реже встречается на H3K36me3; не попадает на ген; чаще всего располагается на laminB1lads, т.е. на участке репрессированного гетерохроматима.|
|4|Weak transcribed|Наиболее выражен для H3K36me3, в меньшей мере для H3K79me2 и H3K4me1; чаще всего располагается на RefSeqTES, RefSeqGene, реже на RefSeqExon; попадает на интрон или экзон.|
|5|Weak transcribed|Наиболее выражен для H3K79me2, в меньшей мере для H3K36me3 и H3K4me1; чаще всего располагается на RefSeqGene; попадает на интрон.|
|6|Weak enhancer|Наиболее выражен для H3K79me2 и H3K4me1; чаще всего располагается на RefSeqGene, реже на RefSeqTES; попадает на интрон.|
|7|Repressed|Наиболее выражен для H3K4me1 и H2A.Z; не попадает на ген; локализация слабая, преимущественно на laminB1lads.|
|8|Strong enhancer|Наиболее выражен для H3K4me1 и H2A.Z; чаще всего располагается на RefSeqTES и RefSeqTSS2Kb, чуть реже на laminB1lads; попадает на интрон или экзон.|
|9|Active promoter|Ярко выражен для большинства меток; чаще всего располагается на CpGIslands, RefSeqExon, RefSeqTES, RefSeqTSS2Kb, реже на  RefSeqTES; попадает на интрон или экзон, не попадает на ген.|
|10|Active promoter|Ярко выражен для большинства меток; чаще всего располагается на RefSeqTES, RefSeqTSS2Kb, реже на CpGIslands, RefSeqExon, RefSeqTES; попадает на интрон или экзон, не попадает на ген.|

![image6](https://github.com/whiteroomlz/hse_hw3_chromhmm/blob/9dcd7494e90baacff3fc3f8d4f8b91dbf90a3027/raw/hgt_genome_13259_d4fc00.jpg)
|-|
![image7](https://github.com/whiteroomlz/hse_hw3_chromhmm/blob/9dcd7494e90baacff3fc3f8d4f8b91dbf90a3027/raw/hgt_genome_32054_d50210.jpg)
