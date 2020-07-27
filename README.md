# Smart Traffic Control System

This was the AI code that was designed for Traffic Management purposes in Rakuten's Rakathon 2.0 

Was meant to be implemented on a Raspberry Pi with a camera module.

The Inspiration and the backstory is documented in [Rakathon2.pdf](https://github.com/imPdhar/Traffic-Signal-Optimisation-/blob/master/Rakathon2.pdf) 

## Features 

- Detects number of different vehicles in the scene and gauges the time required for each different vehicles.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               

- Prioritizes pedestrian safety.

- Designed to prioritize Ambulance passage.

  

## Requirements:

- OpenCV- `pip install opencv-python` 		
- Numpy- `pip install numpy`
- An appropriate dataset like [coco](https://cocodataset.org/#download). 

## How to use

-  Install the requirements.
   1. Place the image files in the  /images directory.
   2. Choose the image which you would like to analyze and copy its directory in your clipboard.
   3. Use the argument **-i** to input the path of the image file and **-y** to input the path of the YOLO model in the command line to run the code. 

## Known Errors

Incorrect labelling of Automobiles. 

**Solution**: Train the model with the right class-labelling. 

