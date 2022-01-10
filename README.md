# Learning Common and Label-Specific Features for Multi-Label classification with correlation information
In multi-label classification, many existing works only pay attention to the label-specific features and label correlation while they ignore the common features and instance correlation, which are also essential for building a competitive classifier. Besides, existing works usually depend on the assumption that they tend to have the similar label-specific features if two labels are correlated. However, this assumption cannot always hold in some cases. Therefore, in this paper, we propose a new approach of learning common and label-specific features for multi-label classification using the correlation information from labels and instances. First, we introduce l2,1-norm and l1-norm regularizers to learn common and label-specific features simultaneously. Second, we use a regularizer to constrain label correlations on label outputs instead of coefficient matrix. Finally, instance correlations are also considered through the k-nearest neighbor mechanism. Comprehensive experiments manifest the superiority of our proposed approach against other well-established multi-label learning algorithms for label-specific features.


This work has been published in: 
Junlong Li, Peipei Li*, Xuegang Hu, and Kui Yu. Learning common and label-specific features for multi-Label classification with correlation information. Pattern Recognition, 21: 108259, 2022.


Please see details from the following github website:

https://github.com/SaltedPerson/CLML
