# Sift-based Object Detection
We implemented the SIFT algorithm presented in this [paper](https://link.springer.com/article/10.1023/B:VISI.0000029664.99615.94) for detecting an object that had 2 modes. One was the car mode and another was the humanoid mode.

## Results: 

**Car: Clutterd**
![clutter_1](https://user-images.githubusercontent.com/35029771/178829700-4d1d7e54-a82d-499d-bfcb-1a7375da66ca.png)

**Car: Rotated**
![rotated](https://user-images.githubusercontent.com/35029771/178829723-1b0c85bf-3dd2-4f10-9190-973ec982c707.png)

**Humanoid: Cluttered**
![clutter_standing](https://user-images.githubusercontent.com/35029771/178829748-40eff062-0a2e-4669-8d2e-9e3191d5a357.png)

**Humanoid: Distanced**
![distanced_2](https://user-images.githubusercontent.com/35029771/178829796-5349e610-1d16-4337-88b0-e4057952a201.png)

---

## Tools and Frameworks

**IDE:** VS Code <br>
*(Any IDE of choice may be used)*

**3rd party libraries:**
- OpenCV 4.2

---
## Usage

If you would like to run this code make sure it is in the same directory as the Data_Set Repository. To run the code just run at the main.P why file. If you would like to change the image change the path location in the __name__==’main’ function.
The GenerateDatabaseInfo.py file is meant to create the database of model keypoints and should not neeed to be run.


    ```bash
	$ python3 main.py
	```	
---
    
    
