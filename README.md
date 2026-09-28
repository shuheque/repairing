# repairing
reparing kits

## hp_feature_byte_crc.py
HP laptop/desktops need to input BID/Feature Bytes after reset bios, but they are hard to identify upper/lower cap, else you got "CRC invalid";
Here is way to validate your input and adjust if your inputs are valid;
feature byte末尾的.XX为校验码，计算feature byte的校验码，或者验证校验码是否正确；

## hp_feature_byte_decode.py
Decode feature byte into human readable format;
解码feature byte为可读信息；
