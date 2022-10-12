# Imitation Learning for Skill Transfer in Human-Robot Teleoperation.

This research will develop a remote control system based on human hand input gestures to enable a faraway robot to replicate human motion with zero latency and high accuracy.
More specifically, to develop an imitation learning system to reproduce skills on robot manipulators with minimal inputs using the Learning by Demonstration (LbD) framework. Human-like input demonstrations are retrieved through a Kinect motion sensor. The experimental results confirm the effectiveness and efficiency of the proposed method when comparing the inferred trajectory to the ground truth.


# Contribution
1. Implement a Gaussian Mixture Model (GMM) to characterize the task trajectory and generate the underlying task trajectory.
2. Build an encoder-decoder system to encode the generated trajectory using minimal inputs.


Overall Systems Design:
![Design](./Img/0_design.jpg)

Input:
![Input](./Img/1_input.jpg)

Groud Truth:
![Ground Truth](./Img/2_ground_truth.jpg)

Gaussian Components:
![Gaussians](./Img/3_gaussians.jpg)

Inference:
![Inference](./Img/4_inferred.jpg)

Encoder:
![Encoder](./Img/5_encoder.jpg)

Decoder:
![Decoder](./Img/6_decoder.jpg)

Task Dictionary:
![Dictionary](./Img/7_dictionary.jpg)


