# FGSM-Attack
Task: Adversarial Attack
Dataset: CIFAR-10
● Download data https://drive.google.com/file/d/1HQRkshrkTfXufzDeeGov_y6vii4Yd52N/view
● 10 classes (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck)
● 20 images for each class
● Each image is in 32*32 RGB
Methods Used : Iterative-FGSM , esemble attack ( IFGSM, FGSM)
Evaluation:
● Parameter ε is fixed to 8
● Distance measurement: L-inf. norm
● The final score is based on the model accuracy after attack.
