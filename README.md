# PEncode
Encoding files in photos

Usage:

1) Compile in netbeans (frame.java)

2) Click on encode and choose a file (any size)

3) Find the generated folder where you ran the program. It will be around the same size as the file, but filled with 512x512 pngs

4) Click decode and find the folder, you will see a new file called out - [foldername], which is the decoded file

General Info:

The program uses a 512x512 RGB png, meaning it can store 512\*512\*4 bytes in each png (4 channels, 1 byte per channel). This totals 1048576 bytes, or exactly 1 Mebibyte (MiB) per png (slightly over 1 Megabyte).

\*Note the file size limit is currently ~2GB.
