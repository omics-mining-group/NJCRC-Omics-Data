# NJCRC Omics Database

### This is an integrative omics datasets across genome, epigenome, transcriptome, and proteome from 79 patients recruited from Nanjing ColoRectal Cancer cohort (NJCRC), which included 30 early-onset colorectal cancer (EOCRC) and 49 late-onset colorectal cancer (LOCRC) cases. 

![image](https://github.com/omics-mining-group/NJCRC-Omics-Data/blob/master/image/Figure-1_2.png)


## Genomic data

We carried out both WGS and WES paired-end sequencing reactions for 27 and 52 pairs of tumors and NATs, respectively, under collaborations with Novogene Co., Ltd (Beijing, China). Briefly, DNA was extracted from fresh frozen tissue blocks using QIAGEN QIAamp DNA Mini Kit. For WGS, library preparation was performed using at least of 0.8 g genomic DNA per sample with high molecular weight (> 20 kb single band) via TruSeq Nano DNA HT Library Prep Kit. Pooled DNA libraries were sequenced on Illumina HiSeq X Ten platform with 150-bp paired-end sequencing. For WES, library construction and whole-exome capture of genomic DNA were performed using the SureSelectXT Reagent Kit (Agilent) and SureSelectXT Human All Exon V6 Kit (Agilent). The captured DNA was then sequenced on an Illumina HiSeq 2500 sequencing platform, with 150-bp paired-end sequencing.

## Transcriptome data

The transcriptome of 79 pairs of tumors and NATs were generated in collaboration with Novogene Co., Ltd (Beijing, China) using the Illumina HiSeq 2500 platform with 150bp sequencing based on Standard Illumina RNA sequencing (RNA-Seq) protocol. RNA was extracted from fresh frozen tissue blocks using the QIAGEN AllPrep DNA/RNA Mini Kit following the manufacturer’s instructions. RNA reads were generated, aligned to the GENCODE v19 genome assembly with HISAT2 (version 2.0.4) (Kim et al., 2019), and quantified with StringTie (version 1.3.4) (Pertea et al., 2016). Cufflinks (version 2.1.1) (Roberts et al., 2011) was then used to quantify the gene expression abundance and calculate the standardized gene expression (represented as fragments per kilobase per million mapped reads [FPKM]) for each sample.

## DNA methylation data

DNA methylation profiling for 43 pairs of tumors and NATs (including 24 EOCRC and 19 LOCRC) were collaborated with CapitalBio (Beijing, China) using Illumina Infinium HumanMethylation EPIC BeadChip, which covered over 850,000 CpG loci across the whole human genome at single-nucleotide resolution. Simply, EZ DNA Methylation Kit (Zymo Research) was used to perform sodium bisulfite-treated arrays for genomic DNA. To minimize batch effects, pairs of tumor and normal tissues were randomly distributed to different arrays. The bisulfiteconverted genomic DNA was isothermally amplified overnight and fragmented enzymatically. Precipitated DNA using isopropyl alcohol was resuspended in hybridization buffer and dispensed onto BeadChips (8 samples/chip). The hybridization procedure was performed at 48°C overnight using an Illumina hybridization oven. After hybridization, free DNA was washed away and BeadChips were processed through a single nucleotide extension followed by immunohistochemistry staining. Finally, we downloaded the manifest files of each array in advance and imaged BeadChips using an Illumina iScan.

## Proteome data

TMT is a chemical label used for mass spectrometry (MS)-based identification and quantitation of proteins. In this study, we collaborated with Novogene Co., Ltd (Beijing, China) to detect proteome for 37 pairs of tumors and NATs. Briefly, BSA quantitative kit was used to quantify extracted tissue proteins, followed by quality control using SDS-PAGE gel electrophoresis and Coomassie brilliant blue R-250 staining. Eligible protein samples were labeled using TMT labeling reagents, which were then mixed with equal volume. For multiple labeled groups, a common reference was created by pooling an equal quantity of each sample. Separation of fractions were performed using L3000 HPLC system (Rigol). Shotgun proteomics analyses were performed using an EASY-nLCTM 1200 UHPLC system (Thermo Fisher) coupled with an Q Exactive HF (X) mass spectrometer (Thermo Fisher) operating in the datadependent acquisition (DDA) mode. 


## Citation:
Characterization of integrative omics in early-onset colorectal cancer. Unpublished.


## Contact:
E-mail: Mulong Du (drdumulong@njmu.edu.cn), or Junyi Xin (junyixin123@126.com). Department of Environmental Genomics (PIs: Prof. Zhengdong Zhang and Meilin Wang), School of Public Health, Nanjing Medical University, Nanjing, China.
