# Blender-pix2vox
## Giulio Mezzotero & Francesco Silvi

Starting from the [Pix2Vox](https://github.com/hzxie/Pix2Vox) we implemented an add-on to have the 3D network output ready to use for modeling inside Blender. 
To use the add-on you need to: 

1) Download the zip from this Git and installing the add-on file inside Blender add-ons section 
2) Download the weights from [Pix2Vox-A](https://gateway.infinitescript.com/?fileName=Pix2Vox-A-ShapeNet.pth)
3) Insert in the add-on (Tools: Pix2Blender): the Input Image folder (3 are provided in this Git to test it), the Core folder and the Weights file.

We also added a [Python parser and writer](https://github.com/gromgull/py-vox-io) to output the .vox model from the network and an [add-on](https://github.com/RichysHub/MagicaVoxel-VOX-importer) to import this model into Blender and work with it.
