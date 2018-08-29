# Distracted-Driver-Detection

Distracted driver detection trained on State Farm Dataset from Kaggle

## Model Information  
* MobileNet - mobilenet_v1_100_224
* Model learning_rate 0.0001
* Testing_percentage=20
* Validation_percentage=20
* Train_batch_size=32
* Validation_batch_size=-1
* Flip_left_right True
* Random_scale=30
* Random_brightness=30
* Eval_step_interval=100
* Training_steps=600 

## Accuracy
* Train accuracy = 81.2%
* Cross entropy = 1.504825
* Validation accuracy = 70.3% (N=2236)

## test.jpg inference
c1 0.23998111 -> True Label
c4 0.20052847
c3 0.20035508
c2 0.18340966
c0 0.17572576


 
