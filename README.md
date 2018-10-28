This is the code of our NIPS 2018 Paper: "Kalman Normalization" and its extension "Populatin Normalization".

# Kalman Normalization

Kalman Normalization (KN) is a normalization technique that is able to achieve excellent performance, under the context of both large-batch training and small-batch training.

As its counterparts, Group Normalization (GN) fails to achieve excellent performance in large-batch training, and Batch Normalization (BN) has poor performance in small-batch traning. 

We have the the following observations:

$KN_{large batch}$ = KN (small batch) > 

## Update

- 2018/10/16: The code of image classification and a pretrained model on ImageNet are released.
