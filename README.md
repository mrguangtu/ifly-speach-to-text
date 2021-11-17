# ifly-speach-to-text

讯飞语音转写api调用的python脚本。买api包比直接买转写服务便宜哟~~
对比价格的时候，可以关注一下“有效期”以及“时长单价”。

[【讯飞开放平台】](https://www.xfyun.cn/services/lfasr#anchor4503211)
[【讯飞语音转文字】](https://www.iflyrec.com/html/addMachineOrder.html)

## 功能
非实时转写调用api完成语音MP3文件等转写成txt文本。

## 使用方法

去控制台找到下面的码，换成你自己的。
```
appid = "xxxx"
secret_key = "xxxxxxxx"
```


然后在命令行下输入

```python weblfasr_python3_demo.py [待转写的mp3文件]```


## 输出
生成带时间轴的文本段落，支持拆分不同角色，可通过speaker_number设置录音中说话人的数量。

