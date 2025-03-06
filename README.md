# HIV-1_mRNA_Atlas

HIV-1 M B NL4-3 mRNA Atlas v1; blat[^1] on 21 queries (MZ242719.1_cds_UED13366.1_1, MZ242719.1_cds_UED13367.1_2, ...). Includes cPPT and nef PPT as off-target blat hits. Source: [GenBank:MZ242719.1](https://www.ncbi.nlm.nih.gov/nuccore/MZ242719.1/).

If using the NL4-3 mRNA Atlas v1, please cite it[^2][^3].

# Previous presentations

[LC2021 Alejandro Gener v1.pdf](https://github.com/user-attachments/files/19116459/LC2021.Alejandro.Gener.v1.pdf)

<iframe src="https://docs.github.com/content/github/managing-files-in-a-repository/working-with-non-code-files/rendering-pdf-documents?url=https://github.com/user-attachments/files/19116459/LC2021.Alejandro.Gener.v1.pdf?raw=true" width="100%" height="500px"></iframe>

[View LC2021 Alejandro Gener PDF](https://docs.github.com/content/github/managing-files-in-a-repository/working-with-non-code-files/rendering-pdf-documents?url=https://github.com/user-attachments/files/19116459/LC2021.Alejandro.Gener.v1.pdf)

# Usage

Available from the [UCSC Genome Browser Public Session Landing Page](https://genome.ucsc.edu/cgi-bin/hgPublicSessions?hgsid=2408999235_6Poc6QfCmUcyIc8M7V7iJCFDMI2v).

Search "MZ242719" for two sessions.

#
## Session 1: mRNA models mapped onto an HIV reference genome with blat (RefSeq:NC_001802.1) First 25 shown.

**Description:** HIV-1 strain NL4-3 mRNA Atlas v1 mRNA transcript models open reading frames (ORFs) mapped onto HIV-1 RefSeq:NC_001802.1. 

**Transcript model method:** Transcript models were downloaded as FASTA from GenBank:MZ242719.1-MZ242757.1 were blat (sic) against NC_001802.1 (GCF_000864765.1) in UCSC. Max number of sequences for blat = 25, so n=38 was partitioned into two blat runs, sorted by accession. These were viewed as a track in UCSC Genome Browser. MZ242719.1, MZ242720.1, MZ242721.1 are models of unspliced, singly-spliced, and doubly-spliced. "Singly-spliced" and "doubly-spliced" have been commonly used in the literature, but without basis in explicitly defined mRNA models. As you can see, HIV-1 NL4-3 splice isoforms supported by high-quality long reads and reanalysis are more complicated that previously understood. Open reading frames (ORFs) method: Coding features were downloaded as FASTA from GenBank:MZ242719.1 were blat (sic) against NC_001802.1 (GCF_000864765.1) in UCSC. These were viewed as a track in UCSC Genome Browser. ORF note 1: Exact ranges for GENER10 and GENER12 differ because of apparent sequence differences at their start codons. This is because blat did not match the small leading exon 5'-ATGGCAG-3' which spans NC_001802.1:4599-4605. This exon is supported by long-read mRNA of NL4-3 infected and transfected cells. ORF note 2: Small regions of homology overlap polypurine tracts important for viral replication. These are not ORFs. ORF note 3: MZ242719.1 (NL4-3) and NC_001802.1 are both HIV-1 subgroup B viruses. NL4-3 is a synthetic chimeric virus reviewed elsewhere. However, it is the most common strain of HIV used in laboratory settings. Both are modeled as "R-U5-HIV-U3-R". 

**Author:** "gener"

**Session Name:** GCF_000864765.1_HIV-1_mRNA_Atlas_v1_blat_mRNA+ORFs

**Genome Assembly:** hub_3521609_GCF_000864765.1

**Creation Date:** 2022-09-21

Note fuzzy mapping of NL4-3 transcriptomic info onto another HIV-1 M B genome (RefSeq).

<img width="1531" alt="Screenshot 2024-12-30 at 7 24 40 PM" src="https://github.com/user-attachments/assets/f4b965b2-aaa7-4410-b718-0ac0a8843239" />

#
## Session 2: mRNA model open reading frames mapped onto an HIV reference genome with blat (RefSeq:NC_001802.1)

**Description:** HIV-1 strain NL4-3 mRNA Atlas v1 open reading frames (ORFs) mapped onto HIV-1 RefSeq:NC_001802.1.

**Method:** Coding features were downloaded as FASTA from GenBank:MZ242719.1 were blat (sic) against NC_001802.1 (GCF_000864765.1) in UCSC. These were viewed as a track in UCSC Genome Browser. Note 1: Exact ranges for GENER10 and GENER12 differ because of apparent sequence differences at their start codons. This is because blat did not match the small leading exon 5'-ATGGCAG-3' which spans NC_001802.1:4599-4605. This exon is supported by long-read mRNA of NL4-3 infected and transfected cells. Note 2: Small regions of homology overlap polypurine tracts important for viral replication. These are not ORFs. Note 3: MZ242719.1 (NL4-3) and NC_001802.1 are both HIV-1 subgroup B viruses. NL4-3 is a synthetic chimeric virus reviewed elsewhere. However, it is the most common strain of HIV used in laboratory settings. Both are modeled as "R-U5-HIV-U3-R". 

**Author:** "gener"

**Session Name:** GCF_000864765.1_HIV-1_mRNA_Atlas_v1_blat_ORFs

**Genome Assembly:** hub_3521609_GCF_000864765.1

**Creation Date:** 2022-09-20

Novel splice isoforms support additional accessory proteins.

Note downstream tat/rev/env splice acceptor sequences splice to a common upstream integrase donor.

<img width="1532" alt="Screenshot 2024-12-30 at 7 20 08 PM" src="https://github.com/user-attachments/assets/52c33b13-5aae-4630-b8f0-699ee97dab85" />

[^1]: Kent WJ. BLAT--the BLAST-like alignment tool. Genome Res. 2002 Apr;12(4):656-64. doi: 10.1101/gr.229202. PMID: 11932250; PMCID: PMC187518.

[^2]: Gener, A. R., Klotman, P. E., Danesh, F. R., Cijiang He, J., Kimata, J. T., Lupski, J. R., & Ross, M. J. (2021). HIV informatics. Baylor College of Medicine Integrative Molecular and Biomedical Sciences Graduate Program.

[^3]: Gener, A. R. (2022). Anticipating HIV drug resistance with appropriate sequencing methods. AIDS, 36(1). https://journals.lww.com/aidsonline/Fulltext/2022/01010/Anticipating_HIV_drug_resistance_with_appropriate.16.aspx.
