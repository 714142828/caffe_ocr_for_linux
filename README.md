# caffe_ocr_for_linux

> 说明：感谢senlinuc贡献的https://github.com/senlinuc/caffe_ocr，我这里的是linux版本，用caffe的master分支合并的。  

1. 需要先安装wrap-ctc,https://github.com/ChWick/warp-ctc/tree/develop，安装完/usr/local/include/下可能没有ctcpp.h，你可以从源码里复制一份过去
2. 对比下Makefile.config.example文件就知道我改了哪些了，然后make编译就可以了。
3. 测试程序最终会编译在./build/tools/ocr_test 
4. 我只在ubuntu 16.04 、cuda 8.0、cudnn 5.1下测试了
