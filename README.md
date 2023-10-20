# Minimal OpenCL program on Windows

This is a project to demonstrate a minimal OpenCL project on Windows.

# MinGW Instructions

```shell
	gcc -I Include -L Lib Examples\hello.c -o hello.exe -lopenCL 
```

For C++, Ensure you have [MinGW Compat Headers](https://github.com/guilt/mingw-std-threads)
cloned, generated and `CPLUS_INCLUDE_PATH` set to.


```shell
	g++ -I Include -L Lib Examples\print_info.cpp -o print_info.exe -lopenCL 
```

# More Details

More details in [this article](http://arkanis.de/weblog/2014-11-25-minimal-opencl-development-on-windows).
