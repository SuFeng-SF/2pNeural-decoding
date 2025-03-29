# 2pNeural-decoding
Visual information is encoded by the sparsely activated neurons in the primary visual cortex (V1). However, it is unclear whether the sparsely activated neurons are variable or consistent across different images, and how to decode the visual information based on few sample data. To address this, we analyzed the neural response to visual stimuli in V1 from two photo calcium imaging, and decoded the visual stimuli in mice and macaques. We found a sparse and variable activation of V1 neurons, but similar activation patterns of neuronal populations across trials, suggesting that neural similarity reliably encodes sensory information. Furthermore, we developed a novel few-shot decoding method based on the neural population vector cosine similarity, which classified the visual stimuli better than the traditional methods. These results provide insight into neural similarity coding in the V1, and offer a promising decoder for few-shot decoding of visual information, which promotes the development of brain-machine interfaces. 

## Quick run
Run *decode_Bayesian.mlx* for Naive Bayesian decoding.    
Run *decode_CosineSimilarity.mlx* for cosine similarity decoding.    

## File organization
*SF_active_all_0.mat* : all 2p data    
*csdata_01_00.mat* : experimental settings for drafting grid with direction of 0 degree.    
*csdata_01_45.mat* : experimental settings for drafting grid with direction of 0 degree.    
...
