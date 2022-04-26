# libdemo
This is a simple demo to build a native library for AOSP.

1. Clone this repository into external dir in AOSP source tree.
2. Build it with the following steps.
```
$ . build/envsetup.sh
$ lunch $(TARGET)-userdebug
$ external/libdemo/
$ mm
```
3. The final library will be generated in target dir.
```
out/target/product/$(TARGET)/vendor/lib/libdemo.so
```
