# outfit-anyone
[English](https://github.com/YeatsLiao/outfit-anyone/blob/main/README.md)  | [简体中文](https://github.com/YeatsLiao/outfit-anyone/blob/main/README_CN.md)

Outfit Anyone（最新修复版）：适用于任何服装和任何人的超高品质虚拟试穿

Outfit Anyone 的模型实际上并未开源，这个项目只是一个调用接口的客户端，模型是固定的，不能上传或修改，只支持用户上传自己的服装，生成图片。

## 如何运行

**测试环境:**  **Python 3.10(ubuntu22.04 RTX 4090)**

拉取或下载代码

```
git clone https://github.com/ihmily/outfit-anyone.git
```

安装依赖

```
cd outfit-anyone
pip install -r requirements.txt
```

**Linux环境下设置环境变量（重点）**

```
export OA_IP_ADDRESS=https://humanaigc-outfitanyone.hf.space/--replicas/5eyuf/
```

**Windows环境下设置环境变量（重点）**
```
set OA_IP_ADDRESS=https://humanaigc-outfitanyone.hf.space/--replicas/adoil/
```

运行

```
python app.py
```

启动成功后，web服务运行在6006端口。你将看到以下类似信息

```
API: https://humanaigc-outfitanyone.hf.space/--replicas/5eyuf/
Loaded as API: https://humanaigc-outfitanyone.hf.space/--replicas/5eyuf/ ✔
Running on local URL:  http://127.0.0.1:6006
```

如果 `OA_IP_ADDRESS` 失效导致无法正常运行，请联系我更新 

或者 访问[OutfitAnyone - a Hugging Face Space by HumanAIGC](https://huggingface.co/spaces/HumanAIGC/OutfitAnyone) 自行获取。

将API地址填入 `app.py` 中的 `OA_IP_ADDRESS` 变量中。

![Snipaste_2024-05-25_20-32-01.png](images%2FSnipaste_2024-05-25_20-32-01.png)

![Snipaste_2024-05-25_20-30-53.png](images%2FSnipaste_2024-05-25_20-30-53.png)


## 演示结果

![screenshot_image](./images/Snipaste_2024-04-18_19-06-02.jpg)

![screenshot_image](./images/Snipaste_2024-04-18_19-13-52.jpg)

![screenshot_image](./images/Snipaste_2024-04-18_19-11-35.jpg)



