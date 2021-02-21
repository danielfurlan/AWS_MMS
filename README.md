# AWS_MMS
Adaptation of AWS MMS for local test


This is a simple yet efficient way to use the AWS Multi-Model-Server script for local tests!

It's for you if it's not time yet to move to the cloud and pay for hosting your models on third parties buckets or just because you're still in an early stage of your project,
where local environments can work perfect to make first tries!!

In this example, the idea is to visually check how my models are doing inferences to detect cat's limbs.
For that purpose, the very first step was to create a CUSTOM dataset in order to detectron2 recognize the limbs. That was need because cat's limbs are not part of the registered datasets.

I'm testing 2 mask_rcnn_R_50_DC5_3x model with different hyper parameters.

As you can see on the video, the model named SAN-17 had a better detection of the lilmbs!

![alt text](https://github.com/danielfurlan/AWS_MMS/blob/master/AWSMMS.gif)

Just make a cURL request and check the results right away.

The predicted images:


![alt text](https://github.com/danielfurlan/AWS_MMS/blob/master/predicted_SAN-16_cat_1.jpg) | ![alt text](https://github.com/danielfurlan/AWS_MMS/blob/master/predicted_SAN-17_cat_1.jpg)
