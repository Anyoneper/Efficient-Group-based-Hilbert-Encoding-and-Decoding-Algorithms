# Hilbert-Group-Encoding-and-Decoding
Efficient Group based Hilbert Encoding and Decoding Algorithms

This repositary contains four files:CHM_8.bin, CSM_8.bin,HCM_8.bin and HSM_8.bin, corresponding to four procomputed 8-order state-views, namely CHM, CSM, HCM and HSM. 

Also Group_K.cpp provides the generation of the kth order state views CHM_k, CSM_k, HCM_k, and HSM_k, which can be opened and executed separately.

Opening and executing FVFG.cpp can be done by following steps:
1, First create a new project;
2. Add the FVFG.cpp file to that project;
3, Open the local address where the FVFG.cpp file is stored;
4. Copy the four files CHM_8.bin, CSM_8.bin, HCM_8.bin and HSM_8.bin to the local address where the FVFG.cpp file is stored;
5. Execute the FVFG.cpp file in the compiler;

In the main function, we firstly load the four 8-order state-views from the four files, then separately call each of following four algorithms:
en_FVFG: the virtual-filling based group encoding algorithm
en_FVFG_batch: the batched en_FVFG algorithm
de_FVFG: the virtual-filling based group decoding algorithm
de_FVFG_batch: the batched de_FVFG algorithm

Note that this sample code works just for the order 8. Please do not change the group size parameter g in the main function unless you have generated the state-views for the specific g.
