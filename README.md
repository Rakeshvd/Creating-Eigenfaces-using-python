# Creating-Eigenfaces-using-python
Representation of a huge set of face dataset by eigenfaces. PCA package in Opencv is used.

Aim of the project is to trasform face images into a small set of charecteristics feature images called "Eigenfaces" , which arer nothing but principal components of 
face images used in training set.

Reference : https://sites.cs.ucsb.edu/~mturk/Papers/mturk-CVPR91.pdf

Mathematically it is finding the principal components of distribution of faces or eigenvectors of covariance matrix of a set of face images. Thes eigen vectors can be thought of as set of features which together charecterize vaiation between face images.

So possible eigenfaces = number of faces images in training set. But we wish to represent this whole dataset using only "best" eigenfaces i.e those that have largest variance within set of face images.

Dataset used: http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html

I am using 400 images and representing them using 10 eigenfaces.

Domo video : demo_eigenface.mp4

Weight--    What it captures/represents:

Weight 0--    Backgraound

Weight 1--    Hairstyle

Weight 2--    Top to bottom Lighting condition (on background and hairstyle)

Weight 3--   Short hairstyle

Weight 4--    Face skintone

Weight 5--  Sideways lighting conditions

Weight 6--   Masculine and Faminine features







