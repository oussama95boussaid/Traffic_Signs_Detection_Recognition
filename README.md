# Traffic_Signs_Detection_Recognition

1. About this file

the German Traffic Sign Detection Benchmark (GTSDB) training dataset. It is provided for a benchmark 
at the IEEE International Joint Conference for Neural Networks (IJCNN) 2013. Please visit
 http://benchmark.ini.rub.de 
for further details. 


2. Content of the download package

Along with this file you should have received a zip-file containing ...

a) 600 image files with natural traffic scenes 00000.ppm - 00599.ppm
b) a text file gt.txt containing the ground truth for all traffic signs in the images
c) a text file ex.txt containing an example submission file for the upcoming competition calculated on this training dataset (true positives = 359, false positives = 595, false negatives = 37, Precision: 0.38, Recall: 0.91)
d) image sections with single traffic signs in the respective subdirectories named after the IDs (see below)


3. Explanation of ground truth text file

for each traffic sign in the dataset. The first field refers to the image file the traffic sign is located in. Field 2 to 5 describe
the region of interest (ROI) in that image. Finally, the ClassID is an integer number representing the kind of traffic sign. 
The mapping is as follows:

0 = speed limit 20 (prohibitory)

1 = speed limit 30 (prohibitory)

2 = speed limit 50 (prohibitory)

3 = speed limit 60 (prohibitory)

4 = speed limit 70 (prohibitory)

5 = speed limit 80 (prohibitory)

6 = restriction ends 80 (other)

7 = speed limit 100 (prohibitory)

8 = speed limit 120 (prohibitory)

9 = no overtaking (prohibitory)

10 = no overtaking (trucks) (prohibitory)

11 = priority at next intersection (danger)

12 = priority road (other)

13 = give way (other)

14 = stop (other)

15 = no traffic both ways (prohibitory)

16 = no trucks (prohibitory)

17 = no entry (other)

18 = danger (danger)

19 = bend left (danger)


20 = bend right (danger)

21 = bend (danger)

22 = uneven road (danger)


23 = slippery road (danger)



24 = road narrows (danger)

25 = construction (danger)

26 = traffic signal (danger)

27 = pedestrian crossing (danger)

28 = school crossing (danger)

29 = cycles crossing (danger)

30 = snow (danger)

31 = animals (danger)


32 = restriction ends (other)

33 = go right (mandatory)

34 = go left (mandatory)

35 = go straight (mandatory)

36 = go right or straight (mandatory)

37 = go left or straight (mandatory)

38 = keep right (mandatory)

39 = keep left (mandatory)

40 = roundabout (mandatory)

41 = restriction ends (overtaking) (other)

42 = restriction ends (overtaking (trucks)) (other)


