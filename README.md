
# 开始
以下均为cpu推理

## 目标检测

![](images/det.gif)

## 跟踪

![](images/track.gif)

## 人脸检测和关键点

![](images/face_det.gif)

## 分割

![](images/human_seg.gif)

## 增强

![](images/enhance.gif)

## 文本分类

![](images/text_cls.gif)

## 文本生成图片

![](images/txt2img.gif)

## 文本生成语音

![](images/txt2wav.gif)

## k8s
k8s管理服务
![](images/k8s.gif)

## one-api中转集成LLM和embedding
集成LLM模型封装成统一API，并使用该one-api进行对话。包含m3e生成向量，向量库匹配获取得分和排名。
![](images/one-api.gif)

## LLM Agent
LLM充当Agent角色，根据user输入执行不同的指令完成任务。
![](images/agent.gif)

参考以下这位大佬的代码，改成使用本地LLM，而非openai。搜索引擎和天气等信息需要自行申请api，集成到Agent。
> [B站: 爱的生命只有82分钟，我要给她完整的一生😭](https://www.bilibili.com/video/BV1md4y1Z7pj/?spm_id_from=333.999.0.0&vd_source=afa6a4d92a2a676ee929209b5bb17202)

## 异步stream和本地知识库
关联本地知识库，并使用异步接收每个字token，进而打印输出。
![](images/async-stream.gif)

## grpc
![](images/grpc.gif)
可ghz进行压测