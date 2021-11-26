# Machine Perception -  ETH Zurich 2021
Final project report for the Machine Perception course held at ETH Zurich in spring 2021. The project involved improving the performance of state-of-the-art neural models for optical flow estimation on a dataset containing human figures movement.

### Abstract

The task of optical flow estimation consists in reliably identify-
ing the pixel-wise motion of objects between two consecutive im-
ages or frames of a video. Recent approaches to this task employ
deep neural architectures extensively trained on multiple synthetic
datasets. One of such datasets is the Multi-Human Optical Flow
(MHOF) dataset. This report will detail how we have adapted,
modified, and fine-tuned the state-of-the-art neural architecture,
Recurrent All-Pairs Field Transforms (RAFT) to a subset of the
MHOF dataset. Our main contributions are the addition of a form
of teacher-forcing to the initialization of the recurrent submodule
of the architecture, a more extensive use of channel dropout on con-
volutional layers to avoid overfitting on our small provided dataset
and the generation of new synthetic data. The final submission,
which combines all these three contributions, achieves an EPE of
0.345 as the public test score of ETH’s Machine Perception Project
6 competition.
