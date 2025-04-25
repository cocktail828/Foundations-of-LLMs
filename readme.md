<h1 align="center">大模型基础</h1>


<div align="center"> 
  <img src=".\figure\cover.png" style="width: 50%">
</div>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue">
  <img src="https://img.shields.io/github/stars/ZJU-LLMs/Foundations-of-LLMs?style=social">
  <img src="https://img.shields.io/github/forks/ZJU-LLMs/Foundations-of-LLMs?style=social">
<!--   <img src="https://img.shields.io/github/license/ZJU-LLMs/Foundations-of-LLMs"> -->
</p>

本书旨在为对大语言模型感兴趣的读者系统地讲解相关基础知识、介绍前沿技术。作者团队将认真听取开源社区以及广大专家学者的建议，持续进行**月度更新**，致力打造**易读、严谨、有深度**的大模型教材。并且，本书还将针对每章内容配备相关的**Paper List**，以跟踪相关技术的**最新进展**。

本书第一版包括**传统语言模型**、**大语言模型架构演化**、**Prompt工程**、**参数高效微调**、**模型编辑**、**检索增强生成**等六章内容。为增加本书的易读性，每章分别以**一种动物**为背景，对具体技术进行举例说明，故此本书以六种动物作为封面。当前版本所含内容均来源于作者团队对相关方向的探索与理解，如有谬误，恳请大家多提issue，多多赐教。后续，作者团队还将继续探索大模型推理加速、大模型智能体等方向。相关内容也将陆续补充到本书的后续版本中，期待封面上的动物越来越多。

当前完整的本书PDF版本路径为<a href="https://github.com/ZJU-LLMs/Foundations-of-LLMs/blob/main/%E3%80%8A%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80%E3%80%8B%E6%95%99%E6%9D%90/%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80%20%E5%AE%8C%E6%95%B4%E7%89%88.pdf">大模型基础.pdf</a>。另外，我们还提供了两个文件夹，<a href="https://github.com/ZJU-LLMs/Foundations-of-LLMs/tree/main/%E3%80%8A%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80%E3%80%8B%E6%95%99%E6%9D%90/%E3%80%8A%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80%E3%80%8B%E5%88%86%E7%AB%A0%E8%8A%82%E5%86%85%E5%AE%B9">大语言模型分章节内容</a>文件夹中包含了各章节的PDF版本。而<a href="https://github.com/ZJU-LLMs/Foundations-of-LLMs/tree/main/%E5%A4%A7%E6%A8%A1%E5%9E%8B%E7%BB%8F%E5%85%B8%E8%AE%BA%E6%96%87%E5%88%97%E8%A1%A8">大语言模型相关论文</a>文件夹中包含了各章节的相关论文，当前正处于不断更新中。

其中每个章节的内容目录如下表所示。

## 本书目录

