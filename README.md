# Autonomous-Car-using-Deep-Learning-and-Computer-Vision
The main purpose of this project is to become familiar with AI techniques, specifically Convolutional Neural Network (CNN), and to apply them to real world problems, i.e., autonomous vehicle.

# Phase 1: Assembly
In this phase, we assembled the Autonomous vechicle. Below you will see a link directing you to our images of the process.
https://github.com/kaitlynb-s/Autonomous-Car-using-Deep-Learning-and-Computer-Vision/issues/1#issue-1038827314

# Phase 2: Setting-Up Raspberry Pi
During this phase, we experienced a few issues with our micro-sd card. We attempted multiple times to connect using our original one but ultimately had to receive a different sd card from our professor. With the second one, we were able to move forward quickly. During this set, we followed the given powerpoint without issues. This setup allowed us to code our vehicle so that we were able to move forward adn learn how to make it move.

This image shows the process we took to complete a cloud connection.
![QQ═╝╞¼20211207094936](https://user-images.githubusercontent.com/90004321/145451318-105d1acb-02da-46a5-9d89-fed2be7d9da9.png)

This image shows how the connection will look once it is completed and how we would be able to access the vehicle itself.
![QQ═╝╞¼20211207121816](https://user-images.githubusercontent.com/90004321/145451347-e7d4f2d5-1ae5-4f9d-bab4-026948f4617c.png)

This shows the window that opens that allows for us to type the code for the vehicle.
![QQ═╝╞¼20211207121848](https://user-images.githubusercontent.com/90004321/145451364-f22386d4-9b7b-4626-a4f5-8e67d5e15d4f.png)

# Phase 3: Download Programs and Configuration
In order to focus on main goal of the project, i.e., applying a deep learning algorithms into an autonomous vehicle, an instructor provides a package of programs and libraries for an autonomous vehicle. DM-Car-New has the following functionalities:
-   Lane detection both straight and curve lanes
-   Controlling back wheel servos
-   Controlling front steering wheel servo
-   Camera module (OpenCV)
-   Creating Video Clip
-   Sequence of Image Files for dataset
-   Deep Learning Models for Autonomous Car
    -   Stop Not-Stop Model: CNN LeNet model
    -   Lane Follower Model: Nvidia CNN model
    -   Lane Follower Model: Nvidia CNN model
    -   Stop Not-Stop Image Classification Model: "Stop No-Stop model" by Retrain a classification model for Edge TPU using post-training quantization (with TF2)
    -   Traffic Sign Object Detection Model: "Traffic Sign Model" by Retrain EfficientDet for the Edge TPU with TensorFlow Lite Model Maker (with TF2)

Below is an image that shows how the process of configuration begins and while we were unable to complete it due to our issues with our car, we were able to begin it.
![QQ═╝╞¼20211207122142](https://user-images.githubusercontent.com/90004321/145459333-3003be4e-de5e-4d6e-9287-456a03a259ed.png)


## Phase 4: Lane Follower for Autonomous Car
In this phase, you are going to make picar follow lanes, a.k.a lane follower. There are 2 methods as below:
-   Method 1: Lane follower using OpenCV
-   Method 2: Lane follower using Deep Learning model (i.e., NVIDIA CNN model)

In this Phase, my partner and I were unable to complete the configuration 


## Phase 5: Creating Models for Traffic Signs
In this phase, you are going to create Deep Learning model to classify or detect traffic signs (starting from "Stop Sign", then extend to other traffic signs including "Speed", "Traffic Signal", and others.
To create Deep Learning model, there are 4 main methods as below:
1.  On-device
2.  Google Colab
3.  Cloud Service (GCP, AWS or Azure)
4.  Docker

While we could not make the vehicle move, we were able to complete all the steps to ensure that when it did work, the car would be able to stay between the two black lines and detect different signs.
![model3](https://user-images.githubusercontent.com/90004321/145461128-f64ec8b3-1ef7-4f5b-a67a-e947b5ac9606.png)
![QQ═╝╞¼20211207124252](https://user-images.githubusercontent.com/90004321/145461142-d2ff1d50-2274-4cef-afa6-57e12b8a6432.png)
![QQ═╝╞¼20211207125348](https://user-images.githubusercontent.com/90004321/145461156-ec8f050b-009c-48eb-adfa-eafd6e8fb9ad.png)
![QQ═╝╞¼20211207125523](https://user-images.githubusercontent.com/90004321/145461172-8d83b126-23a1-4d53-94a1-1418c7a16c07.png)
