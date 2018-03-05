Extended essay raw data
=======================
The raw data from JPEG encoding library testing experiment in my extended essay "Comparison of lossy JPEG file format image encoders libjpeg-turbo, mozjpeg, jpeg-recompress, jpegoptim and guetzli in terms of encoding speed, compression rate and image quality"

*uncompressed.csv* contains the following data about 15 raw sample images (which can be found on https://github.com/mpoc/EE-sample-images): category, width, height, filesize, amount of pixels and bitrate.

*compressed.csv* contains the following data about compressed sample images: compression tool used, JPEG quality level, filesize, time taken to encode, butteraugli index, visual information fidelity index, multi-scale structural similarity index, bitrate.

The JPEG images were encoded with 5 different encoding tools (libjpeg-turbo, mozjpeg, jpeg-recompress, jpegoptim and guetzli) in 4 different JPEG quality levels (84, 87, 90, 93). Each of the images was rates using 3 different image quality metrics (butteraugli, visual information fidelity, multi-scale structural similarity).
