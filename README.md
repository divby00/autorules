# Autorules
Small script to prepare basic LDtk autorules from Tilesetter blob output image

## Usage
Just run the python script with the -t parameter to point to the tileset taken from Tilesetter

Example:
  
  autorules.py -t tileset.png
  
The PNG is expected to be on the following format:

![Blob tileset from Tilesetter](https://user-images.githubusercontent.com/7277786/147404411-9b9a40fc-84e4-4c8e-8984-ff6293cf562b.png)

The script output will be a file called 'output.ldtk', you can open it with LDtk.
