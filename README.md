# NN-interaction-sequence data
This repository contains the preprocessed data files used for the parameter calibration in the paper 'Parameter calibration for interacting particle systems driven by neural networks' by Simone Göttlich (University of Mannheim) and Claudia Totzeck (University of Wuppertal). The data processing is based on date from the ESIMAS project (E. Kallo, A. Fazekas, S. Lamberty, and M. Oeser. Microscopic traffic data obtained from videos
recorded on a german motorway. Mendeley Data, V1, 2019).

The first number in the name of the sequence data file refers to the camera (1,...,5) the second number is the day and the third number refers to the sequence. For example sequence_data_3-1_2.mat is the preprocessed data of the second sequence of the third camera on day one.

When loading the file in matlab, you obtain a cell array with several struct objects, each of these structs contains position and timestamps for the cars involved in that sequence. The data was used to run the parameter calibration in the aforementioned paper. 

For questions please contact my via totzeck(at)uni-wuppertal.de
