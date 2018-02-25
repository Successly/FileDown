1.前端下载文件

2.一种是后台直接传过来地址 使用window.open()直接下载

3.另一种后台传过来流(二进制)，前端处理

文章：http://blog.csdn.net/zhoumengshun/article/details/71405963



4.还有一种通过ajax来接受二进制流,本质是使用Blob接受，创建a标签实现的，但会有问题
   1.IE 与火狐 不兼容
   2.pdf形式下载不了，csv .html 格式可以，因为ajax只接受text文件形式

5.最好用form 下载（流）