## Data Structures and Algorithms ##
### _Merge Sorting_ ###
### [16,21,11,8,12,22] -> Merge Sort ###
S for Step 
+ S1 --> [16,21,11] [8,12,22]
+ S2 --> [16,21] [11]   [8,12] [22]
+ S3 --> [16] [21] [11] [8] [12] [22]
+ S4 --> [16,21] [11]   [8,12] [22]
+ S5 --> [11,16,21] [8,12,22]
+ **S6 --> [8,11,12,16,21,22]** 
### Big O Notation ###
+ **O(n*(logn)) --> O(6*(log6))**
