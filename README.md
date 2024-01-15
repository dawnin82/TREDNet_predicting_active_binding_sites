# TREDNet_predicting_active_binding_sites
Deep learning pipeline to predict active binding sites of transcription factors in enhancer regions.
General steps of processing are as follows:
1. Define active enhancers using open chromatin regions, active mark H3K27ac and enhancer mark H3K4me1. Using TREDNet (link) or other models to calculate the probability of a selected DNA segment being a tissue-specific enhancer, for example, the Liver cell.
