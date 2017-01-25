# Motion-Estimation
In this Project we implement two motion estimation algorithm:1- Full Search Motion Estimation 2- Fast Search Motion Estimation (Cross Search Algorithm). 
In DemoExpriment1I.m we Do Full Search motion estimation between frame2 with reference to frame1 and calculate the motion compensated frame quality with search windows (4 pixels/frame, 8 pixels/frame, 16 pixels/frame, 32 pixles/frame) with block size equal to 8 pixel, then change block sizes of: 4,8,16 and 32 pixels with search window 16 pixels/frame . 
In DemoExpriment1II.m we Do Fast Search motion estimation between frame2 with reference to frame1 and calculate the motion compensated frame quality with search windows (4 pixels/frame, 8 pixels/frame, 16 pixels/frame, 32 pixles/frame) with block size equal to 8 pixel, then change block sizes of: 4,8,16 and 32 pixels with search window 16 pixels/frame
In bidirectional.m we do bi-directional motion compensation between frame 2 and reference of frame 1 and motioncompensated frame 3, with a search size of 16 pixels/frame (integer accuracy) for full search motion estimation and fast search motion estimation
