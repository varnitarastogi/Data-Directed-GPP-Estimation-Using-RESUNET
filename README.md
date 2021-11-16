# GPP-ESTIMATION-USING-RESUNET
Gross Primary Productivity(GPP) is the measure of total carbon fixed by plants into the atmosphere during the process of photosynthesis. It depends on various climate variables such as precipitation, temperature , moisture in the soil and radiation energy from the sun. This project aims to estimate GPP by finding non linear relationships between these variables and how they affect GPP over time.


## Data
The data is in the form of iris cubes and has been taken from two Earth System Models- UK Earth System Modelling Project (UKESM) and Beijing Climate Center Earth System Model version 1 (BCC-ESM1).It is in a gridded format with 64 latitude coordinate points and 128 longitude coordinate points for BCCESM and 144 latitude coordinates and 192 longitude
coordinates for UKESM and has been taken on seasonal and annual basis.

## Architecture
The CNN is based on UNet architecture with Resblocks. 
It has been referenced from https://github.com/Nishanksingla/UNet-with-ResBlock .
![my_resunet](https://user-images.githubusercontent.com/73664577/142017799-193c0a8a-711e-4d43-a590-8d9b52f2e935.png)

## Results
The estimated GPP by the model is visualized as follows-
![bcc_ann_gpp](https://user-images.githubusercontent.com/73664577/142029030-79fa9c24-b394-43f3-85be-b8c46bfc8ed3.png)

