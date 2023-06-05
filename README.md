# auto-midjourney

midjourney 自动出图脚本

# 安装步骤

安装几个库文件

```
pip install pyautogui
pip install pandas
pip install openpyxl
pip install pyperclip
pip install pynput
```

# 使用步骤

安装上面的库后输入命令

```
python main.py
```

![image](https://github.com/lhwd521/auto-midjourney/assets/15196067/2527a4b5-cf06-4e22-ac72-eccf499ac340)

excel 第一列从上到下写入 midjourney 提示词

例如：/imagine prompt: A white cat playing in an autumn forest filled with red and yellow leaves, in the style of landscape photography--ar 9:16--v 5.1

填入间隔时间后，点确定鼠标位置，移动至 discord 输入栏后再次点击确定位置。点击开始即可开始任务。

搭配我制作的油猴自动切图与下载脚本使用更香。

油猴脚本网址：https://greasyfork.org/zh-CN/scripts/466277-discord%E4%B8%ADmidjourney%E8%87%AA%E5%8A%A8%E5%88%87%E5%9B%BE%E4%B8%8E%E4%B8%8B%E8%BD%BD

飞书详细操作文档：https://evnr5jw9no.feishu.cn/wiki/PP1mwJqePi9qaokW8BBcTfoJnUf

# 备注

1. windows 用户可直接在 dist 文件夹下载 main.exe 使用。也可运行main.py
2. 此程序是我与 GPT-4 一起完成，过程如下：https://sharegpt.com/c/6VyHGs7
3. 如果觉得还不错，可以请我喝杯咖啡（vx：laolu2045）。
4. mac用户请使用main_mac.py 注意：需要在系统设置>>隐私安全>>辅助功能 中把终端开启，否则会报错。 (感谢@動物兇猛 提供mac代码支持)

![image](https://github.com/lhwd521/auto-midjourney/assets/15196067/d7a826fb-bfaf-4fda-b30e-57da16a62719)
