# Minimal OpenCL program on Windows

This is a sample project to demonstrate a minimal OpenCL project on Windows. To compile it you only need MinGW64 and a graphics driver with an OpenCL runtime. Then compile it with

	gcc -I. main.c C:\Windows\System32\OpenCL.dll -o main.exe

No SDK or anything else needed. More details in [this article](http://arkanis.de/weblog/2014-11-25-minimal-opencl-development-on-windows).
