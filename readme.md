To run in collab
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

   
