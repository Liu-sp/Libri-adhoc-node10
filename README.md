# **Libri-adhoc-nodes10**
Libri-adhoc-nodes10 is a synchronized speech corpus, which collects the replayed Librispeech data from loudspeakers by ad-hoc microphone arrays of 10 synchronized distributed nodes in real world environment.
## **Description of the dataset**
The Libri-adhoc-nodes10 dataset is composed of the speech signals collected by the microphone array and use the "test-clean" part of the Librispeech as the sound source.  The "test-clean" part of the Librispeech contains about 5.4 hours of US English speech from 20 male speakers and 20 female speakers. This dataset is recorded in two rooms, an office room and a conference room. There are a sound source and an ad-hoc microphone array with 10 nodes in the room, each node contains a ULA(uniform linear array) with 4 microphones and the intermicrophone distance was set to 8cm. The ad-hoc nodes and the loudspeaker have the same height of 1.3m. Each room contains two configurations, each configuration hase two sub-configurations. And each sub-configurations contains ten different positions of the loudspeakers. Eventually, Libri-adhoc-nodes10 contains 432 hours data in total. 

The introduction of two rooms can be seen below.

### **The office room**
The office room is an irregular room, the height of the room is 4.2 m. The size of the room can be seen in the figure below. Because the room size is large, and because the floor is laid with smooth tiles, the room is highly reverberant with the T60 around 1.39s. Because the room is far from noisy environments, the recorded speech has little additive noise.

<img src="https://github.com/Liu-sp/Libri-adhoc-nodes10/blob/main/images/room1_1.png" width="450"><img src="https://github.com/Liu-sp/Libri-adhoc-nodes10/blob/main/images/room1_2.png" width="450">

### **The conference room**

<img src="https://github.com/Liu-sp/Libri-adhoc-nodes10/blob/main/images/room2_1.png" width="450"><img src="https://github.com/Liu-sp/Libri-adhoc-nodes10/blob/main/images/room2_2.png" width="450">


The difference between the sub-configurations are that the directions of the ULAs at the ad-hoc nodes are different. For each sub-configuration, each position of the loudspeaker replays only one speaker.  

## **Download Link**
The test data of Libri-adhoc-nodes10 is available at now.
