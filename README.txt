
To use the compressors:

- You must have python in your path.

- You must have the bitarray python module installed.

- Ensure that the file you are trying to compress is located in the input folder.

- If you're only decompressing something, make sure you use the same python file as you did when compressing it.


Instructions:

- Extract the source folder to a directory that does not require administrative permissions.

	***** Make sure the compressed, decompressed and input folders are all present *****

- In a Command Prompt/Terminal window, navigate to the source directory.

- Enter the command:

	python *compressor.py* *inputfile.ext* *windowsize*

  where:
		compressor.py: either lz77.py, lz77-bytewise.py or lzss.py
		inputfile.ext: your input filename, with the file placed in the correct folder
		windowsize: an integer representing the desired window size - use 0 if you wish to only decompress

- If you wish to decompress a file, place the file in the decompressed folder, and use 0 as the window size. 
  Otherwise, all input files should go in the input folder.

- Once complete, the window will display the results of the compression, including the runtime and compression
  statistics.

	*****    Please note that the files in the compressed/decompressed folder will be overwritten    *****
	***** if the compressor is run on the same file multiple times, even using different parameters. *****


Other Notes:

I have provided the input files used in gathering results for the writeup, for your reference.