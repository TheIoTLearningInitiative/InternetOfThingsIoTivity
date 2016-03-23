Introduction
==

- [Slashdot The IoT, the MinnowBoard, and How They Fit Into the Universe (Video)](https://hardware.slashdot.org/story/15/08/24/1856256/the-iot-the-minnowboard-and-how-they-fit-into-the-universe-video)

This is are the steps followed to know IoTivity

- [IoTivity Documentation Linux Getting Started](https://www.iotivity.org/documentation/linux/getting-started)
- https://wiki.iotivity.org/running_sample_codes_in_iotivity_0.9_sdk_on_edison
- https://wiki.iotivity.org/_media/oicsensorboardreadme.pdf
- http://pagealh.com/2015/08/15/intel-edison-investigating-iotivity/
- https://github.com/mwichmann/meta-oic
- http://git.yoctoproject.org/cgit/cgit.cgi/meta-oic/tree/README?h=master
- http://slideplayer.com/slide/8777224/


```sh
    # apt-get install libboost-dev libboost-program-options-dev libexpat1-dev libboost-thread-dev uuid-dev libssl-dev
    # apt-get install libglib2.0-dev autoconf libtool scons
    # git clone https://github.com/01org/tinycbor.git extlibs/tinycbor/tinycbor
    # scons WITH_RA=1 WITH_RA_IBB=1
    # ./auto_build.sh
    # echo "Android SDK was built"
 ```
 
 ```sh
 —- iotivity-resource : Contains IoTivity resource libraries as release mode
shared libs.  
-- iotivity-resource-dev : Contains IoTivity header files.
-- iotivity-resource-staticdev : Contains IoTivity resource thin client SDK
as static libraries.
-- iotivity-resource-dbg : Contains IoTivity resource libraries with debug
symbols.  
-- iotivity-resource-samples : Contains sample IoTivity resource client and
server applications built in release mode.  
-- iotivity-resource-samples-dbg : Contains debug builds of sample IoTivity
resource clients and servers.  
-- iotivity-service : Contains IoTivity service runtimes (Plugin Manager Impl,
Things Manager, Soft Sensor Manager, Notification Manager), protocol plugins,
and soft sensor plugins.
-- iotivity-service-dev : Contains IoTivity service header files.
-- iotivity-service-staticdev : Contains IoTivity service SDK as static
libraries.
-- iotivity-service-dbg : Contains debug versions of IoTivity service runtimes.
-- iotivity-service-samples : Contains IoTivity service sample applications in
release mode.
-- iotivity-service-samples-dbg : Contains IoTivity service sample applications
in debug mode.
-- iotivity-tests : Contains IoTivity framework unit tests in release mode.
-- iotivity-tests-dbg : Contains IoTivity framework unit tests in debug mode.
-- iotivity : Meta-package which installs all IoTivity runtimes from packages
listed above.  
—- iotivity-dev : Meta-package which installs all runtimes and development files
from packages listed above.
-- iotivity-simple-client : Contains only the simpleclient example.  
 ```