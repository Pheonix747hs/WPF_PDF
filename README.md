First attempt to build a full working application in C#
planned features include a pdf splitter, picture to pdf converter and more
currently only working feature is the viewer , it makes use of the windows10 runtime apis to convert a pdf into a bitmap and displays them in a scrollable viewer
main advantage of this approach is it doesnt require any external libraries and makes use of internal features of windows, 

the winmd file can be found in the bin/debug directory and must be included in the project to allow it to compile in visual studio
