# AnchCare: Personalized Prognosis of ICU Patients with Emerging Epidemic via Clustering-Based Anchor

The source code for *AnchCare: Personalized Prognosis of ICU Patients with Emerging Epidemic via Clustering-Based Anchor*

## Visualization
Welcome to test the prototype of our visualization tool:

The dynamic visualization system is available at:<br>
https://anonymous20201020.github.io/AnchCare-DeadGraph/.

The AI-Doctor interaction interface is available at:<br>
http://47.93.42.104/covid/63. (Discharge)<br>
http://47.93.42.104/covid/240. (Mortality)<br>

## Data Preparation
The Tongji Hospital COVID-19 dataset is introduced at: https://www.nature.com/articles/s42256-020-0180-7

## Case Observation
| Record | Date      | Cluster ID | Condition          | Avg. LOS Risk | #Records |      Important Features      |
| :----: | :-------: | :--------: | :----------------: | :-----------: | :-------------: | :--------------------------: |
|   0    | Feb.4     | 3          | Low Risk        | 23.413        | 55   |   Hgb, pH   |
|   1 - 2    | Feb.4     | 42          | Low Risk        | 16.545        | 108   |   LIN%, Platelets   |
|   3    | Feb.4     | 19          | Low Risk        | 15.411        | 146   |   LIN%, neutrophils(%)   |
|   4 - 5    | Feb.4     | 49          | Low Risk        | 14.553        | 168   |   LIN%, Monocytes(%)   |
|   6 - 8    | Feb.4     | 9          | Low Risk        | 13.808        | 171   |   LIN%, Monocytes(%)   |
|   9    | Feb.4     | 47          | Low Risk        | 12.488        | 139   |   Eosinophils(%), LIN%   |
|   10    | Feb.6     | 27          | Low Risk        | 10.260        | 154   |   Eosinophils(%), Platelets   |
|   11    | Feb.7     | 12          | Low Risk        | 9.423        | 160   |   Eosinophils(%), Platelets   |
|   12    | Feb.7     | 34          | Low Risk        | 8.601        | 169   |   2019-nCoV, RDW   |
|   13    | Feb.7     | 20          | Low Risk        | 7.824        | 175   |   2019-nCoV, Platelets   |
|   14 - 15    | Feb.8     | 4          | Low Risk        | 7.052        | 299   |   2019-nCoV, RDW   |
|   16 - 17    | Feb.12    | 15          | Close to discharge        | 6.432        | 372   |   2019-nCoV, RDW   |
|   19    | Feb.14     | 37          | Close to discharge        | 5.749        | 212   |   2019-nCoV, Eosinophils(%)   |

## Requirements
- Install python, pytorch. We use Python 3.7, Pytorch 1.2.
- If you plan to use GPU computation, install CUDA

All the hyper-parameters and steps are included in the AnchCare.ipynb file.


