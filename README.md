# Demographs from FIJI linescans
A collaborator recently asked me for assitance on generating demographs from fluorescent images of bacteria. Here, I detail a basic pipeline for how to generate linescans manually in FIJI then to apply a basic python script, written in Jupyter Notebook, to make a demograph. For these demographs, they are normalized by z-score to emphasize where signal is enriched along the cell body.

The code is well-annotated as to its function and application, and I have a PDF protocol for how to measure the linescans. Please refer to both of these for instructions. The base code for constructing demographs was used in my main publication, so please cite the paper below if you use my code. 

McCausland JW, Kloos ZA, Irnov I, Sonnert ND, Zhou J, Putnick R, Mueller EA, Steere AC, Grimes CL, Jacobs-Wagner C. 2025. Bacterial and host enzymes modulate the pro-inflammatory response elicited by the peptidoglycan of Lyme disease agent *Borrelia burgdorferi*. PLOS Pathogens 21(7): e1013324. [https://doi.org/10.1371/journal.ppat.1013324](https://doi.org/10.1371/journal.ppat.1013324)
