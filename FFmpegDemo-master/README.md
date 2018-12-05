# FFmpegDemo
视频直播和播放转码器框架

介绍：
-----

    FFmpeg是一套可以用来记录、转换数字音频、视频,并能将其转化为流的开源计算机程序。采用LGPL或GPL许可证。
     
    它提供了录制、转换以及流化音视频的完整解决方案。它包含了非常先进的音频/视频编解码库libavcodec,为了保证高可移植性和编解码质量,libavcodec里很多codec都是从头开发的。
      
    FFmpeg在Linux平台下开发,但它同样也可以在其它操作系统环境中编译运行,包括Windows、Mac OS X等。这个项目最早由Fabrice Bellard发起,现在由Michael Niedermayer维护。
     
    许多FFmpeg的开发人员都来自MPlayer项目,而且当前FFmpeg也是放在MPlayer项目组的服务器上。项目的名称来自MPEG视频编码标准,前面的"FF"代表"Fast Forward"。
      
    简单来说，FFmpeg是一个免费的多媒体框架,可以运行音频和视频多种格式的录影、转换、流功能,能让用户访问几乎所有视频格式,包括mkv、flv、mov,VLC Media Player、Google Chrome浏览器都已经支持。
    
说明：
-----

    本demo中的FFmpeg已经编译过了，可以随意拖入到项目中，添加需要的库文件和框架就可以build success。
![image](https://github.com/xiayuanquan/FFmpegDemo/blob/master/show.png)   


拓展：
-----

    FFmpeg既有转码的功能，本身也具有视频媒介的特性，可以作为播放器使用。其实，ijkplayer是一个挺不错的视频直播和播放的框架。
    它仅仅使用FFmpeg进行视频的转码，自己作为一个播放器进行播放.
    
    ijkplayer框架集成可以看博客：http://www.cnblogs.com/XYQ-208910/p/5856815.html
    
    
演示：
-----

    在控制器中给出视频文件，点击按钮即可播放，显示帧数和时间

### 网络视频                    

![image](https://github.com/xiayuanquan/FFmpegDemo/blob/master/movie.png)   
### 网络直播 
![image](https://github.com/xiayuanquan/FFmpegDemo/blob/master/movie2.png) 
