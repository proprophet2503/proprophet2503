# Jeremy Mattathias Mboe

**AI Engineering student at Institut Teknologi Sepuluh Nopember (ITS), Surabaya, Indonesia.**

I build machine learning systems where the method is the hard part: physics-informed inverse problems for medical imaging, generative models for speech, and reliable inference backends. I usually implement a method from scratch in PyTorch before I reach for a library wrapper.

**Portfolio:** [proprophet2503.github.io/portofolioJeremy](https://proprophet2503.github.io/portofolioJeremy/). Each featured project there has an interactive, in-browser figure of how the method works.

## Now

- **Research Assistant**, Diagnostic and Prognostic Laboratory (AI Division), ITS: tuberculosis screening from cough audio and 3D lung reconstruction from plain X-rays.
- **Laboratory Assistant**, Intelligent Computing and Vision Laboratory, ITS: kidney cyst segmentation with clinicians from Rumah Sakit Universitas Airlangga.
- **Teaching Assistant** for Probability & Statistics, Machine Learning and Data Mining.

## Selected work

Full write-ups and figures are on the [portfolio](https://proprophet2503.github.io/portofolioJeremy/#work).

| Project | What it does | Built with |
|---|---|---|
| **Physics-informed 3D lung reconstruction** | Reconstructs a 3D CT volume from three plain X-rays (AP, PA, lateral), so TB screening does not need a CT scanner. | PINN, Neural Attenuation Fields, Beer-Lambert law, PyTorch |
| **[AVID-MM](https://github.com/proprophet2503/AVID-MM-Audio-Visual-Identity-Disentanglement-for-Missing-Modality-Speaker-Identification)** | Cross-modal speaker verification that keeps working when the audio or the face is missing. Raised accuracy from 59% to over 93% on the POLY_1 challenge setup. | ECAPA-TDNN, AAM-Softmax, modality dropout, PyTorch |
| **SwaraTTS** | Low-latency speech synthesis with latent flow matching, built with a research team at Avalon AI × RISTEK UI. | Flow matching, score-based diffusion, PyTorch |
| **Neuromorphic vision, no SNN framework** | Spiking neural network with Izhikevich neurons and custom surrogate gradients, trained with plain PyTorch autograd. 76.6% accuracy on N-MNIST. | SNN, custom autograd, PyTorch |
| **[TB cough screening](https://github.com/proprophet2503/TB-Cough-Detection-Model)** | Classifies cough recordings for TB indication with an LSTM on MFCC features. 1st Place & Best Scientific Paper, National Electrolympic UPNVJ 2025. | Signal processing, MFCC, LSTM, PyTorch |
| **[EEG screening for ALS](https://github.com/proprophet2503/EEG_BinaryEncoding)** | End-to-end signal pipeline that separates ALS subjects from controls across 1,809 clinical EDF recordings. | EEG, feature engineering, scikit-learn |
| **TB meningitis mortality model** | XGBoost model for three-month mortality risk (AUROC 0.825), with an interpretable 8-feature logistic surrogate (AUROC 0.815). e-Poster at the ASEAN4TB Conference 2026. | XGBoost, SHAP, decision curve analysis |
| **REXTRA LLM inference backend** | REST API layer for LLM inference with request routing, retries and failover across model providers. | REST APIs, Docker, Linux |

**Also built:** oil palm health detection from drone imagery (YOLOv8s, ResNet-18, NDVI, Gradio on Hugging Face Spaces); tilapia disease classification with a CBAM-attention CNN (Top 50, Innovillage by Telkom Indonesia); CodeSight, a tool that turns physical flowchart blocks into code for visually impaired learners (YOLOv8); and ROS/C++ robot control at IRIS ITS.

## Toolbox

- **ML and research:** PyTorch, TensorFlow, Hugging Face, scikit-learn, XGBoost, OpenCV, YOLO
- **Methods:** score-based diffusion, flow matching, physics-informed neural networks, spiking neural networks, multimodal learning
- **Engineering:** Python, C++, JavaScript, SQL, PostgreSQL, Docker, Linux, Git, REST APIs

## Recognition

- 1st Place & Best Scientific Paper, National Electrolympic, Universitas Pembangunan Nasional Veteran Jakarta (2025)
- Top 50 Social Project, Innovillage, Telkom Indonesia
- e-Poster presenter, ASEAN4TB Conference (2026)

## Connect

[Portfolio](https://proprophet2503.github.io/portofolioJeremy/) · [LinkedIn](https://www.linkedin.com/in/jeremymboe/) · [Kaggle](https://www.kaggle.com/jeremymattathiasmboe) · [Hugging Face](https://huggingface.co/jeremymboe) · jeremymattathiasmboe@gmail.com

Open to research collaborations in medical AI, generative models and inverse problems.
