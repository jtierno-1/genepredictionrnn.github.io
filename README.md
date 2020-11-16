# Gene Sequence Prediction with Machine Learning
> Fall 2020 Research Project by: Haley Granger and Joe Tierno<br />
> Faculty Advisor: Dr. Muhammad Aledhari

### Introduction
Pseudogene and other gene sequence predictions using a RNN and other architectures. Using machine learning models ExPecto and DanQ we have attempted at finding pseudogenes based on the small mutations in noncoding regions of the human genome. Both ExPecto and DanQ utilize models which predict the function of DNA based on sequence data and can infer changes to gene expression based on comparing the input sequence to the training model.
<br />

### Research Question
Pseudogenes have long been thought to lack a function, but have recently been found to play an important role in regulation and prevention of disease. However, finding these have been difficult as they are typically considered noncoding and most previous genetic analysis has focused on genes. With 98% of the human genome being noncoding, a much larger majority of the genome needs to be explored for possible mutations which could impact the regulation of genes.

### Our Implementation
We have three different implementations we explored for predicting pseudogenes with a RNN:<br />
-ExPecto Architecture (https://github.com/FunctionLab/ExPecto)<br />
-DanQ Architecture (https://github.com/uci-cbcl/DanQ)<br />
-RNN we created<br />

We used ExPecto and DanQ models which were trained with datasets from DeepSEA(http://deepsea.princeton.edu/job/analysis/create/). ExPecto uses the data and creates a model which can identify common motifs found in the sequence and predict possible changes to chromatin based on the mutations. DanQ is able to predict possible function based on sequence data. Together it is possible to determine a possible function and identify if the mutations in the region could affect genetic packaging.

### Current Progress
Currently we have both example models working to predict gene effects of test sequences based on example DeepSEA datasets. We plan on expanding this to analyze additional sequence data of known pseudogenes and attempt to obtain sequences that may be implicated in disease based on published data.

### Research Implications
This research could identify new targets for big pharma. With many protein/genes being considered undruggable, these new targets could guide drug discovery projects.


