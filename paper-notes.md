## Efficient Multimodal Semantic Segmentation via Dual-Prompt Learning

基于双提示学习的高效多模态语义分割

这篇题为“Efficient Multimodal Semantic Segmentation via Dual-Prompt Learning”的论文提出了一种名为DPLNet的新方法，用于训练高效的多模态语义分割。现有的多模态语义分割方法通常需要使用复杂的特征融合策略对双分支编码器-解码器框架进行全面微调，这在计算上是昂贵的。相比之下，DPLNet 直接将冻结的预训练 RGB 模型适应多模态语义分割，从而减少了参数更新。它引入了两个提示学习模块，即多模态提示生成器 （MPG） 和多模态特征适配器 （MFA），以融合来自不同模态的特征，并在冻结的骨干中适应提示的多模态特征。DPLNet 在四个 RGB-D/T 语义分割数据集上实现了最先进的性能，同时具有参数效率。它也适用于其他多模态任务，如显著目标检测和视频语义分割。所提出的方法训练高效、部署友好，并且对多模态语义分割有效。 

大意： 

现有的多模态语义分割方法在计算上成本很高，因为需要对具有复杂特征融合的双分支编码器-解码器框架进行全面微调。 

DPLNet 将冻结的预训练 RGB 模型直接适应多模态语义分割，从而减少参数更新。 

DPLNet 引入了两个提示学习模块，即多模态提示生成器 （MPG） 和多模态特征适配器 （MFA），以融合不同模态的特征，并在冻结的骨干网中适配提示的多模态特征。 

DPLNet 在四个 RGB-D/T 语义分割数据集上实现了最先进的性能，同时具有参数效率。 - DPLNet适用于其他多模态任务，如显著目标检测、视频语义分割等。





























