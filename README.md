# 每日论文阅读记录

### <font color=Green> Daily Reading</font>

> [2023-3-13]- [A $^3$ lign-DFER: Pioneering Comprehensive Dynamic Affective Alignment for Dynamic Facial Expression Recognition with CLIP]-[Arxiv](https://arxiv.org/abs/2403.04294)
>  
> > 论文框架图（有助于一眼就能想起论文内容）
> > 论文简述：
> > 在CLIP的基础上，提出多个模块，从affective, dynamic和bidirectional三个角度实现了动态情感对齐，达到了较高的performance。在vision-language模型里达到了SOTA。 冻结了了CLIP的预训练模型


> [2023-3-14] 
> “emotion2vec: Self-Supervised Pre-Training for Speech Emotion Representation” ([Ma 等, 2023, p. 1](zotero://select/library/items/7VRD2MS6)) ([pdf](zotero://open-pdf/library/items/JDD3XVM9?page=1&annotation=58YPEKMD))
> > 论文框架图（有助于一眼就能想起论文内容）
> > 论文简述：
> > 自监督预训练模型用于语音情绪识别, 在下游多个数据集上面达到了 sota

> [2023-3-17]  OmniVec: Learning robust representations with cross modal sharing
> ![image](https://github.com/cyinen/paper-readings/assets/56926538/5d04a9f8-e7a9-423c-bad9-69c54edf98cf)

>> 提出了一个统一的模型架构，将多种模态的数据编码到同一个向量空间（OmniVec）
输入是不同的模态，使用不同的 encoder编码，后续使用同一个框架将各种模态数据编码到同一向量空间。在下游各种任务上达到了 SOTA。


### <font color=Green> Image + Video pretrain for downstream tasks</font>
&nbsp;
> EVT: BERT Pretraining of Video Transformers (CVPR 2022)
> ![image](https://github.com/ReadingPapers/Report/assets/56926538/36d9776b-43a1-4336-b2d9-c71a30b0e2ad)
>> 描述: 将 BERT-Style 预训练的方式扩展到了Video task, 将视频表征学习解耦成空间学习和时间学习，预测 target 仿照 bert 预测 visual tokens

&nbsp;
> OmniMAE: Single Model Masked Pretraining on Images and Videos (CVPR 2023)
> ![image](https://github.com/ReadingPapers/Report/assets/56926538/694379e1-da39-4d82-b6cd-4fd7f9494ad5)
>> 描述: 提出了统一的编码器解码器，一个模型可以接受图像或者视频的输入，使用 Image+Video 预训练可以使用极高的掩码率（iamge:90%, video:95%), 提升了下游任务的性能

&nbsp;
> ViC-MAE: Self-Supervised Representation Learning from Images and Video with Contrastive Masked Autoencoders 
> ![image](https://github.com/ReadingPapers/Report/assets/56926538/2aa9cfc7-6816-4c1b-9d3d-0696946edcd2)
>> 描述:  加入了对比学习，进一步提升了模型的表征能力，同时在 Image 和 video相关的 task上达到 sota 性能



######### 模版 #############

[日期]-[总结人]-[论文标题]-[来源]（附带链接，链接可选）

论文框架图（有助于一眼就能想起论文内容）

论文简述 （一两句话总结精华，切勿过长）

######### 模版 #############
