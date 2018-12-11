# Steganography-with-RSA

## Methodology
Steganography is the field of transmitting data within covert channels such as images, videos, audios, etc. so as to not raise any suspicion.
In this project I implemented least significant bit method in which the data is hidden in the LSB of a pixel. This works because human eye is
not able to percieve the change in color differing by 1 LSB. For example, to a human eye 255 (11111111) and 254 (11111110) appear to be same.
This idea is exploited to embed secret data within the image itself.

Further RSA encryption is added to prevent an adversary who may suspect data to be embedded within the file to read its contents.

## Results
The results can be seen with the help of the two pictures where barbara.bmp is the original image whereas barbaraRSA.bmp is the encoded image with the secret data.
Both of them perceive to be equivalent but in reality are not.

Further metrics such as PSNR can be calculated to get the destortion added to the image.


#### Thanks to RameshAditya for his help