<table>
    <tr>
        <th style="text-align:center; width: 25%;">章节</th>
        <th style="text-align:center; width: 75%;" colspan="3">所含内容</th>
    </tr>
    <tr>
        <td rowspan="2"><b><a href="https://github.com/ZJU-LLMs/Foundations-of-LLMs/blob/main/%E3%80%8A%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80%E3%80%8B%E6%95%99%E6%9D%90/%E3%80%8A%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80%E3%80%8B%E5%88%86%E7%AB%A0%E8%8A%82%E5%86%85%E5%AE%B9/%E7%AC%AC1%E7%AB%A0%20%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80.pdf">第 1 章：语言模型基础</a></b></td>
        <td style="width: 25%;">1.1 基于统计方法的语言模型</td>
        <td style="width: 25%;">1.2 基于 RNN 的语言模型</td>
        <td style="width: 25%;">1.3 基于 Transformer 的语言模型</td>
    </tr>
    <tr>
        <td>1.4 语言模型的采样方法</td>
        <td>1.5 语言模型的评测</td>
        <td></td>
    </tr>
    <tr>
        <td rowspan="2"><b><a href="https://github.com/ZJU-LLMs/Foundations-of-LLMs/blob/main/%E3%80%8A%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80%E3%80%8B%E6%95%99%E6%9D%90/%E3%80%8A%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80%E3%80%8B%E5%88%86%E7%AB%A0%E8%8A%82%E5%86%85%E5%AE%B9/%E7%AC%AC2%E7%AB%A0%20%E5%A4%A7%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E6%9E%B6%E6%9E%84.pdf">第 2 章：大语言模型</a></b></td>
        <td>2.1 大数据 + 大模型 → 新智能</td>
        <td>2.2 大语言模型架构概览</td>
        <td>2.3 基于 Encoder-only 架构的大语言模型</td>
    </tr>
    <tr>
        <td>2.4 基于 Encoder-Decoder 架构的大语言模型</td>
        <td>2.5 基于 Decoder-only 架构的大语言模型</td>
        <td>2.6 非 Transformer 架构</td>
    </tr>
    <tr>
        <td rowspan="2"><b><a href="https://github.com/ZJU-LLMs/Foundations-of-LLMs/blob/main/%E3%80%8A%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80%E3%80%8B%E6%95%99%E6%9D%90/%E3%80%8A%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80%E3%80%8B%E5%88%86%E7%AB%A0%E8%8A%82%E5%86%85%E5%AE%B9/%E7%AC%AC3%E7%AB%A0%20Prompt%20%E5%B7%A5%E7%A8%8B.pdf">第 3 章：Prompt 工程</a></b></td>
        <td>3.1 Prompt 工程简介</td>
        <td>3.2 上下文学习</td>
        <td>3.3 思维链</td>
    </tr>
    <tr>
        <td>3.4 Prompt 技巧</td>
        <td>3.5 相关应用</td>
        <td></td>
    </tr>
    <tr>
        <td rowspan="2"><b><a href="https://github.com/ZJU-LLMs/Foundations-of-LLMs/blob/main/%E3%80%8A%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80%E3%80%8B%E6%95%99%E6%9D%90/%E3%80%8A%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80%E3%80%8B%E5%88%86%E7%AB%A0%E8%8A%82%E5%86%85%E5%AE%B9/%E7%AC%AC4%E7%AB%A0%20%E5%8F%82%E6%95%B0%E9%AB%98%E6%95%88%E5%BE%AE%E8%B0%83.pdf">第 4 章：参数高效微调</a></b></td>
        <td>4.1 参数高效微调简介</td>
        <td>4.2 参数附加方法</td>
        <td>4.3 参数选择方法</td>
    </tr>
    <tr>
        <td>4.4 低秩适配方法</td>
        <td>4.5 实践与应用</td>
        <td></td>
    </tr>
    <tr>
        <td rowspan="2"><b><a href="https://github.com/ZJU-LLMs/Foundations-of-LLMs/blob/main/%E3%80%8A%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80%E3%80%8B%E6%95%99%E6%9D%90/%E3%80%8A%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80%E3%80%8B%E5%88%86%E7%AB%A0%E8%8A%82%E5%86%85%E5%AE%B9/%E7%AC%AC5%E7%AB%A0%20%E6%A8%A1%E5%9E%8B%E7%BC%96%E8%BE%91.pdf">第 5 章：模型编辑</a></b></td>
        <td>5.1 模型编辑简介</td>
        <td>5.2 模型编辑经典方法</td>
        <td>5.3 附加参数法：T-Patcher</td>
    </tr>
    <tr>
        <td>5.4 定位编辑法：ROME</td>
        <td>5.5 模型编辑应用</td>
        <td></td>
    </tr>
    <tr>
        <td rowspan="2"><b><a href="https://github.com/ZJU-LLMs/Foundations-of-LLMs/blob/main/%E3%80%8A%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80%E3%80%8B%E6%95%99%E6%9D%90/%E3%80%8A%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%9F%BA%E7%A1%80%E3%80%8B%E5%88%86%E7%AB%A0%E8%8A%82%E5%86%85%E5%AE%B9/%E7%AC%AC6%E7%AB%A0%20%E6%A3%80%E7%B4%A2%E5%A2%9E%E5%BC%BA%E7%94%9F%E6%88%90.pdf">第 6 章：检索增强生成</a></b></td>
        <td>6.1 检索增强生成简介</td>
        <td>6.2 检索增强生成架构</td>
        <td>6.3 知识检索</td>
    </tr>
    <tr>
        <td>6.4 生成增强</td>
        <td>6.5 实践与应用</td>
        <td></td>
    </tr>
</table>

## 致谢
本书的不断优化，将仰仗各位读者的帮助与支持。您的建议将成为我们持续向前的动力！
所有提出issue的人，我们都列举在此，以表达我们深深的谢意。
