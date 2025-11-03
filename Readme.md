Paper: Modulation of the 14-3-3σ/C-RAF “auto”inhibited complex by molecular glues by Markella Konstantinidou et al
https://www.biorxiv.org/content/10.1101/2025.07.30.667769v1.full.pdf


Aim: Disrupt the transition from C-RAF monomer to dimer by stabilizing C-RAF closed intereaction with 14-3-3 dimer. 
Optimize molecular glues to stabilize covalent bonds between 14-3-3 and C-RAF259 as well as polar interaction with CRAF260 residue.
Assays: FP, nanoBRET assays blocking C-RAF N-RAS formation. MS assay between nucleophile (Cysteine38 on 14-3-3) and electrophile - look at % bound +/- C-RAF259 peptide.

FP assay with FAM labeled C-RAF259 peptide + 14-3-3sigma +/- MG

SPR: 
Selectivity assessed by SPR 14-3-3 is considered to recognize between 2 and 20 amino acid residues on the client.  Up to this point, to establish the SAR for C-RAF we used an 11-mer acetylated peptide for the MS assay and a 10-mer FAM-labeled peptide for the FA assay. 

14-3-3σ, tagged with a Twinstrep-tag, was immobilized on a Strep-Tactin XT coated SPR chip. Subsequently, a 2-fold dilution series of acetylated 12-mer C-RAF, A-RAF, and B-RAF peptides were injected. 

14-3-3σ + MG with C-RAF forms a complex -> Immobilized on SPR chip -> C-RAF washed away and C-RAF again added over a concentration range. 

14-3-3 interaction with C-RAF peptides ~ uM range Kd.  14-3-3 + MG interaction with C-RAF peptides ~ nM range Kd (kon increases with MG, koff decreases with MG)

Cellular assays: 
1. NanoBRET between C-RAF (N-luc tagged) and 14-3-3Sigma (Halo tagged), between N-RAS and C-RAF, C-RAF/C-RAF dimerization nano-BRET
2. co-IP in HEK293T cells: N-RAS (GTP bound form) - RAF (FLAG tagged) - 14-3-3 (HA tagged) => co IP with anti-FLAG beads
3. Lumit antibody assay for pERK activation
4. nanoBRET for 14-3-3sigma - A RAF/14-3-3sigma - B RAF as well as A-RAF/B-RAF/C-RAF homo and heterodimers

Paper: "Targeted protein degradation via intramolecular bivalent glues"

Aim: Develop molecule glues targeting BRD2/4 - E3 ligase interactions, these bind the two domains in Cis compared to trans which is the norm with Protacs

General background: 
IBG1 is a protac-like degrader targeting BRD4 using JQ1 and E8720 as the E3 binding segment. 
Proteasome inhibitor - MG132, neddylation inhibitor - MLN   

Figure 1: 
Westerns show degradation of BRD2/4 with increasing IBG1 concentrations. 
Proteomics with DMSO, IBG1 show specific BRD4 degradation by IBG1 compared to dBET6, graph looks at adjusted P-value vs fold-change
nano-BRET ubiquitination and degradation assays:
Bromotag-HiBiT-BRD4 degradation assay: BRD4 degradation with IBG1, rescued by proteasome inhibitor
LgBiT-transfected HiBiT–BromoTag–BRD4 for ubiquitination: BRD4 ubiquitination, no ubiquitination with DMSO or IBG1 + MLN4924 (proteasome inhibitor) or IBG1 + JQ1 (JQ1 binds BRD4 preventing IBG1 from accessing BRD4?)
BRD4 degradaiton with IBG1 is DCAF15 independent - as seen from DACF15 KO cells (sgRNA targeting DCAF15)

Figure 2 - 
FACS based protein stability reporter assay (GFP and mCherry reporters) - report on BRD4 stability
CRISPR screens indicate proteins that are highly expressed with BRD4high in DMSO, IBG1, dBET6 treatments. With IBG1 treatment, DACF16 is expressed as well. 
CRISPR screen for viability indicates which genes are selective with IBG1 treatment
CRISPR screen validation - 
KBM7 iCas9 BRD4–BFP reporter cells were transduced with AAVS1, DCAF16 or DDB1-targeting sgRNAs +/- IBG1 assessing BRD4 abundance:
With just DMSO, BRD4 abundance is similarly high across different sgRNA treated cells
With IBG1, BRD4 abundance is high only in DACF16 sgRNA cell, indicating DACF16 dependance. 
With dBET6, BRD4 abundance is unaffected in DCAF15 sgRNA cell. 
When KBM7 iCas9 BRD4–BFP reporter cells were transduced with AAVS1 or DCAF16-targeting sgRNAs +/- sgRNA-resistant DCAF16 cDNA, ectopic expression of DCAF16 rescues BRD4 expression and degrades it in the presence of IBG1. 
Apoptosis assay with cleaved PARP1 shows increasing cleavage with WT+IBg1, WT+ dBET6, DCAF16KO + dBET6 but not with DACF16 KO+ IBG1
Viability assay shows increased viability with DACF16 KO sgRNA cells with IBG1
FP assay shows IBG1 binding to DACF15 and not DCAF16


