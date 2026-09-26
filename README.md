# Descriptions
This folder contains scripts used in "Data-driven investigation of bacterial growth dynamics in response to the medium-drug interplay" by Taro Kawano, Shunpei Araki and Bei-Wen Ying.

# Data
This file describes the relationship between the chemical component concentrations of each culture medium and three types of growth parameters. The file contains six sheets: "na", "multi", "kan", "nal", "ery", and "rif", which indicate the drug conditions. In each sheet, the column for each chemical component represents its concentration (mM). The columns "r", "K", and "t" represent the values of the respective growth parameters.

# Nested_GBDT
This file contains code to calculate the contribution of each chemical component to the growth parameters. In the output file, columns "1", "2", "3", "4", and "5" represent each of the five independently constructed models. The "mean" and "sd" columns indicate the average and standard deviation across these five models, respectively. The "Model_Score_R2" row represents the model accuracy, and the row for each chemical component indicates its feature importance.
