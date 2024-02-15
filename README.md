## Joint prototype and coefficient prediction for 3d instance segmentation (in press)

**The code will be released soon. Estimated time of arrival: 15 March 2024**

**Authors:** <a href="https://www.linkedin.com/in/remcoroyen/" target="_blank">Remco Royen</a>, <a href="http://www.etrovub.be/LeonDenis" target="_blank">Leon Denis</a>, and <a href="http://www.etrovub.be/AdrianMunteanu" target="_blank">Adrian Munteanu</a> - Vrije Universiteit Brussel (VUB). The first author has been funded by a FWO-SB scholarship.

### Introduction

This repository is the code release of the work from our [electronic letter] (link not yet available), published in ??? 2024. We propose a 3D instance segmentation method which simultaneously learns coefficients and prototypes.

3D instance segmentation is crucial for applications demanding comprehensive 3D scene understanding. In this paper, we introduce a novel method that simultaneously learns coefficients and prototypes. Employing an overcomplete sampling strategy, our method produces an overcomplete set of instance predictions, from which the optimal ones are selected through a Non-Maximum Suppression (NMS) algorithm during inference. The obtained prototypes are visualizable and interpretable. Our method demonstrates superior performance on S3DIS-blocks, consistently outperforming existing methods in mRec and mPrec. Moreover, it operates 32.9\% faster than the state-of-the-art. Notably, with only 0.8\% of the total inference time, our method exhibits an over 20-fold reduction in the variance of inference time compared to existing methods. These attributes render our method well-suited for practical applications requiring both rapid inference and high reliability.

### Citation
If you find our work useful in your research, please consider citing:

	Bibtex not yet available
	
### License
Our code is released under MIT License (see LICENSE file for details).

## Contact
If you have any questions or suggestions regarding this repo or the paper, feel free to contact me (remco.royen@vub.be).
