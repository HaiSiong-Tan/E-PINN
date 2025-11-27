## E-PINN

Evidential Physics-Informed Neural Networks (E-PINN) : a couple of illustrative examples

#### 📘 Contents

<small> 
This repository includes:
  
- **EPINN_poisson.ipynb** – An application of E-PINN to Poisson equation with Gaussian source.
  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HaiSiong-Tan/E-PINN/blob/main/EPINN_case_studies/EPINN_poisson.ipynb)
- **EPINN_FisherKPP.ipynb** – An application of E-PINN to Fisher-KPP equation.
  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HaiSiong-Tan/E-PINN/blob/main/EPINN_case_studies/EPINN_FisherKPP.ipynb)
- **doc_epinn_poisson.pdf** – A short write-up providing some explanatory details for key methods and equations, ideally to be read alongside https://arxiv.org/abs/2509.14568
- **models** - folder containing some pretrained models and related objects for reference.

All notebooks are written for **Google Colab**. 
</small>

#### 🚀 Getting Started

 - **Opening in Google Colab** -
simply upload the notebooks and the 'models' folder to Colab and run them as-is.
 - **Running Locally** -
if you prefer running locally, install the required packages:

```bash
pip install numpy scipy matplotlib numba torch
```
#### 💡 What is E-PINN?

<small>
E-PINN is a novel class of uncertainty-aware physics-informed neural networks. It leverages the marginal distribution loss function of evidential deep learning for estimating uncertainty of outputs, and infers unknown parameters of the PDE via a learned posterior distribution.

For full details, see the accompanying paper:
https://arxiv.org/abs/2509.14568
</small>


#### 👥 Authors

Hai Siong Tan, Kuancheng Wang and Rafe McBeth

#### 📝 License

This project is released under the MIT License.
