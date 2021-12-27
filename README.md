![output image](https://qengineering.eu/images/SDcard16GB_tiny.jpg) Find this example on our [SD-image](https://github.com/Qengineering/RPi-image)
# Yolact-ncnn on Raspberry Pi 64 bits
![output image]( https://qengineering.eu/images/Yolact_result_zebra.png )<br/>
## Yolact with the ncnn framework. <br/><br/>
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)<br/><br/>
The frame rate is about 3.5 sec per image (RPi overclocked to 1950 MHz)<br/>
Special made for a bare Raspberry Pi see [Q-engineering deep learning examples](https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html) <br/>

------------

Paper: https://openaccess.thecvf.com/content_ICCV_2019/papers/Bolya_YOLACT_Real-Time_Instance_Segmentation_ICCV_2019_paper.pdf <br/>
Size: 550x550 <br/><br/>

------------

## Dependencies.
To run the application, you have to:
- A raspberry Pi 4 with a 32 or 64-bit operating system. It can be the Raspberry 64-bit OS, or Ubuntu 18.04 / 20.04. [Install 64-bit OS](https://qengineering.eu/install-raspberry-64-os.html) <br/>
- The Tencent ncnn framework installed. [Install ncnn](https://qengineering.eu/install-ncnn-on-raspberry-pi-4.html) <br/>
- OpenCV 64 bit installed. [Install OpenCV 4.3](https://qengineering.eu/install-opencv-4.3-on-raspberry-64-os.html) <br/>
- Code::Blocks installed. (``` $ sudo apt-get install codeblocks ```)

------------

## Installing the app.
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/Yolact-ncnn/archive/refs/heads/master.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
dog.jpg <br/>
elephant.jpeg <br/>
girafe.jpeg <br/>
mumbai.jpg <br/>
onyx.jpeg <br/>
result_elephant.png <br/>
result_zebra.png <br/>
Yolact.cpb <br/>
yolact.cpp <br/>
yolact.bin (download this file from [Gdrive](https://drive.google.com/file/d/1vu3GGOEWh-jmedM-cvoqzhGzaZaOQB9k) )<br/>
yolact.param <br/>

------------

## Running the app.
Run Yolact.cpb with Code::Blocks.<br/>
For more info follow the instructions at [Hands-On](https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html#HandsOn).<br/><br/>
Many thanks to [nihui](https://github.com/nihui/) again!

------------

[![paypal](https://qengineering.eu/images/TipJarSmall4.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CPZTM5BB3FCYL) 
