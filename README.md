# ML_Project_17807
Kernel Method: Fisher’s Discriminant Analysis, Principal Component Analysis and K-means

In Machine Learning, Kernel Trick is used whichimplicitly  maps  the  feature  space  of  data  to  ahigher dimension enabling us to classify a non-linear dataset using a linear classifier. The Kernelfunction transforms the linearly inseparable datato a linearly separable one by projecting it onto ahigher dimensional space.The Kernel Trick givesus the inner product of the data in the higher di-mensional feature space without actually project-ing the data. It is efficient and less expensive thanexplicit computation of coordinates. We can applythe Kernel Trick to unsupervised algorithms suchas Principal Component Analysis and K-meanswhen the data is non-linear.

In this project the kernalized versions of PCA, FDA and K-means is implemented. Gaussian kernel, polynomial kernel, laplacian kernel, sigmoid kernel, linear kernels are used. For comparison, data is plotted for each kernel and for each algorithm used.

