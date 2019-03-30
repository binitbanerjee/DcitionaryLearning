# DcitionaryLearning
This shows a comparison of the dictionary learning and PCA using custom code for PCA analysis a
nd sk learn for extracting the sparse matrix. 
The code also has a phase two where I have used the Hinge loss optimisation technique to evaluate the hidden vectors 
which is then used to recreate the transformed image. 

To compare the custom Hinge loss algorithm, I have also used SPAMS lasso to calculate the hidden vectors for the image 
transformation using the Dictionary obtained via the sklearn minibatchdictionary in the step above and calculated the l2 norm
of the recreated image patches to the original image patches.

Observation:
The recreation error using dictionary learning is comparable to using the PCA, 
where top 255 eigen vectors out of 256 are used to recreate.

Note:
The experiment is performed no 1000 random patches of only the R-channel of the image of size 16x16.

