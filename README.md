# SME-Assignment

**Part-1** 
Download SFML and extract files from it.
Copy include and lib folder and paste them in the sfml directory where text file present with name paste here.
To setup the project you must have VS and open .soln file in it.
Once it opened then add make right click on the file open properties.
Goto the C++ in properties and select configration.
Add path to the additional include directory column.
Goto the Linker on the left side and add path of the additional lib directory.
The setup of the project is done with that.

**Part-2**
To debug the project goto properties and select Linker
Select the configuration and platform
In the Linker click on the Input and add 
  sfml-graphics-d.lib
  sfml-window-d.lib
  sfml-audio-d.lib
  sfml-network-d.lib
  sfml-system-d.lib
in the debug configuration
and for release configuration
  sfml-graphics.lib
  sfml-window.lib
  sfml-audio.lib
  sfml-network.lib
  sfml-system.lib
add these file and apply it.
To start select debug and x86 and click on start local debug

It show error C2143, C4430 and C2238 in PlayerController.h