## C++ Include

- C/C++ -> 其他include目錄 -> "D:\Lib\opencv\build\include\"
- Linker -> 一般 -> 其他程式庫目錄 -> "D:\Lib\opencv\build\x64\vc15\lib\"
- Linker -> 輸入 -> 其他相依性 -> "opencv_world455.lib;"
- 偵錯 -> 命令引數 -> "../input_image/ ../output_image/"
- 新增環境變數：D:\Lib\opencv\build\x64\vc15\bin，include .dll，重新開啟VS
- Configuration Properties -> C/C++ -> Preporocessor -> Preprocessor Definitions -> _CRT_SECURE_NO_WARNINGS