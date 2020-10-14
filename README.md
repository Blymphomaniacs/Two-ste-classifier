# Two-step genetic classification
We developed a simplified genetic classification based on those proposed by Schmitz-Wright and Lacy and their research teams. We used the alterations of specific genes to classify the samples as N1<sup>2-S</sup>, BN22-S, EZB2-S, MCD2-S, or ST22-S. The A53 LymphGen subtype was not included due to the lack of copy number variation data in our series and most published series. We developed a two-step classification method. The genes from the Schmitz-Wright12,13 and Lacy15 studies were selected by calculating their power to classify determined by the Fisher's exact test, as featured in these studies (Suppl. Table S9). Several tests were then carried out to select the best combination of genes, taking into account the sensitivity and specificity in the PdH and HMRN cohorts according to the LymphGen and Lacy classification (AIC cluster). In the first step, at least one of the top genes should be mutated: NOTCH1, for N12-S (NOTCH1 mutated samples were classified as N12-S, regardless the presence of other alterations); MYD88, CD79B, and PIM1 for MCD2-S; BCL6 translocation, NOTCH2, BCL10, and TNFAIP3 mutations for BN22-S; BCL2, EZH2, and CREBBP for EZB2-S; and SGK1, TET2, and SOCS1 for ST22-S. Samples with the same score for two or more subtypes, or samples with no mutations, were classified in the second step, in which we added the following genes for each subtype: PRMD1, BTG1, PIM2, and CD58 for MCD2-S; UBE2A, CD70, CCND3, and DTX1 for BN22-S; TNFRSF14, KMT2D, IRF8, and EP300 for EZB2-S, and STAT3 for ST22-S. In this second step, at least two genes from any of the genes that define each subtype should be mutated to assign the sample to the corresponding subtype (Fig. S5 and Suppl. Table S9).

## Usage
This script is made for running in R with a mutational table as the example.txt file.
