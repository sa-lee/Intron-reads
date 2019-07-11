**Supplementary Figures** 

*Supplementary figure 1* : RNA protocols are compared for gene-level exon log-CPM (left) and gene-level intron log-CPM values (right) for human cell line HCC827 R1, R2, R3, human cell line NCI-H11975 R1, R2, and R3 (in order of plots shown).

*Supplementary figure 2* : From left to right, intron versus exon log-CPM, intron versus exon log-RPKM, intron log-RPKM versus total intron length, relative coverage between exon and intron regions versus total intron length, and relative coverage versus exon log-RPKM; with poly(A) RNA (top row) and Total RNA libraries (bottom row). The plots are displayed for human cell line HCC827 R1, R2, R3, human cell line NCI-H11975 R1, R2, and R3 (in order of plots shown).



**Scripts for Annotations**

*gtf_to_exon_saf.R* : Convert gtf file to simplified exon locations and save in saf format (also saves GENCODE gene information to txt).

*exon_saf_to_genebody_and_intron_saf.R* : Exon saf file is used to create genebody saf and intron saf files.

*genebody_saf_to_nonoverlapping_genebody_saf.R* : Create genebody saf file for non-overlapping genes.
