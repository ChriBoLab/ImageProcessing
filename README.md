# ImageProcessing
Aplying filters to images and finding similarities between them.


## Introduction

Σέ αυτήν την εργαστηριακή άσκηση θα εξασκηθούμε στην ανάγνωσή και επεξεργασία εικόνων. Συγκεκριμένα, θα μάθουμε να διαβάζουμε εικόνες και να εφαρμόζουμε φίλτρα προσθήκης θορύβου και φίλτρα εξομάλυνσης. Τέλος, θα αξιολογήσουμε την ομοιότητα μεταξύ των αριθμών 3, 5, 8, 9 στο πεδίο του χώρου και του χρόνου. 


Αποφάσισα να υλοποιήσω 4 φίλτρα ταξινομητών τα οποία είναι τα παρακάτω:

    1. Averaging-cv2.blur() 
    2. Gaussian Filtering-cv2.GaussianBlur() 
    3. Median Filtering –cv2.medianBlur()
    4. Bilateral Filtering -cv2.bilateralFilter()
 
    
Θα μετραμε την ομοιότητα της νέας εικόνας με την πρωτότυπη, χρησιμοποιώντας 3 διαφορετικές μετρικές απόδοσης:


    1. Structural Similarity Index 
    2. Mean Squared Error 
    3. Peak signal to noise ratio 


## Installation

### Environment 

I use [Anaconda](https://www.anaconda.com/products/individual) because it comes with many Python
packages already installed and it is easy to work with. After installing Anaconda,
you should create a [conda environment](http://conda.pydata.org/docs/using/envs.html)
so you do not destroy your main installation in case you make a mistake somewhere:

       conda create --name ip python=3.7

Now you can switch to the new environment by running the following:

      source activate ip
      jupyter notebook
