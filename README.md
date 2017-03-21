# PlayGuetzli
try google Guetzli

玩玩看Guetzli

[Guetzli github](https://github.com/google/guetzli) 
# windows 

windows

[download](https://github.com/google/guetzli/releases)

下載下來(exe)

cmd切換到該資料夾

直接guetzli_windows_x86-x64.exe 你的圖片.png 輸出後的圖片.png

# ubuntu

要先裝 `apt-get install libpng-dev`

然後clone後make後就能用了

資料夾會多一個bin/Release/guetzli

docker的人記得要先裝pkg-config、g++、git、make！

我的docker是用ubuntu 16.04

# Q&A

如果make碰到gflags錯誤

在新版的guetzli已經被移除了

重新下載應該就可以了
