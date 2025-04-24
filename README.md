fork for pake : https://github.com/tw93/Pake

pack the web : https://www.age.tv

采用在线Actions的[Build App With Pake CLI]功能，以下是部分填写的参数

{

Platform: windows-latest

url: https://www.age.tv/

name: AGE

icon: https://raw.githubusercontent.com/UMR-kira/AGE-Anime/refs/heads/main/src-tauri/png/age_256.ico

height: 720

width: 1280

fullscreen: true

}

提示：

1、name不能有中文字符

2、icon程序检查确定为ico格式，然后上传到仓库即可获取对应的链接，如果是其它网页在线的ico文件不一定格式正确，会在Action后报错

3、尺寸默认是1200x780，我改成1280x720了，也就是16：9，个人感觉区别不大，当缩放比例为200%时，1280为2560宽度刚好填满2k屏幕
