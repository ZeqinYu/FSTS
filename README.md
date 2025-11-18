# FSTS 
Official implementation of Fourier Series-based Tampering Synthesis (FSTS) from our NeurIPS 2025 paper “[Toward Real-world Text Image Forgery Localization: Structured and Interpretable Data Synthesis](https://arxiv.org/abs/2511.12658)”.

> 🌍 **Future FSTS Development**  
> The FSTS dataset has been primarily developed through self-funded effort. We are now preparing **FSTS vX**, with expanded scale and richer tampering diversity. If you are interested in **supporting or collaborating**, please reach out: kimjyu@foxmail.com.  

## 📰 News
* **[2025.11.18]** 🚀 We have released the [arXiv version](https://arxiv.org/abs/2511.12658), with additional experiments and analyses included in the appendix.
* **[2025.11.14]** 🚀 The FSTS dataset is publicly available on the following platforms: [Hugging Face](https://huggingface.co/datasets/Zegkim/FSTS).
* **[2025.11.07]** 🔥 We have released video samples that showcase the implementation pipeline of FSTS.


<details open>
<summary>✨ We also have other Text Image Forgery Forensics projects that may interest you</summary>
<p>

> [**Reinforced Multi-teacher Knowledge Distillation for Efficient General Image Forgery Detection and Localization (AAAI 2025 Oral)**](https://arxiv.org/abs/2504.05224) <br>
> Zeqin Yu, Jiangqun Ni, Jian Zhang, Haoyi Deng, Yuzhen Lin <br>
> 🏆 **This method achieved [1st Place](https://github.com/ZeqinYu/ICCV-DeepID2025-Sunlight)** in both **Detection Track** and **Localization Track** of the **[ICCV 2025 DeepID Challenge](https://deepid-iccv.github.io/)**. <br>

> [**Learning to Locate the Text Forgery in Smartphone Screenshots (ICASSP 2023)**](https://ieeexplore.ieee.org/abstract/document/10095070) <br>
> Zeqin Yu, Bin Li, Yuzhen Lin, Jinhua Zeng, Jishen Zeng <br>
> 📌 This work introduced the first real-world screenshot forgery dataset,  which was later adopted in the [“2022 Real-World Image Forgery Detection Challenge” (真实场景篡改图像检测挑战赛)](https://tianchi.aliyun.com/competition/entrance/531945). <br>

</p>
</details>


## 🧩 Examples of FSTS Synthesis Process
Below are several examples (slow version) showing the *automatic synthesis pipeline* of FSTS, which collects and models real-world tampering parameters to synthesize samples with the _replacement_ operation.

### Example1
https://github.com/user-attachments/assets/d627d363-8983-44f4-affe-0b87f9ea7343


### Example2
https://github.com/user-attachments/assets/062d52df-9823-4b7d-a685-48b1f53ae90b


### Example3
https://github.com/user-attachments/assets/d31570d1-694a-4a76-af18-a51f59d45d85

## ✍️ Citation
```bibtex
@inproceedings{yutoward,
  title={Toward Real-world Text Image Forgery Localization: Structured and Interpretable Data Synthesis},
  author={Yu, Zeqin and Xie, Haotao and Zhang, Jian and Ni, Jiangqun and Su, Wenkang and Huang, Jiwu},
  booktitle={The Thirty-ninth Annual Conference on Neural Information Processing Systems Datasets and Benchmarks Track}
}
