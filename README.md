# qlibrary-example
Simple example project to demonstrate the usage of loading symbols from a shared object using Qt Core's QLibrary class.

使用c++类生成的dll or .so 很难使用动态链接库去调用

故 转换用 extern "C" 加全局函数模式，生成dll or so 

可以方便通过函数名进入函数接口
