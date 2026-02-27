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

Generation of HiBiT-BRD4 cells: ssODN donor template + spCas9 + sgRNA directed towards knock-in of BRD4/BRD2 in HEK293 cells through electropporation -> validated by luminescence using HibiT lytic assay

HiBiT- BRD4 tagged HEK293 cells + (LgBiT + Halo-Ub cDNA) plasmids transfected into cells -> +/- Halo tagged nanoBRET ligand -> Replace with media + Vivazine substrate (Substrate for HiBiT-lgBiT complementation)-> NanoBRET ratio calculation (460 nm donor/618 nm acceptor) minus halo tagged nanoBRET ligand control => assess ubiquitination rate

Degradation with HiBit-BRD4 cells + LgBiT transfection + Endurazine substrate  -> Observe luminescence over time (Vivazine and Endurazine are furimazine based substrates that extend lifetime)


BRD4 degradaiton with IBG1 is DCAF15 independent - as seen from DACF15 KO cells (sgRNA targeting DCAF15)

Figure 2 - 
FACS based protein stability reporter assay (GFP and mCherry reporters) - report on BRD4 stability
CRISPR screens indicate proteins that are highly expressed with BRD4high in DMSO, IBG1, dBET6 treatments. With IBG1 treatment, DACF16 is expressed as well.CRISPR screen identifies which KOs result in high BRD4 expression with IBG1 treatment. 

Tranduce cells with sgRNA library -> induce Cas9 with Doxycycline -> Treat with a degrader -> Sort with FACS to BRD4high (degradation resistant), BRD4 low (Degradation sensitive) -> Sequence sgRNA from each population -> Compared BRD4^high to low to find enriched sgRNA

CRISPR screen for viability indicates which genes are selective with IBG1 treatment

CRISPR screen validation - 
KBM7 iCas9 BRD4–BFP reporter cells were transduced with AAVS1, DCAF16 or DDB1-targeting sgRNAs +/- IBG1 assessing BRD4 abundance:
AAVS1 - negative control, safe harbor site for genome editing
DDB1 - adaptor protein in CRL complex
DACF16 - Substrate receptor in CRL complex

With just DMSO, BRD4 abundance is similarly high across different sgRNA treated cells
With IBG1, BRD4 abundance is high only in DACF16 sgRNA cell, indicating DACF16 dependance. 
With dBET6, BRD4 abundance is unaffected in DCAF15 sgRNA cell. 

When KBM7 iCas9 BRD4–BFP reporter cells were transduced with AAVS1 or DCAF16-targeting sgRNAs +/- sgRNA-resistant DCAF16 cDNA, ectopic expression of DCAF16 rescues BRD4 expression and degrades it in the presence of IBG1. 
Apoptosis assay with cleaved PARP1 shows increasing cleavage with WT+IBg1, WT+ dBET6, DCAF16KO + dBET6 but not with DACF16 KO+ IBG1
Viability assay shows increased viability with DACF16 KO sgRNA cells with IBG1 => DACF16 KO increases tolerance of IBG1 in cells
FP assay shows IBG1 binding to DACF15 and not DCAF16

Figure 3: 

1. In vitro measurement of ternary interaction: DCAF16– DDB1(ΔBPB)–DDA1 binding to pre-incubated BRD4Tandem–IBG1 complex by ITC

ITC with DCAF16 + BRD4^Tandem
Kd = 4 µM (weak binding)
ΔH = −8 kJ/mol (slightly exothermic - some favorable bonds)
TΔS = 22.5 kJ/mol (modest entropy gain)
ΔG = −30.6 kJ/mol

ITC - DCAF16- BRD4^Tandem With IBG1:
Kd = 0.567 µM (7× tighter!)
ΔH = +38 kJ/mol (endothermic - unfavorable!)
TΔS = 73.9 kJ/mol (huge entropy gain!)
ΔG = −35.7 kJ/mol (more favorable overall)
n = 0.75 (n = 0.7–1.3 is typical, not all of the protein may be active)

2. TR-FRET with Europium-labelled anti-His bound to BRD4Tandem was incubated and equimolar Cy5-labelled DCAF16–DDB1(ΔBPB)–DDA1 and increasing concentrations of IBG1 or JQ1 => with IBG1 more higher potency observed. As well, DACF16-BRD4 tandem interaction observed in the absence of IBG1 but with higher EC50. 
3. SEC - co-elution of DACF16 and BRD4^tandem, further stabilized by IBG1. Do not see the co-elution with the BD1/BD2. 
4. Alphalisa displacement assay -
5. BET stability reporter assay with different Bromodomain mixing and matching - indicates BD2 maintains selectivity of BRD4 over BRD3, and BD1 - BD2 need to be in tandem to

Figure 4:
1. SEC analysis of BRD4^tandem + DMSO/JQ1 shows lower RT compared to + IBG1 indicating compaction and lower hydrodynamic radius with IBG1 (Higher MW elutes first)
2. Also make IBG3, which is more potent than IBG1 as tested in BRD4 degradation, BRD4-DACF16 TR-FRET as well as ITC (showing endothermic profile as with IBG1). Hypothesis - bifunctional compounds with two high-affinity bromodomain ligands should stabilize the degradation-competent bromodomain conformations, enabling generation of more DACF16 degraders

