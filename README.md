# argdump
Arg Dump is a C++ console application that dumps program command line arguments.
This is my first C++ program in my course of learning C++

Usage Example:

C:\argdump.exe -d C:\program-files\someprogram\program.exe

Output:
C:\argdump.exe -d C:\program-files\someprogram\program.exe

program.exe accepts the following command line arguments
-a
-novid
-something
-else


ArgDump.exe uses the following command line arguments itself:

argdump.exe ( No Argument ) = Print help text
argdump.exe -d = dump ( argdump.exe -d path\to\executable )
argdump.exe -h = Print help text ( Same as no argument )
