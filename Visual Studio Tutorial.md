# How to create a new win32 C++ project in Visual Studio 2017
After opening Visual Studio 2017 application, do the following:
1. FILE > NEW > PROJECT
2. Set it as Visual C++ type

	1.Go to General
	2.Begin with an Empty Project
	3.NOTE: Do not save on default location, create a file (ei. 'bin'), and back file up.
3. Go to the project properties by right clicking on the name under 'Solutions'
	1.Under 'General', make sure the SDK is okay and up to date.
	2. Go to Linker > System > Subsystem and set it to console, this will give you a system pause.
4. Lastly, add a source file by right clicking on source file
	1. Add > New Item... > C++ File (.cpp)
	2. Rename it 'main.cpp'
