# README for AGP_ClassTest by B00324366

Include directories
Right-Click solution is vs -> C/C+ -> General -> Additional Include Directories and enter these paths
C:\dev\glm-0.9.4.4
C:\dev\glew-2.1.0\include
C:\dev\SDL2-2.0.8\include

Include Additional Libraries Directories
Right-Click solution is vs -> Linker -> General -> Additional Libraries Directories and enther these paths
C:\dev\SDL2-2.0.8\VisualC\Win32\Debug
C:\dev\glew-2.1.0\lib\Debug\Win32

After this go to Linker -> Input -> Additional Dependences and enter these file names
glew32d.lib
SDL2.lib
SDL2main.lib

The additonal files needed such as the .obj files can be found in the folder on the moodle submission and must be inseted into this folder
..\..\AGP_ClassTest\AGP_ClassTest\AGP_ClassTest

The .dll files must be place in this folder
..\..\AGP_ClassTest\AGP_ClassTest\Debug

All dependencies are the latest version and were used within the lab enviroment 
