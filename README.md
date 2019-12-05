# Traffic-Signs-Detection
SIGNS_LOOKUP = {
        (1, 0, 0, 1): 'Turn Right', # turnRight
        (0, 0, 1, 1): 'Turn Left', # turnLeft
        (0, 1, 0, 1): 'Move Straight', # moveStraight
        (1, 0, 1, 1): 'Turn Back', # turnBack
    }
    
    
    
The sign_lookup matrix is defined to distinguish between ahead, back, left and right showing traffic signals. The algorithm can be used to define other traffic signs also. Video is captured using a webcam and output window is generated after initial code run. Test it on the sample images. currently works on these four signs, you can add up more sign matrices and also define functions for traffic signals.
    
    Compiled on Python 3.6.2
