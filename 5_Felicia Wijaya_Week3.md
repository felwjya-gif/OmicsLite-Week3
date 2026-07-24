## Molecular Docking Analysis of Top 10 Hubs and Naringenin

![Table1](/Table1.png)
Table 1. Structural information of naringenin and the selected hub proteins used for molecular docking analysis.

Molecular docking is a computational approach often used in drug discovery to help in predicting the structural details of proteins and protein-ligand interaction (Meng et al. 2011).To validate the interactions predicted by network pharmacology, molecular docking was performed between naringenin and the 10 hub proteins identified from the PPI network. Protein structures were obtained from Protein Data Bank (PDB), selecting the X-Ray crystallographic method with a resolution of ≤2.00 Å if available, or the highest-quality structure with the lowest available resolution was chosen (Table 1). The ligand-binding pockets of each protein target were predicted using PrankWeb. Prior to docking, protein structures were prepared by removing heteroatoms that might disturb the binding during docking simulation, whereas essential cofactors and metal ions important in structural stability and catalytic activity were retained. Docking simulations were conducted using SwissDock with the AutoDock Vina scoring function.

![Figure1](/PrankwebCompile.png)
Figure 1. Ligand-binding pocket prediction using PrankWeb of SRC (A), AKT1 (B), PTGS2 (C), MMP9 (D), ESR1 (E), BCL2 (F), PIK3CA (G), CYP19A1 (H), MMP2 (I), and APP (J).

![Figure2](/DockingCompile.png)
Figure 2. Docking Visualization using SwissDock of SRC (A), AKT1 (B), PTGS2 (C), MMP9 (D), ESR1 (E), BCL2 (F), PIK3CA (G), CYP19A1 (H), MMP2 (I), and APP (J).

![Figure3](/AffinityCompile.png)
Figure 3. Binding affinity calculation using SwissDock of SRC (A), AKT1 (B), PTGS2 (C), MMP9 (D), ESR1 (E), BCL2 (F), PIK3CA (G), CYP19A1 (H), MMP2 (I), and APP (J).

The predicted binding pockets (Figure 1), were generally located within the cavities of the proteins. These pockets resemble the ligand-binding regions and served as the search space for molecular docking. The visualization of the docking results (Figure 2) displays that naringenin successfully binds the predicted active sites in each protein target. This suggests that the shape and size of the binding sites are compatible with naringenin. Furthermore, the calculated affinity (Figure 3) shows a notable variation of affinities among the protein targets. The strongest interaction was observed with MMP9, exhibiting the lowest binding energy of -9.239 kcal/mol, meaning the strongest binding. This was followed by AKT1 (-8.773 kcal/mol), PIK3CA (-8.383 kcal/mol), PTGS2 (-8.081 kcal/mol), SRC (-8.029 kcal/mol) and CYP19A1 (-7.657 kcal/mol). The binding affinities below -7.0 kcal/mol suggest relatively strong and stable protein-ligand interactions (Venkatesan & Muniyan 2025). Therefore, this suggests that naringenin is less likely to bind efficiently to ESR1, BCL2, MMP2, and APP, indicating that the interaction may not be sufficient to significantly alter protein function.

The docking results support the multi-target characteristics predicted by the network pharmacology analysis. Particularly, the strong binding affinities with MMP9, AKT1, PIK3CA, PTGS2, SRC, and CYP19A1. These proteins are known to regulate key processes involved in cervical cancer progression. MMP9 contributes to remodeling of the ectocervix (Ghosh et al. 2014). AKT1 protein is involved in cell proliferation, differentiation and apoptosis (Qiu et al. 2025). PIK3CA mutations in cervical cancer are associated with higher tumor mutation burden (Voutsadakis 2021). PTGS2 protein might be affecting macrophage polarization and mutation effects (Zou et al. 2022). SRC protein is one of the most studied oncoproteins, known to be the one that can orchestrate the metabolism pathway to support specific tumour cell processes (Pelaz & Tabernero 2022). CYP19A1 is upregulated in cervical cancer to promote local estrogen production, driving tumor cell proliferation and development (Setiawan et al. 2009). In conclusion, this study provides structural evidence that suggests naringenin may exert its anticancer activity through simultaneous modulation of the protein targets that hold a key role in cervical cancer progression.

**Reference**

Ghosh A, Moirangthem A, Dalui R, Ghosh T, Bandyopadhyay A, Dasgupta A, Banerjee U, Jana N, Basu A. 2014. Expression of Matrix Metalloproteinase-2 and 9 in Cervical Intraepithelial Neoplasia and Cervical Carcinoma Among Different Age Groups of Premenopausal and Postmenopausal Women. Journal of Cancer Research and Clinical Oncology, 140(9): 1585-1593. doi: 10.1007/s00432-014-1695-2.

Meng XY, Zhang HX, Mezei M & Cui M. 2012. Molecular Docking: A Powerful Approach for Structure-based Drug Discovery. Current Computer-aided Drug Design, 7(2): 146-157. doi: 10.2174/157340911795677602.

Pelaz SG & Tabernero A. 2022. Src: Coordinating Metabolism in Cancer. Oncogene, 41: 4917-4928. doi: 10.1038/s41388-022-02487-4.

Qiu J, Xu J, Zhang J, He H & Lin J. 2025. Exploring the Mechanism by which BXSD Decoction Treats Cervical Cancer Through the Combination of Network Pharmacology and Molecular Docking Analysis: Molecular Mechanism of AKT1 and CASP3 Protein.  International Journal of Biological Macromolecules, 317(2). doi: 10.1016/j.ijbiomac.2025.144818.

Setiawan VW, Doherty JA, Shu XO, Akbari MR, Chen C, Vivo ID, DeMichele A, Garcia-Closas M, Goodman MT, Haiman CA, Hankinson SE, Henderson BE, et al. 2009. Two Esterogen-related Variants in CYP19A1 and Endometrial Cancer Risk: A Pooled Analysis in the Epidemiology aof Endometrial Cancer Consortium. Cancer Epidemiology, Biomarkers & Prevention, 18(1): 242-247. doi: 10.1158/1055-9965.EPI-0800689.

Venkatesan U & Muniyan R. 2025. Therapeutic Potential of Acalypha indica L. Leaf Fractions Against Foodborne Pathogens: An In Vitro and In Silico Study. Scientific Reports, 16(2423). doi: 10.1038/s41598-025-32216-2.

Voutsadakis IA. 2021. PI3KCA Mutations in Uterine Cervix Carcinoma. Journal of Clinical Medicine, 10(2): 220. doi: 10.3390/jcm10020220.

Zou C, Xu F, Shen J & Xu S. 2022. Identification of a Ferroptosis-related Prognostic Gene PTGS2 Based on Risk Modeling and Immune Microenvironment of Early-Stage Cervical Cancer. Journal of Oncology, 3997562. doi: 10.1155/2022/3997562.
