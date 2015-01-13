# EasyPR_Dll_src
这里的文件是用来生成EasyPR的DL。

文件里默认引用的opencv库是248，如果需要修改可以参照如下的方式：
在plate_recognize.cpp里有
pragma comment(lib,"opencv_calib3dXXX.lib") 类似的语句，将其中XXX的数字改成你对应的opencv版本再编译。


