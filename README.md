# mupdf
An Android Libray for  viewing PDF with signature. 

一款优秀的pdf库，能正确的加载带签署信息的mupdf库。

<a href="art/mupdf.png"><img src="screenshot.gif" width="30%"/></a>

# 使用方法
1.下载mupdf库。
  `git clone https://github.com/Neo-Turak/mupdf.git`
  
2.Android Studio 在项目中
    File-Import Module.. 并选择下载的mupdf库。

3.编译->完成。

通过把PDF用APP打开的方式，可以打开浏览了。

如果需要，可以定制化DocumentViewer。
如果加入aar 格式，请加入依赖
repositories 下
```
      maven {
            allowInsecureProtocol=true
            url 'http://maven.ghostscript.com'
        }
```

在Build.gradle里引入
        
`implementation 'com.artifex.mupdf:fitz:1.18.0'`

mupdf直通车->[MUPDF](http://www.mupdf.com)
