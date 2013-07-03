nrrd2raw
========

Creates 2 channel Vaa3D raw format file from 2 NRRD files using ImageJ/Fiji

macro is run as: 

fiji -macro nrrd2raw.ijm outputfilename-warp.raw -batch

it requires the two NRRD input image files to have same name as the 'outputfilename' given in the command but with -BGwarp.nrrd and -SGwarp.nrrd instead of -warp.raw

requires the Vaa3D raw writer plugin in fiji: https://code.google.com/p/vaa3d/wiki/ImageJIO 
