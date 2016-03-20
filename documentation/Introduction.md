Introduction
==

This is are the steps followed to know IoTivity

- [IoTivity Documentation Linux Getting Started](https://www.iotivity.org/documentation/linux/getting-started)
- https://wiki.iotivity.org/running_sample_codes_in_iotivity_0.9_sdk_on_edison

```sh
    # apt-get install libboost-dev libboost-program-options-dev libexpat1-dev libboost-thread-dev uuid-dev libssl-dev
    # apt-get install libglib2.0-dev autoconf libtool scons
    # git clone https://github.com/01org/tinycbor.git extlibs/tinycbor/tinycbor
    # scons WITH_RA=1 WITH_RA_IBB=1
    # ./auto_build.sh
    # echo "Android SDK was built"
 ```