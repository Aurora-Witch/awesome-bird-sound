# 🐦 Awesome Bird Sound Recognition

一个专为鸟鸣识别研究者（特别是生物专业+计算机背景）整理的高质量资源列表，涵盖论文、代码工具、数据集和研究方向建议。

---

## 📘 学习综述与教程类论文

- **Stowell et al. (2019)**  
  [Automatic acoustic detection of birds through deep learning](https://arxiv.org/abs/1807.05812)  
  ⏳ 鸟鸣识别挑战赛和深度学习方法的综述文章，推荐入门者阅读。

- **Kahl et al. (2021)**  
  [BirdNET: A deep learning solution for avian diversity monitoring](https://doi.org/10.1002/ece3.7123)  
  ✅ 康奈尔大学的 BirdNET 系统介绍，含模型架构、数据策略和部署方法。

- **Priyadarshani et al. (2018)**  
  [Automated birdsong recognition in complex acoustic environments: a review](https://doi.org/10.1016/j.ecoinf.2018.03.003)  
  🔍 讨论鸟鸣识别在噪声环境下的挑战和方法综述。

---

## 🧠 方法进展论文（深度学习、特征提取）

- **Morfi & Stowell (2018)**  
  [Deep learning for audio event detection and tagging on low-resource datasets](https://arxiv.org/abs/1803.07435)

- **Lostanlen et al. (2019)**  
  [Per-channel energy normalization: Why and how](https://arxiv.org/abs/1910.11436)  
  📌 强烈推荐，介绍 PCEN 特征，对鸟鸣识别在噪声背景下特别有效。

- **Kahl et al. (2021)**  
  [A modular deep learning architecture for bird sound classification](https://arxiv.org/abs/2008.03892)

---

## 📊 数据集与挑战赛

- **[BirdCLEF Challenge (2014–2024)](https://www.imageclef.org/lifeclef/2024/bird)**  
  📂 每年更新的大型鸟鸣识别比赛，数据真实、多标签复杂。

- **[Xeno-Canto](https://www.xeno-canto.org/)**  
  🐦 最大的开放鸟鸣数据平台，用户上传，种类丰富，常用于研究。

- **[Warblr dataset](https://doi.org/10.5281/zenodo.4005064)**  
  来自英国的城市鸟类音景数据集。

---

## 🔧 实用工具 & GitHub 项目

- **[BirdNET-Analyzer](https://github.com/kahst/BirdNET-Analyzer)**  
  📡 康奈尔大学开源的鸟鸣检测工具，支持推理、批处理和地图定位。

- **[PANNs (Pretrained Audio Neural Networks)](https://github.com/qiuqiangkong/audioset_tagging_cnn)**  
  🎧 高质量的预训练模型，可用于迁移学习与特征提取，适配 log-mel、waveform。

- **[OpenSoundscape](https://github.com/kitzeslab/opensoundscape)**  
  🧰 生态学家友好的音频分类工具包，支持自定义训练。

---

## 📚 应用类研究方向（生态保护、栖息地监测）

- **Wood et al. (2021)**  
  _Bird species recognition in soundscapes using CNNs_  
  ➤ 探讨如何在自然音景（Soundscape）中识别多物种。

- **Stowell et al. (2022)**  
  _Bird population monitoring through passive acoustic surveys_  
  ➤ 声景分析 + 长期监测，适合生态学背景研究者。

---

## 🛠️ 实验建议方向（研究生选题参考）

1. **使用 PANNs + Fine-tune 进行物种分类迁移学习**  
2. **多标签识别：一个音频中多只鸟叫**  
3. **声景识别（Soundscape Detection）与物种丰富度估计**  
4. **弱监督学习：使用无标签或部分标签数据学习鸟类特征**  
5. **特征对比：MFCC、Log-mel、PCEN 哪种对鸟类更敏感？**

---

## 🙌 欢迎补充

如果你发现了新的优质资源、数据集或想分享自己的项目，欢迎提交 Pull Request！

---

