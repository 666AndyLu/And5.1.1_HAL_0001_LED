编译hal文件： arm-eabi-gcc -fPIC -shared hardcontrol.c -o libhardcontrol.so -I /usr/lib/jvm/java-1.7.0-openjdk-amd64/include/ -nostdlib /work/SC20_R01/prebuilts/ndk/9/platforms/android-19/arch-arm/usr/lib/libc.so /work/SC20_R01/prebuilts/ndk/9/platforms/android-19/arch-arm/usr/lib/liblog.so -I /work/SC20_R01/prebuilts/ndk/9/platforms/android-19/arch-arm/usr/include/ 
在安卓目录下查找find -name "log.h"
在安卓目录下查找find -name "liblog*"
