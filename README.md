
In this , we choose most dominant K colors from the Image and Reconstructing the same image with those K colors , and we get a beautiful abstracted picture



1. first we upload the image we want to segment , sample images are given in repositry

2. from sklearn , we import in built KMeans 

3. by the k means , we find the position of k points (k = no. of colour segments we want to make of the picture)

4. we iterate over mean points and make a subplot of 1 row and k columns , each column depict the mean clustering dominant colour 

5. push each colour in the array
