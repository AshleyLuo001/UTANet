
<div align=center>
<h1> UTANet: Task-Adaptive Mixture of Skip Connections for Enhanced Medical Image Segmentation</h1>
<h4 align="center">
  
[Zichen Luo](https://github.com/AshleyLuo001)<sup>1</sup>,
Xinshan Zhu<sup>1</sup>,
Lan Zhang<sup>1</sup>,
Biao Sun<sup>1</sup>


<sup>1</sup>Tianjin University

</h4>
  <a href="" style="margin: 2px;">
    <img alt="Code License" src="https://img.shields.io/badge/Code_License-MIT-f5de53?&color=f5de53" style="display: inline-block; vertical-align: middle;"/>
  </a>

</div>
<div align=center>
Made with ❤️ by <b>Ashley</b> | PhD @ Tianjin University 
  <br>
  🧠 Medical AI · 🧬 Quantum Learning · 🧩 GUI Agent& Computer Use
   <br>
</div>

## 🔥 News

* **`2025.05.22`** We update the TA-MoSC code in the utanet document, a plug-and-play module for U-shaed Architecture!

## ✨ Overview
![structure](./assets/architecture.png)

## 📌 Introduction
UTANet is a U-Net-based architecture enhanced with the **Task-Adaptive Mixture of Skip Connections (TA-MoSC)** module. By integrating the Mixture of Experts (MoE) framework into skip connections, our method dynamically aligns encoder-decoder features, addressing dataset-specific segmentation challenges. Key contributions include:

- **TA-MoSC**: Adaptive routing mechanism for multi-scale feature fusion.
- **Balanced Expert Utilization (BEU)**: Ensures balanced training of lightweight convolutional experts.
- **State-of-the-art Performance**: Outperforms existing methods on GlaS, MoNuSeg, Synapse, and ISIC16 datasets.

## 📌 TODO / Work in Progress

The following features and improvements are planned or in progress:

- [x] [2025.05.22] Add Model scripts. 
- [ ] Training framework
- [x] [2025.05.22] Implement TA-MoSC module
- [ ] Upload weight
- [ ] Add Jupyter notebook examples
- [ ] Add data preprocessing scripts
- [x] [2025.01.09] Add README.md.

## ✨Highlights
- **Dynamic Skip Connections**: Replaces fixed skip connections with task-adaptive expert mixtures.
- **Lightweight Design**: Minimal parameter overhead compared to vanilla U-Net.
- **Multi-Dataset Generalization**: Robust performance across diverse medical imaging tasks.
- **Code Efficiency**: Compatible with PyTorch and easy to integrate into existing U-Net variants.
  

## 🧠 TA-MoSC: Why It Works

> TA-MoSC learns to select relevant skip features dynamically across different tasks, allowing better specialization in edge cases such as:
>
> - 🔬 Tiny tumor detection  
> - 🧩 Irregular lesion boundaries  
> - 🧠 Low-contrast or noisy regions
>

## 🚀Quick Start
#### Installation
1. Clone the repository
```shell
git clone https://github.com/AshleyLuo001/UTANet.git  
cd UTANet
```
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Training

waiting...

## 📊Results
#### Performance on Medical Image Segmentation Datasets
waiting...







## 🛠️ Contributing

We welcome contributions! Please see [`CONTRIBUTING.md`](CONTRIBUTING.md) for instructions.



## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.






## 📜Citation
#### If you use UTANet in your research, please cite:
```bibtex
@article{luo2025rethinking,  
  title={Rethinking U-Net: Task-Adaptive Mixture of Skip Connections for Enhanced Medical Image Segmentation},  
  author={Luo, Zichen and Zhu, Xinshan and Zhang, Lan and Sun, Biao},  
  journal={AAAI},  
  year={2025}  
}
```


### ✨ Star this repo if you find it helpful!
