# Paper: Comparison of Controlled Undersampling Methods for Machine Learning
# Experiment Results

 Performance metrics are presented in the two tables. Results for small datasets are shown in Table *Model Evaluation Results on Small Datasets*, whereas the results for the larger datasets can be found in Table *Model Evaluation Results on Large Datasets*.  These tables have the following structure. *F1* scores with standard deviation for each dataset are shown based on the reduction ratio for the tested model and the sampling method. The reduction ratio indicates the amount of data that is removed from the original dataset. The ratio of *0.0* indicates no reduction, while the ratio of *0.9* means that *90%* of the data was removed. The final column displays the mean *F1* score across all reduction ratios, excluding *0.0*. The bold values highlight the optimal method for the given dataset and model. 

## Table with results for small datasets

![Averaged Boxplot](small.png)

## Table with results for large datasets
![Averaged Times](large.png)

## Visualization of all datasets (Reduction phase line graphs and Deviation boxplots)
### Banana dataset
![Averaged Banana](averaged_banana.png)
![Averaged Banana Boxplot 0.5](averaged_banana_boxplot_0.5.png)
### Buba dataset
![Averaged Bupa](averaged_bupa.png)
![Averaged Bupa Boxplot 0.5](averaged_bupa_boxplot_0.5.png)
### KDD CUP dataset
![Averaged KDD Cup](averaged_kddcup.png)
![Averaged KDD Cup Boxplot 0.5](averaged_kddcup_boxplot_0.5.png)
### Magic dataset
![Averaged Magic](averaged_magic.png)
![Averaged Magic Boxplot 0.5](averaged_magic_boxplot_0.5.png)
### Monk-2 dataset
![Averaged Monk-2](averaged_monk-2.png)
![Averaged Monk-2 Boxplot 0.5](averaged_monk-2_boxplot_0.5.png)
### Phoneme dataset
![Averaged Phoneme](averaged_phoneme.png)
![Averaged Phoneme Boxplot 0.5](averaged_phoneme_boxplot_0.5.png)
### Pima dataset
![Averaged Pima](averaged_pima.png)
![Averaged Pima Boxplot 0.5](averaged_pima_boxplot_0.5.png)
### Ring dataset
![Averaged Ring](averaged_ring.png)
![Averaged Ring Boxplot 0.5](averaged_ring_boxplot_0.5.png)

## Overall results (Overall F1 score and time consumption)

![Averaged Boxplot](averaged_boxplot.png)
![Averaged Times](averaged_times.png)


