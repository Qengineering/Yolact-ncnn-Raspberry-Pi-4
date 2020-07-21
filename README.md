# Yolact-ncnn on Raspberry Pi 64 bits
![output image]( https://qengineering.eu/images/Yolact_result_zebra.png )

## Yolact on bare Raspberry Pi 4 with the ncnn framework.
The frame rate is about 3.5 sec per image<br/>
Paper: https://openaccess.thecvf.com/content_ICCV_2019/papers/Bolya_YOLACT_Real-Time_Instance_Segmentation_ICCV_2019_paper.pdf <br/>
Size: 550x550 <br/><br/>
Special made for a bare Raspberry Pi see https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html <br/>
## Dependencies.
To run the application, you have to:
- A raspberry Pi 4 with a 64-bit operating system. It can be the Raspberry 64-bit OS, or Ubuntu 18.04 / 20.04. (https://qengineering.eu/install-raspberry-64-os.html) <br/>
- The Tencent ncnn framework installed. (https://qengineering.eu/install-ncnn-on-raspberry-pi-4.html) <br/>
- OpenCV 64 bit installed. (https://qengineering.eu/install-opencv-4.3-on-raspberry-64-os.html) <br/>
- Code::Blocks installed.
## Running the app.
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/Face-Mask-Detection-Raspberry-Pi-64-bits/archive/master.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
Face_1.jpg <br/>
Face_2.jpg <br/>
Face_3.jpg <br/>
Face_Mask_Video.mp4 <br/>
MaskUltra.cpb <br/>
mask_ultra.cpp <br/>
UltraFace.cpp <br/>
UltraFace.hpp <br/>
RFB-320.bin <br/>
RFB-320.param <br/>
slim_320.bin <br/>
slim_320.param <br/>
 <br/>
The RFB-320 model recognizes slightly more faces than slim_320 at the expense of a little bit of speed. It is up to you.<br/>
Note that the compilation of the Paddle Lite framework in your application can take minutes (> 3 min). <br/> <br/>
See the video at https://youtu.be/LDPXgJv3wAk
