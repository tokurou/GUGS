## <b>GUGS</b>: General Utilities for Genotyping Studies

### About

<b>General Utilities for Genotyping Study (GUGS) </b> is a suite for the evaluation and conversion of genotype data in the MS Excel environment. Three major genotype formats, simple sequence repeat (<b>SSR</b>, aka short tandem repeat; STR), single nucleotide polymorphism (<b>SNP</b>), or <b>single-letter genotype</b>, are supported with their accompanying data formats in GUGS. All of the capabilities of GUGS were implemented as a function, and users can combine them with the built-in functions of MS Excel seamlessly. GUGS provides more than 100 functions that consist of basic operations to support genotype data format conversion for linkage analysis, functions for frequency analysis of a DNA marker or population, parentage analysis with functions to validate the proposed relationships by a statistical genetic approach, and formatting data for linkage analysis. The basic evaluation supports SSR marker format (two numeric), SNP marker format (two alphabetic letters), and the single-letter genotype of MapMaker/JoinMap (A/B/H). Data formatting functions support the conversion of SSR/SNP to the single-letter genotype of MapMaker and equivalents or the two-letter genotype such as the CP mode of JoinMap. Users are not requested to sort or format the data before evaluation or conversion; users can execute all the functions at any place in the spreadsheet. A set of functions to manipulate nucleotide or amino acid sequence will support DNA marker design.  

Though GUGS does not support a graphical user interface (GUI), it does not require formatting the user data in a predetermined style, and it extends the functionality according to the user’s demands. The current version of GUGS does not support an advanced analysis, such as simulation-based methods (e.g., MCMC), phylogenetic analysis (UPGMA, Neighbor-Joining, maximum likelihood, or else), or linkage map construction because various excellent applications are already available. GUGS enables users to evaluate their genotype data and convert it between different formats for further analysis on a single environment without any efforts to export/import data. Users can confirm the usage of individual functions by referring to the ‘GUGS workbook’ which is included in the GUGS.xlsm file.

### How to use GUGS

* GUGS is a VBA application of MS Excel. Download the `GUGS_xxxx.xlsm` file (<i>xxxx</i> represents the version).  
This file includes VBA code of GUGS and a tutorial workbook to learn how GUGS will work.
* You can launch GUGS by opening the GUGS.xlsm file. No prerequisite steps are required for installation. However, MS Excel prohibits the automatic VBA execution in default; therefore, users need to enable VBA execution when launching GUGS.
* Any user data should be saved in ‘Excel Macro-Enabled Workbook (\*.xlsm)’ format to keep GUGS functionalities.
* See the manual to consult the usage of each function.

### Version history
* 04 Oct 2021 - ver.1.01 released
* 24 Oct 2017 - ver.1.00 released.

### License
Copyright (c) 2013 - 2017, Tokurou Shimizu, All right reserved.  
GUGS is distributed under the GNU General Public License Version 3 (GPL3).

### Citation
Shimizu, T. (2021) General Utilities for Genotyping Study (GUGS): A Comprehensive Application in Genotype and Sequence Data Manipulation. JARQ 55 (4), 333-339.

### Publications
GUGS have been used in the following publications successfully:
* [Shimizu, T., Kitajima, A., Nonaka, K., Yoshioka, T., Ohta, S., Goto, S., et al. (2016). Hybrid origins of citrus varieties inferred from DNA marker analysis of nuclear and organelle genomes. <b>PLoS One</b> 11, e0166969. doi:10.1371/journal.pone.0166969.](http://dx.plos.org/10.1371/journal.pone.0166969)
* [Shimizu, T., Kaminuma, E., Nonaka, K., Yoshioka, T., Goto, S., Matsumoto, T., et al. (2016). A genomic approach to selecting robust and versatile SNP sets from next-generation sequencing data for genome-wide association study in citrus cultivars. <b>Acta Hortic.</b> 1135, 23–32. doi:10.17660/ActaHortic.2016.1135.4.](http://www.actahort.org/books/1135/1135_4.htm)
* [Minamikawa, M. F., Nonaka, K., Kaminuma, E., Kajiya-Kanegae, H., Onogi, A., Goto, S., et al. (2017). Genome-wide association study and genomic prediction in citrus: Potential of genomics-assisted breeding for fruit quality traits. <b>Sci. Rep.</b> 7, 4721. doi:10.1038/s41598-017-05100-x.](http://www.nature.com/articles/s41598-017-05100-x)


### Funding
GUGS has been supported by a grant from the Ministry of Agriculture, Forestry and Fisheries of Japan (Genomics-based Technology for Agricultural Improvement, NGB-1006, NGB-2009).


#### Version history
##### ver.1.01 - 04 Oct 2021
* A bug of <i>ssrpd</i> and <i>snppd</i> that do not reply value was fixed.
* A bug of <i>snp2cpgt</i> that returned an ambiguous value for a particular case was fixed.
* A bug in <i>splitseq</i> that did not process a nucleotide sequence given that contains LineFeed was fixed.
* Fixed behavior of <i>bracket</i>, <i>motifcount</i>, <i>firstmotif</i>, <i>findmotif</i>, <i>markmotif</i>, <i>matchseq</i>, and <i>matchscore</i> in accordance with the bug fix of <i>splitseq</i>.
* <i>nuc2aa</i>	The frame assignment became optional.
* Minor bug fix: <i>fold</i>, <i>GCratio</i>, <i>toRNA</i>, <i>toDNA</i>, <i>RNA2Dnuc</i>, <i>DNA2Rnuc</i>, <i>clip3</i>, <i>clip5</i>, <i>motifcount</i>, <i>findmotif</i>, <i>firstmotif</i>, and <i>markmotif</i>.
* Introduces applications for the dynamic evaluation of genetic identity and shared alleles and a scheme for DNA marker design.
* VBA scripts became digitally signed.
* Citation was updated.


