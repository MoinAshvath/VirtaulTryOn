To run in collab change runtime to cpu to t4 gpu
1. Clone the repository:
   ```
   !git clone https://github.com/MoinAshvath/VirtualTryOn.git
   ```
2. Navigate to the project directory:
   ```
   %cd VirtualTryOn
   ```
3. Install:
   ```
   !pip install ninja
   ```
4. Face Alignment:
   ```
   !python align_face.py -seed 42
   ```
5. Run Main:
   ```
   !python main.py --im_path1 15.png --im_path2 16.png \
      --im_path3 16.png --sign realistic --smooth 5
   ```
The output image can be downloaded as png format by navigating to the output directory under the Blend_realistic folder.
## result
<img width="1078" alt="Screenshot" src="https://github.com/MoinAshvath/VirtualTryOn/blob/main/output.png">


   
