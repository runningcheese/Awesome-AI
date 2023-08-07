





## 一、Stable Diffusion




<br/>

### 1.1、SD 原理



更新中....



<br/>

### 1.2、SD 优势



目前主流的 AI 绘画工具： 



Midjourney、Stable Diffusion、DALL-E 2、Imagen 等，本质上都是基于 Diffusion 算法模型。



而自从 Midjourney 关闭免费通道后，Stable Diffusion 就成为了大多数人的首选。



因为免费，生成时间快，不用排队，没有生成数量的限制，不被 NSFW 约束，自由度高很多，还支持模型训练。



只要你有显卡，就能驾驭 SD。






<br/>


### 1.3、在线体验



这些在线应用，仅仅是提供简单检验，大部分为阉割版，不支持模型选择，不支持否定提示，不支持插件。



地址1：huggingface.co

https://huggingface.co/spaces/stabilityai/stable-diffusion



地址2：dreamstudio.ai

https://beta.dreamstudio.ai/generate



地址3：GRAVITI Diffus

https://www.diffus.graviti.com






<br/>


### 1.4、云服务器



硬件条件不行用户，还可以考虑使用 Google 云服务器，有一定的门槛，需要有一定的编程知识。



但 Google 已经宣布 Colab 不再支持免费的绘图生成了。



所以这个方法算是失效了。




<br/>


## 二、Windows 安装






<br/>


### 2.1、硬件要求



本地化部署运行虽然很好，但是也有一些基本要求。



1、需要 NVIDIA 显卡，GTX1060起，显存 4G 以上。

2、操作系统需要 Win10 或 Win11。

3、电脑内存 16G 以上。

4、最好要有魔法，否则容易网络波动，导致下载失败，甚至直接无法下载。





<br/>

### 2.2、Stable Diffusion WebUI



目前最爱欢迎的 Stable Diffusion 本地部署项目是 **Stable Diffusion WebUI**。



随时可玩，支持自己选择基础模型，支持 LoRA，支持 ControlNet，支持集成到 WebUI 的各种其他插件。



地址：https://github.com/AUTOMATIC1111/stable-diffusion-webui






<br/>


### 2.3、一键安装包



鉴于 Stable Diffusion WebUI 本地部署难度较大，于是有网友开发了一键配置包，解压即可使用。


其中比较知名的是“秋叶”一键安装包。



地址：https://www.bilibili.com/video/BV17d4y1C73R

下载：https://pan.baidu.com/s/1MnyQH_gWgVdxU1S_Hjc5JQ，提取码： t724 





<br/>

## 三、Mac 安装











<br/>

### 3.1、硬件要求



最好是 ARM 芯片，Intel 芯片也可以，但会慢很多。





<br/>

### 3.2、Diffusion Bee



优势：Mac 下有手就会用的 SD 应用。

不足：不支持中文，不支持 LoRA 模型。



地址：[https://diffusionbee.com](https://diffusionbee.com)

下载：[https://github.com/divamgupta/diffusionbee-stable-diffusion-ui](https://github.com/divamgupta/diffusionbee-stable-diffusion-ui) 

模型目录：在终端输入代码：open ~/.diffusionbee






<br/>


### 3.3、Draw Things



优势：支持中文、支持 LoRA 模型、支持 ControlNet、甚至还支持 iPhone、iPad 移动设备。

不足：不支持训练模型。



地址：[https://drawthings.ai](https://drawthings.ai)

下载：[https://apps.apple.com/us/app/id6444050820](https://apps.apple.com/us/app/id6444050820)

模型目录：/Users/你的用户名/Library/Containers/Draw Things/Data/Documents/Models



**设备兼容：**



Mac：M1/M2 芯片，macOS 12.4 以上系统、统一内存 32G 以上。

iPhone：iPhone XS 以上设备，iOS 15.4 以上系统。

iPad：iPadOS 15.4 及以上系统。





<br/>

### 3.4、Stable Diffusion WebUI



Draw Things 可能是 Mac 下最好的 SD 应用，唯一的缺点是不支持训练模型。



而 Mac 下没有 Stable Diffusion WebUI  那样的一键安装包，所以你需要手动安装，具体可参考官方项目。



地址：[https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Installation-on-Apple-Silicon](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Installation-on-Apple-Silicon)






<br/>


## 四、模型说明



<br/>

### 4.1、底模型


名称：Base Model、大模型、主模型、底模型

格式：.ckpt、.safetensors

大小：2G以上

作用：没有的话，SD 将无法工作，默认会下载 SD 1.5 模型。





<br/>

### 4.2、LORA 模型


更新中....



<br/>

### 4.3、其它模型


更新中....






<br/>


## 五、模型下载


<br/>

**模型下载：**

Civitai：https://civitai.com（目前最火的 SD 模型网站）
aigccafe：https://aigccafe.com（国内对 Civitai 的镜像网站，支持高速下载）

<br/>

**写实模型：**


ChilloutMix：东亚脸型
https://civitai.com/models/6424


娜乌斯嘉nwsj_realistic：LORA
https://civitai.com/models/53601



FilmGirl

https://civitai.com/models/33208



Deliberate：欧美脸型 character

https://civitai.com/models/4823



Realistic Vision：欧美脸型

https://civitai.com/models/4201


Protogen： (二次元)

https://civitai.com/models/3627



<br/>

**提示词网站：**

Novel AI Tag：https://wolfchen.top/tag

ClickPrompt：https://www.clickprompt.org/zh-CN/stable-diffusion-generator







<br/>


##  六、模型微调



更新中....



<br/>


## 七、模型训练

更新中....






<br/>


## 结尾 





