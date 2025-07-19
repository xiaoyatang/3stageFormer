# Three_stage_former_for_ECG

A lightweight and efficient multi-scale transformer model, especially suitable for multi-channel time-sequential data classification like ECG signals!  
This paper was accepted by MIDL 2025 as a short paper. Feel free to check more details in our 📄 Paper

📌 Check out our paper:  
**[Hierarchical Transformer for Electrocardiogram Diagnosis](https://arxiv.org/abs/2411.00755)**  
→ [https://arxiv.org/abs/2411.00755](https://arxiv.org/abs/2411.00755)

---
Our model is built upon the champion **['prna'](https://www.cinc.org/archives/2020/pdf/CinC2020-107.pdf)** of the PhysioNet2020 Challenge, a plain transformer architecture. Thanks to their great pioneering work.
## 📁 `feats` Directory Setup

To reproduce our results on the PhysioNet2020 Challenge data, you need to download their data from their **[website](https://moody-challenge.physionet.org/2020/)** , **OR** follow the instructions below.

### 🔽 Step 1: Download Required Files

Download the required folders from the shared Google Drive link:

👉 [Download feats folders from Google Drive](https://drive.google.com/drive/folders/1XWfkR159jWJCcC6jJ9DQECq4XV-of8JG?usp=sharing)

Simply place the downloaded folders inside a local directory named `feats`.

---

### 📂 Step 2: Directory Structure

Your `feats/` directory should look like this:
```text
feats/
├── CPSC-Extra/
├── Georgia/
├── PTB/
├── PTB-XL/
├── StPetersburg/
├── pyeeg/
├── utils/
├── __init__.py
├── dataset.py
├── feature_map.py
├── get_feats.py
└── signal_process.py
```text

## 🛠 Environment Setup

To run our model, please create the conda environment using the provided `environment.yml`:

```bash
conda env create -f environment.yml -n your_env_name
conda activate your_env_name


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
