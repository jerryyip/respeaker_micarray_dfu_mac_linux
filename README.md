# respeaker_micarray_dfu_mac_linux

This is a DFU tool to upgrade ReSpeaker Microphone Array Firmware on Mac/Linux.

## How to use

1. 
```
git clone https://github.com/jerryyip/respeaker_micarray_dfu_mac_linux.git
```

2. 
```
cd respeaker_micarray_dfu_mac_linux
make
```

3. 
```
export DYLD_LIBRARY_PATH=$PWD:$DYLD_LIBRARY_PATH
```

4. 
```
./xmosdfu --download ReSpeaker_Mic_Array_firmware_raw_0x83_20170601.bin
```
