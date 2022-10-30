# Chapter_2
## Building a local, customized COI barcoding da-tabase for taxonomic assignment of metabarcoding data
### In this file collection you can find supplementary material relative at Chapter 2 of Francesco Mugnai’s PhD thesis.
#### Please note that all the CSV files have TAB as column separator.
1. The sampling location coordinates and metadata are available in **Data_S1.csv**.
2. All the new barcoded sequences used to build the COInr-Med+ database and submitted to GenBank (Accession numbers ON716004-ON716119), together with their taxonomic and geographic origins, are presented in **Data_S2.csv**.
3. The list of the ASVs (Amplicon Sequence Variants) used in this study and obtained from Wangensteen et al., 2018, are available in **Data_S3.csv**.
4. In **Data_S4.csv**, a list of Mediterranean marine families, obtained from OBIS (www.obis.org) restricting the search field to Mediterranean Sea LME (Large Marine Ecosystem), are listed.
5. A complete step-by-step guide about Perl commands used to create, customize, and format the desired reference databases are available in **Data_S5.html**.
6. The number of taxonomic assignments for each resolution level **from unassigned to species** using four different taxonomic assignment methods (VTAM, QIIME_SKLEARN, QIIME_BLAST and RDP) and four different reference databases are available in **Data_S6.csv**. The QIIME_BLAST algorithm was carried out using three different minimum identity thresholds (80%; 90% and 97%).
7. The taxonomic assignment of all ASVs using the QIIME_BLAST algorithm with 97% identity cutoff and 4 different databases can be found in **Data_S7.csv**.
8. The taxonomic assignment of all ASVs using the QIIME_BLAST algorithm with 90% identity cutoff and 4 different databases is presented in **Data_S8.csv**.
9. **Data_S9.csv** includes the taxonomic assignment of all ASVs using the QIIME_BLAST algorithm with 80% identity cutoff and 4 different databases.
10. In **Data_S10.csv** you can find the taxonomic assignment of all ASVs using the VTAM algorithm and 4 different databases.
11. The taxonomic assignment of all ASVs using the RDP algorithm and 4 different databases can be found in **Data_S11.csv**. Only assignment with at least 70% bootstrap support were accepted.
12. In **Data_S12.csv**, the taxonomic assignment of all ASVs using the QIIME_SKLEARN algorithm and 4 different databases is presented. Only assignment with at least 70% support were accepted.
13. The pairwise comparison of the resolution of taxonomic assignments obtained by using two different databases is shown in **Data_S13.csv**.
14. The taxonomic resolutions of ASVs using different similarity thresholds of QIIME 2 BLAST-based taxonomic assignment algorithm are shown in **Figure_S1.pdf**.
15. The detailed changes in taxonomic resolution between taxonomic assignments of two databases are presented in  **Figure_S2.pdf**.
