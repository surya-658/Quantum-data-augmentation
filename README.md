# Quantum-data-augmentation
This is a quantum data augmentation model designed to enhance feature diversity for machine learning tasks.

In this model, random quantum gates are applied to the data to generate extended representations. This transformation not only enriches the data but also produces new, informative features that are crucial for training machine learning models.

The data used is the MNIST digits data set which contains the images of digits 0 to 9 

we have trained a SVM model with the orginal data and the augmented data for comaparsion 

and we can see that the SVM trained with original data gave a accuracy of 60% whereas SVM trained usign augmented data gave a accuracy of 70% thus clrearly indicating that the augmentation  indeed improved the accuracy of the ML model
