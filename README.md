### Hi there 👋

<img align='right' src="https://github-readme-stats.vercel.app/api?username=MSubasi1&show_icons=true">

# I'm Muhammet Subaşı

📍 Based in Turkey · interested in **machine learning, distributed systems, and applied cryptography**.

I'm a Computer Engineering graduate from **Hacettepe University**, currently pursuing my **MS in Computer Engineering** at the same university. My recent work spans kernel-level systems observability, filtered vector search for RAG, post-quantum cryptography, quantum-classical hybrid models, and reinforcement learning robustness. I enjoy turning messy data into something useful, reproducing and stress-testing published results, and I'm always happy to chat about a new project, a hard problem, or a good paper.

---

### 🔧 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)

**Machine Learning & Data**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**Systems & Specialized**

![eBPF](https://img.shields.io/badge/eBPF-FF6F00?style=for-the-badge&logo=linux&logoColor=white)
![OpenMP](https://img.shields.io/badge/OpenMP-A8B9CC?style=for-the-badge)
![OpenSSL](https://img.shields.io/badge/OpenSSL-721412?style=for-the-badge&logo=openssl&logoColor=white)
![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=for-the-badge&logo=qiskit&logoColor=white)
![Stable--Baselines3](https://img.shields.io/badge/Stable--Baselines3-blue?style=for-the-badge)

**Tools**

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

### 🎓 Graduate research projects

#### 🛰️ [QUIC-Performance-Monitoring-eBPF](https://github.com/Msubasi1/QUIC-Performance-Monitoring-eBPF)
Kernel-level QUIC observability framework using BCC/eBPF probes attached to UDP socket operations. Quantifies bandwidth, latency, and packet-loss impact on QUIC across five Mininet-simulated scenarios with **<0.5% CPU overhead** — latency dominates (52% throughput degradation at 50 ms RTT).
`C` · `Python` · `eBPF / BCC` · `Mininet` · `Quiche` · `Linux kernel`

#### 🔎 [Adaptive-Filtered-Vector-Search-RAG](https://github.com/Msubasi1/Adaptive-Filtered-Vector-Search-RAG)
Selectivity-aware query router for filtered vector search in RAG systems. Calibrates parametric cost and recall models for pre-, post-, and integrated filtering and routes each query to the optimal strategy — **Recall@10 = 0.999 with 89.5% oracle match** across 275 filters on a 650K arXiv subset.
`Python` · `HNSW (hnswlib)` · `Sentence-Transformers` · `PyTorch` · `SciPy`

#### ⚛️ [Quantum-GAN-vs-Classical-GAN](https://github.com/Msubasi1/Quantum-GAN-vs-Classical-GAN)
Hybrid quantum-classical GAN that replaces the classical generator with parameterized variational quantum circuits (4 / 6 / 8 qubits). On CIFAR-10 the **6-qubit QGAN achieves FID = 0.32 vs classical 0.49** (−35%); every QGAN configuration beats classical Inception Score.
`PyTorch` · `Qiskit Aer` · `IBM Quantum Runtime` · `torchmetrics`

#### 🔐 [Post-Quantum-Cryptography-TLS](https://github.com/Msubasi1/Post-Quantum-Cryptography-TLS)
From-scratch TLS 1.3 server and client in C using OpenSSL 3.0.8 with the OQS Provider for post-quantum key encapsulation (ML-KEM / Kyber, Falcon, SPHINCS+). Quantum-safe key exchange at only **+13% handshake overhead** vs classical TLS.
`C` · `OpenSSL 3.0.8` · `liboqs` · `oqs-provider` · `TLS 1.3`

#### 🎮 [Enhancing-PPO-CartPole-Benchmark](https://github.com/Msubasi1/Enhancing-PPO-CartPole-Benchmark)
Reproducible benchmark of vanilla vs hyperparameter-tuned PPO under Gaussian observation noise on CartPole-v1 and LunarLander-v3. Tuned variant beats vanilla at every noise level — **+76% reward at σ = 0.2 on CartPole**. `verify.py` regenerates every figure in under 2 minutes.
`Python` · `Stable-Baselines3` · `Gymnasium` · `PyTorch` · `TensorBoard`

#### 🧵 [Parallel-Pattern-Matching-OpenMP](https://github.com/Msubasi1/Parallel-Pattern-Matching-OpenMP)
OpenMP-parallelized 5×5 pattern matching on 16-bit grayscale images in C. Three implementations (sequential, static scheduling, dynamic scheduling) with **per-thread private result storage** to eliminate lock contention; static wins on uniform workloads, dynamic shines under uneven load.
`C99` · `OpenMP` · `GCC 15` · `Apple Silicon`

#### 🎚️ [Adaptive-Noise-Cancellation-QPSO](https://github.com/Msubasi1/Adaptive-Noise-Cancellation-QPSO)
Feed-forward neural network for adaptive noise cancellation on time-domain audio, with hyperparameters tuned by **Quantum-Assisted PSO** (mean-best position instead of velocity updates). QPSO beats classical PSO on every metric: **MSE 0.010 vs 0.015, SNR 18.5 vs 15.2 dB, 5 vs 10 iterations** to converge.
`Python` · `TensorFlow / Keras` · `librosa` · `pyswarm`

#### 🌧️ [Rainfall-Prediction-Grey-Wolf-LM](https://github.com/Msubasi1/Rainfall-Prediction-Grey-Wolf-LM)
Reproducibility study of GWLM-NARX (Mohd et al., 2020) for Indian rainfall prediction — NARX + Grey Wolf Optimizer + Levenberg-Marquardt hybrid. **Honest negative result**: the paper's accuracy claims could not be reproduced despite seven different mitigation strategies; combining two strong optimizers does not automatically yield a stronger one.
`Python` · `TensorFlow` · `SciPy` · `scikit-learn`

#### 🎨 [CNN-Image-Colorization-Segmentation](https://github.com/Msubasi1/CNN-Image-Colorization-Segmentation)
PyTorch CNN coursework: (1) image colorization on the CIFAR-10 Horse subset using a custom encoder-decoder, then UNet-style skip connections; (2) fine-tuning a pre-trained dilated-convolution segmentation model on Oxford-17 Flowers. Includes a pedagogical custom `MyConv2d` implementation.
`Python` · `PyTorch` · `torchvision`

---

### 🚧 Work in progress

#### 💔 [Kındar](https://github.com/Msubasi1/Kindar)
**The anti-Tinder.** A Flutter social app where the metric is inverted: users swipe right to *dislike*, the most-disliked profiles climb a public leaderboard, and achievements reward milestones like "100 dislikes in a single day." Card-swipe UI, post-match chat, Firebase backend. Manifest-only public repo while the source tree is in active development.
`Flutter` · `Dart` · `Riverpod` · `go_router` · `Firebase (Auth + Firestore)` · `flutter_card_swiper` · `Google / Apple Sign-In`

---

### 🎯 Undergraduate projects

- **[Disease Detection Application](https://github.com/Msubasi1/Disease-Detection-Application-using-Machine-Learning)** — Streamlit web app predicting four diseases from questionnaire data with SelectKBest + Logistic Regression (~97% accuracy). `Python` · `scikit-learn` · `Streamlit`
- **[Skin Cancer Detection by Lesion Images](https://github.com/Msubasi1/Skin-Cancer-Detection-by-Lesion-Images-with-ML)** — CNN classifying seven pigmented skin lesions from HAM10000 (~75% test accuracy). `Keras` · `TensorFlow`
- **[Geographical Origin of Music](https://github.com/Msubasi1/Geographical-Origin-Of-Music)** — Predicting a track's country of origin from low-level audio features; compares RF / LR / SVM / MLP with GeoPandas world maps. `scikit-learn` · `GeoPandas`

> Browse the **[Repositories](https://github.com/Msubasi1?tab=repositories)** tab for more — including data-structure assignments in Java/C and small games in Python and C#.

---

### 📫 Get in Touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammetsubasi/)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://subasimuhammet01.medium.com/)
[![Email](https://img.shields.io/badge/subasimuhammet01@gmail.com-c14438?style=for-the-badge&logo=Gmail&logoColor=white)](mailto:subasimuhammet01@gmail.com)
[![GitHub followers](https://img.shields.io/github/followers/Msubasi1?style=for-the-badge&logo=github&label=Follow)](https://github.com/Msubasi1)
