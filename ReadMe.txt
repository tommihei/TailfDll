Tailf

Tailf is a C# implementation of the tail -f command available on unix/linux systems. 
Differently form other ports it does not lock the file in any way so it works even if other rename the file.

TailfDll 15.2.2019

This is the dll implementation of the Codeplex project Tailf (http://tailf.codeplex.com/) of Felix Pollan with some enhancements.
The dll implementation is same as in the tail.cs of the tailf project, but just added possibility to get lines in list format if there is no event handler.
The dll project is added to the original Visual Studio solution.

License is GNU Lesser General Public License (LGPL) Version 2.1.
