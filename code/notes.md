# Plan of Action

### Preprocessing
1. Crop Image to circle - remove the edges

___


## Stages
### First
1. Take an image and convert it to NDVI
2. Return what percentage of the image is life
3. Calculate the land coverage per image

### Second
---
1. Itterate over an existing dataset to create NDVI values
2. Split the images created in an array of numbers (1>10) that represent how "green" a pixel is, this can then be used in the predictive algorihtm. 

---
### Astro Pi Possible Measurements
Existing NDVI dataset: https://neo.gsfc.nasa.gov/view.php?datasetId=MOD_NDVI_M&year=2001
	
- time	
- humidity	
- temperature	
- pressure	
- gyro_pitch	
- gyro_roll	
- gyro_yaw	
- accel_pitch	accel_roll	
- accel_yaw	
- accel_x	
- accel_y	
- accel_z	
- magnet_x	
- magnet_y	
- magnet_z	
- Lat_deg	
- lat_min	
- lat_sec	
- long_deg	
- long_min	
- long_sec