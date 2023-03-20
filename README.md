### diannQC R Package
Universal software DIA-NN is used to process data-independent acquisition (DIA) proteomics data using neural networks, as discussed in the paper by [Demichev et. al.](https://www.nature.com/articles/s41592-019-0638-x) and is available to download from [Github](https://github.com/vdemichev/DiaNN). In order to determine the quality of individual samples, ```R``` package ```diannQC``` is used to generate various plots to assess the data quality, as well as determine which samples are outliers based on various metrics.

**DIA-NN: neural networks and interference correction enable deep proteome coverage in high throughput**  
Vadim Demichev, Christoph B. Messner, Spyros I. Vernardis, Kathryn S. Lilley, Markus Ralser  
https://www.nature.com/articles/s41592-019-0638-x

**Installation in R**:
```
install.packages("devtools")
library(devtools)
install_github("https://github.com/oshomroni/diannQC")
library(diannQC)
```

**Examples**:   
```
library(diannQC)
```
Load statistics report to R
```
TODO
```
## Plots
Use PCA plots to determine whether any samples appears as outliers
```
TODO
```
Create z-score plots to determine whether samples are outliers for any specific metrics
```
TODO
```
## Outlier detection
Detect outlier samples using mahalanobis distances
```
TODO
```
Detect outlier samples based on important metrics
```
TODO
```
