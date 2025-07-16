# Three_stage_former_for_ECG

A lightweight and efficient multi-scale transformer model, especially suitable for multi-channel time-sequential data classification like ECG signals!  
This paper was accepted by MIDL 2025 as a short paper. Feel free to check more details in our 📄 Paper

📌 Check out our paper:  
**[Hierarchical Transformer for Electrocardiogram Diagnosis](https://arxiv.org/abs/2411.00755)**  
→ [https://arxiv.org/abs/2411.00755](https://arxiv.org/abs/2411.00755)

---
To reproduce our results on the PhysioNet2020 Challenge data, you may need to download their data from their **[website](https://moody-challenge.physionet.org/2020/)** .
Our model is built upon the champion **['prna'](https://www.cinc.org/archives/2020/pdf/CinC2020-107.pdf)** of the PhysioNet2020 Challenge, a plain transformer architecture. Thanks to their great pioneering work.
## 🛠 Environment Setup

To run our model, please create the conda environment using the provided `environment.yml`:

```bash
conda env create -f environment.yml
conda activate prna-oldlib


---
## 📚 Citation

If you find this repository useful, please consider giving a star ⭐ and citing our work 🩺:

```bibtex
@article{tang2024hierarchical,
  title={Hierarchical Transformer for Electrocardiogram Diagnosis},
  author={Tang, Xiaoya and Berquist, Jake and Steinberg, Benjamin A and Tasdizen, Tolga},
  journal={arXiv preprint arXiv:2411.00755},
  year={2024}
}