Figure 5: 
1. IBG4 shows BRD4 degradation in KBM7 cells, SEC shows compaction as did IBG1
2. CRISPR–Cas9 BRD4 stability screen- KBM7 iCas9 BRD4 reporter cells expressing a CRL-focused sgRNA library were treated with IBG4 and results in DCAF11 enrichment at BRD4high signal => DCAF11 mediates resistance to IBG4
3. TR-FRET: DCAF11 showed measurable intrinsic affinity for BRD4 in TR-FRET (Fig. 5f) and this interaction was significantly
enhanced in the presence of IBG4 (5g)
4. Summary of monovalent glue vs bivalent glues (PROTACS) vs intramolecule glue (IBG1/IBG4 as presented here) provided

They discovered that a compound designed as a DCAF15 PROTAC actually works as a DCAF16 intramolecular bivalent glue through a completely different mechanism!


Paper: Molecular basis of proton sensing by G protein-coupled receptors
Matthew K. Howard et al, 2025

This paper illuminates the proton sensing mechanism of GPCRS - GPR4, GPR65, GPR68. They generate cryo-EM structures of GPRs, perform deep mutational scan of every residue evaluating the effect of each mutation on expression as well as signaling,constant pH MD simulations that give insights into the mechanism. Not a single residue is responsible for the proton recognition - rather, a network of titrable residues determines framework of proton sensing and recognition by these GPCRs. 

Figures 1/S1 - Determine pH50 (pH at which 50% activation of GPCR is observed) for the three GPRs - GPR4 has highest pH50 (8) and GPR68 lowest (6.8) determined by Glosensor Luminescence assay in HEK293T cells (monitors luciferase signal upon actiation of GPCR). They then swap one-pH sensing receptor for another (GPR68 pH sensing into GPR4) to evalluate drift of pH50 - only a construct with the entire extracellular signal region of GPR68 into GPR4 results in complete shift of pH50. So not a single site but a bunch of proton sensing sites is reponsible for receptor activation. (They also look at anti-FLAG-APC staining to evaluate receptor expression)

Figure 2/3/S2-S3 - Determine cryoEM structures of GPR4, 65, 68. GPR4, 65 are activated by Galphas so they have mini-Galphas to stabilize their receptors and for GPR68, they use both Galphas and Galpha/Gq. They compare the structures with Beta2-AR structure (Class A GPCR) 
Conserved GPCR motif:  P5.50I3.40F6.44, N7.49P7.50xxY7.53 (TM7), C6.47W6.48xP6.50” motif in TM6
These structures show many titratable residues in the TM regions of all proteins (His, Lys, Arg/Asp, Glu)


Figure 4 - Deep Mutational Scanning of GPR68 for high-throughput Seq-function insight. 

Prior work used a cAMP-DMS transcriptional readout for receptor activation - but suffered from low signal window and high basal activity. 
They devised a new readout with a FACS-seq approach. Activation of GalphaS -> cAMP production -> eGFP activation. To correct for GPCR basal activity resulting in low signal to noise, they employed two methods: 1. titrated receptor expression precisely 2. Fuse eGFP to dihydrofolate reductase degron stabilized by a small-molecule TMP (so with TMP, eGFP is produced upon stimulation).

4b/c/d - Control FACS experiments with B2AR - show eGFP expression with forkskolin (direct cAMP production) and none with DMSO/other inhibitors, GPR68 shows eGFP peak at pH 5.5 (active) and not at pH 6.5 (inactive, left shifted peak). %GFP+ cells is 0 at pH 6.5 and and 100% at pH 5.5 consistent with eGFP signal peaks. 

4E/F - They generated a gpr68 mutant library containing all possible single missense mutations, a single synonymous mutation, as well as 1–3 amino acid insertions and deletions (indels) at each position => 9464 pooled variants in stable HEK293T cells with each one containing a variant - performing screen at pH 5.5 (active) and pH 6.5 (inactive). 

At pH 6.5, mutations have little effect (consistent with inactivating condition)
Ar pH 5.5, mutations in TM regions are less tolerated, Cys mutations that are involved in S=S bonds are less tolerated, substitutions in conserved GPCR motif positions are mostly deleterious. 

Multi-phenotypic DMS: 

Figure 5 - To deconvolute expression and signaling, they are performed FACS with anit-FLAG antibody. 
Syn mutations have little effect on signaling, missense mut have distributed effects on signaling and expression. 
They devise an expression-adjusted functional score for each variant for pH dependent activation. Since syn mutation should have least effect on expression or function, they define the regression line of how expression changes signaling. GOF with missense mutations that have higher signaling at same expression and LOF with lower signaling at same expression are mapped as euclidean distance to regression line (Linear distance). 

They then separated postive, negative and average mutational scores per position and identity the usual GPCR motifs and residues contacting Galpha as those in the highest 5% GOF or lowest 5% LOF. Some also map to titrable extracellular residues. 

Figure 6: 

MD simulations of GPR68:





