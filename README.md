
# 人体跌倒检测
---
### 目录s 

- [描述](#描述)
- [如何使用](#如何使用)
- [方法](#方法s)
- [参考文献](#参考文献)
- [作者信息](#作者信息)

---

## 描述 

这里的目标是开发一个可靠的跌倒检测系统。因为这对老年人来说是最危险的问题之一。它是受伤、丧失行动能力、害怕跌倒甚至死亡的根源...我们不是在阻止下跌，而是在增加我们对下跌的反应。使用人检测和跌倒分类，这种方法解决了端到端的跌倒检测问题。人物检测算法旨在定位图像中的所有人物。它的输出是封闭的边界框和反映这些框包含人的可能性的置信度得分。跌倒分类估计被检测人是否跌倒。该模型是在坠落者数据集(FPDS)上使用yolov5s训练。
FPDS数据集地址： http://agamenon.tsc.uah.es/Investigacion/gram/papers/fall_detection/FPDS_dataset.zip.


#### 技术
- Yolov5 (Pytorch)
- Repvgg
- Picodet

## 如何使用
