# RoofD

RoofD is dataset for flat roof defect segmentation

## Details

RoofD dataset contains 6400 color image pairs (aerial image and segmentation mask) with size of 1024x576 divided on two parts: train (5184 image pairs) and test (1216 image pairs).

![RoofD fragment](https://github.com/yuddim/RoofD/blob/master/resources/Figures%20-%20RoofD.png)

Roof defect segment catergories:

“hollows” (a), “swellings” (b), “folds” (c), “patches” (d) and “breaks” (e)

![Roof defect segment catergories](https://github.com/yuddim/RoofD/blob/master/resources/Figures%20-%20Defects.png)

Details of RoofD Dataset:
| Segment category | Train ID | Color	| Pixels (train) | Pixels (test) 	| Images (train) | Images (test)  |
|------------------|---------|---------|---------|---------|-------|---------|
| background	| 0	| (0, 0, 0)	| 2749885350	| 638910979	| 5184	| 1216 | 
| hollows	| 1	| (255, 255, 0)	| 154395478	| 34493513	| 3598	| 751 | 
| swellings	| 2	| (153, 255, 204)	| 143853128	| 42520381	| 3307	| 896 | 
| folds 	| 3	| (6, 89, 182)	| 8763604	| 1098290	| 1199	| 208 | 
| patches 	| 4	| (0, 255, 255)	| 642958	| 126472	| 107	| 31 | 
| breaks	| 5	| (255, 193, 255)	| 107098	| 76349	| 54	| 32 | 

## Download

Download RoofD parts:
- [RoofD train (3.7 GB, 5184 image pairs)](https://drive.google.com/open?id=1l5hWzXC7McRox6Z_RgYgLMGWRK5TJSDa)
- [RoofD test (0.9 GB, 1216 image pairs) ](https://drive.google.com/open?id=1q_G5v6S41ZicJIU-yw1Sv6MCWS3mNWdv)
