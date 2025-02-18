# Introduction 
This project aims to provide EPPY scripts enabling automated electrification modeling in EnergyPlus. Each folder contains an example of automated modeling scripts for a specific type of system. The library will expand to contain more automation scripts for different systems.

# Getting Started
Each folder contains the following:
1.	IDD file
2.	Automation scripts
3.	Two input IDF files: one target file that will be modified, one source file that contains the specific electrified system that user want to model to the target file
4.	EPW file

# Build and Test
Download the entire folder fo a specific type of system. The input target file can be changed according to user's needs, minimal manual editting is required.
We suggest not to change the input source file as each script is written for a specific type of system. If any settings of the electrified system need to be changed, please modify the input source file directly.

# Contribute
For datail instructions, see the IBPSA paper (link will added once published) and the annotations within the scripts.
We welcome collaborations to expand this library to include more types of electrified system.

If you want to learn more about creating good readme files then refer the following [guidelines](https://docs.microsoft.com/en-us/azure/devops/repos/git/create-a-readme?view=azure-devops). You can also seek inspiration from the below readme files:
- [ASP.NET Core](https://github.com/aspnet/Home)
- [Visual Studio Code](https://github.com/Microsoft/vscode)
- [Chakra Core](https://github.com/Microsoft/ChakraCore)
