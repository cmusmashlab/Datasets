
=============================== FitByte Dataset ReadMe ======================================

All data should be accessible from the following link:
https://drive.google.com/drive/folders/11FoVzERk52HetB0C9FEw8n4Lxr8xoBRd?usp=sharing

For any questions please email:
bedri@cmu.edu
Or
Akareem.bedri@gmail.com
===============================================================================================
* The dataset file contains 5 directories one for each activity performed in the first study.
* Inside each directory there are 10 data files labeled with the ID of the participant.
* You will notice the listed IDs are different in each activity because not all participants performed the 5 activities -- In total there are 18 participant. 
* You can use the ID information to perform user dependent or user independent testing. 

* The date in each file is organized as follow:
	-Each line represents a data sample acquired at 50 Hz with annotations (Notice: The Accelerometer data is sampled at 4 Khz so in each line there are 80  Accelerometer samples.

	-The labels for the data sample line are in the following order:

"Time stamp", "cameraOn","gx1","gy1","gz1","gx2","gy2","gz2","gx3","gy3","gz3","gx4","gy4","gz4","gx5","gy5","gz5","proximity sensor","80 samples Acceleromter"," label silent","label eating", "label drinking" "label talking", "label moving".

	-Code:
		"g" indicates gyroscope value
		"x,y,z" indicate the axis 
		The number indicates which gyroscope it is:
			g1: Left Ear Upper
			g2: Left Ear Lower
			g3: Nose gyroscope
			g4: Right Ear Upper
			g5: Right Ear Lower


* The last 4 columns contain the annotation for this sample. The value 1 indicates the presence of this activity (silent, eating, drinking, talking, walking ) and 0 indicates the absence of it.

