
# Environment3
A library for android to access all storage that are connected to the device. This project is the continuation of the project Environment2 by  Jörg Wirtgen that support all android version 

In this library i made a new project cernel to Environment2 to support API 19 and later too.

#Usage:

Download project from this link:
https://github.com/omidfaraji/Environment3/archive/master.zip

Insert environment3.jar (this file is in lib folder of project)  as project dependency and use it.

All usage is similar with Environment2.

#Some sample of useage:


 Getting all storage device:
 
    Device[] devices = Environment3.getDevices(null, true, true, false);
  	
  	
 Getting root file of Storage:
 
    File storageFile=device.getFile();

		
 Getting cach file of Storage:
 
    File cachStorageFile=device.getCacheDir(context);


 Getting External SDCard File:
 
    File externalSDCardFile=Environment3.getSecondaryExternalStorage().getFile();

 

