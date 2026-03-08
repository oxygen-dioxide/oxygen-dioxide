# 如何在 Windows 上配置 python ReaScript 环境

1. 安装[Reaper](https://www.reaper.fm/download.php)和[Python](https://www.python.org/)
2. 在Reaper的 Options -> Preferences -> Python 中：
  - “Custom path to python dll”填python.exe所在的文件夹路径
  - “Force ReaScript to use specific Python .dll”填该文件夹中带有python版本号的dll（例如python312.dll），只包括文件名，不包括路径

现在你应该可以在Reaper的 Actions -> Show Action List -> New action -> New ReaScript 中创建python ReaScript
