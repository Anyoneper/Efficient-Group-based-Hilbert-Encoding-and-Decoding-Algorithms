# Hilbert-Group-Encoding-and-Decoding
Efficient Group-Based Hilbert Coding and Decoding Algorithms

This repository contains four files, CHM_8.bin, CSM_8.bin, HCM_8.bin, and HSM_8.bin, which correspond to four computed 8-order state-views i.e., CHM, CSM, HCM, and HSM.

Meanwhile Group_K.cpp provides the generation of the K-order state-views CHM_k, CSM_k, HCM_k, and HSM_k, and the order K can be modified by yourself. It can be opened and executed separately through Group_K.cpp.

Opening and executing FVFG.cpp can be done by following steps:
1, First create a new project;
2. Add the FVFG.cpp file to that project;
3. Open the local folder where the FVFG.cpp file is stored;
4. Copy the four files CHM_8.bin, CSM_8.bin, HCM_8.bin and HSM_8.bin to the local folder where the FVFG.cpp file is stored;
5、Execute the FVFG.cpp file in the compiler, such as visual studio 2022, Visual Studio Code, and so on;

In the main function, we first load the four 8th order state views from the four files and then call each of the following four algorithms: en_FVFG: virtual padding based group encoding algorithm en_FVFG_batch: batch en_FVFG algorithm de_FVFG: virtual padding based group decoding algorithm de_FVFG_batch: batch de_FVFG_batch: batch de_FVFG algorithm FVFG algorithm

Please note that this example code is for 8th order only. Do not change the group size parameter g in the main function unless you have already generated a state view for the particular g.

In the main function, we firstly load the four 8-order state-views from the four files, then separately call each of following four algorithms:
en_FVFG: the virtual-filling based group encoding algorithm
en_FVFG_batch: the batched en_FVFG algorithm
de_FVFG: the virtual-filling based group decoding algorithm
de_FVFG_batch: the batched de_FVFG algorithm

Note that this sample code works just for the order 8. Please do not change the group size parameter g in the main function unless you have generated the state-views for the specific g.
