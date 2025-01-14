---
aside: false
---



我们提出了一个概念简单、灵活和通用的对象实例分割框架。我们的方法有效地检测图像中的对象，同时为每个实例生成高质量的分割掩码。该方法被称为Mask R-CNN，通过添加一个用于预测对象掩码的分支与用于边界框识别的现有分支并行，扩展了Faster R-CNN。面具R-CNN是简单的训练，只增加了少量的开销快速R-CNN，运行速度为5帧/秒。此外，Mask R-CNN很容易推广到其他任务，例如，允许我们在相同的框架下估计人体姿势。我们展示了COCO挑战套件的所有三个方面的顶级结果，包括实例分割、边界框对象检测和人员关键点检测。在没有技巧的情况下，Mask R-CNN在每项任务上都超越了所有现有的单模型条目，包括COCO 2016挑战赛的获胜者。我们希望我们简单而有效的方法将作为一个坚实的基线，并有助于简化未来在实例级识别方面的研究。代码将被提供。

<iframe src="/papers/mask_rcnn.pdf" width="100%" height="700"> </iframe>

[下载链接](/papers/mask_rcnn.pdf)