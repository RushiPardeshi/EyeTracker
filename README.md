# EyeTracker

To run this file, the data needs to be in the format of 
```
timestamp            datetime64[ns],
is_fix                         bool,
gaze_smooth_x               float64,
gaze_smooth_y               float64,
gaze_raw_x                  float64,
gaze_raw_y                  float64,
lefteye_smooth_x            float64,
lefteye_smooth_y            float64,
lefteye_raw_x               float64,
lefteye_raw_y               float64,
lefteye_psize               float64,
lefteye_p_x                 float64,
lefteye_p_y                 float64,
righteye_smooth_x           float64,
righteye_smooth_y           float64,
righteye_raw_x              float64,
righteye_raw_y              float64,
righteye_psize              float64,
righteye_p_x                float64,
righteye_p_y                float64.
```
The arguments for the eye_heatmap.py file are : 

1. -t : threshold(int)
2. -img : image path on which heatmap to be superimposed
3. -txt : the txt file containing above mentioned columns
