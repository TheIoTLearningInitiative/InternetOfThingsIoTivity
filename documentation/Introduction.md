Introduction
==

- [Slashdot The IoT, the MinnowBoard, and How They Fit Into the Universe (Video)](https://hardware.slashdot.org/story/15/08/24/1856256/the-iot-the-minnowboard-and-how-they-fit-into-the-universe-video)

This is are the steps followed to know IoTivity

- [IoTivity Documentation Linux Getting Started](https://www.iotivity.org/documentation/linux/getting-started)
- https://wiki.iotivity.org/running_sample_codes_in_iotivity_0.9_sdk_on_edison
- https://wiki.iotivity.org/_media/oicsensorboardreadme.pdf


```sh
    # apt-get install libboost-dev libboost-program-options-dev libexpat1-dev libboost-thread-dev uuid-dev libssl-dev
    # apt-get install libglib2.0-dev autoconf libtool scons
    # git clone https://github.com/01org/tinycbor.git extlibs/tinycbor/tinycbor
    # scons WITH_RA=1 WITH_RA_IBB=1
    # ./auto_build.sh
    # echo "Android SDK was built"
 ```