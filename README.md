# CodingTask
# Introduction 
This is the implementation for a simple numeric to words converter. 
Ths user will be able to enter a number in valid format and get the word representation of the same.
Expected format :xxx,yy - xxx dollars and y cents

# Getting Started
1.	Installation process:
	-Build the solution and it will create all required outputs in the Build folder inside the Sourcecode Folder
	-Run the GrpcNumericToWordsConverterService.exe from Build\bin\Debug\net6.0
	-Run the ConverterUI.exe from Build\bin\Debug\net6.0-windows
	-Enter the number to be converted - format should be number seperated by a comma indicating dollars and cents
	-Result will be displayed and each converted entry will be added to the list box to show the history
2.	Software dependencies
	-.Net framework 6.0 and above.
3.  Used Technologies
	- .Net 6 Console app for Server
	- .Net 6 wpf for UI
	- grpc for communication
