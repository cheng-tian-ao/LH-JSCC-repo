<div align="center">

<h1>LH-JSCC: A Lightweight Hybrid Network Toward Few-Shot Semantic Communication for Industrial Internet of Things</h1>

[![Status: Under Review](https://img.shields.io/badge/Status-Under%20Review-yellow)](#)
[![Code: Coming Soon](https://img.shields.io/badge/Code-Coming%20Soon-blue)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green)](LICENSE)

<br>

**Yuyi Sun**<sup>1*</sup> &emsp; **Tianao Cheng**<sup>1*</sup> &emsp; **Tingting Xiao**<sup>1</sup> &emsp; **Yijun Lu**<sup>2</sup> <br> **Zheng Lin**<sup>3</sup> &emsp; **Shibo He**<sup>4</sup> &emsp; **Wei Ni**<sup>5</sup> &emsp; **Jun Luo**<sup>6</sup>

<sup>1</sup> Hangzhou Normal University &emsp; <sup>2</sup> Waseda University &emsp; <sup>3</sup> The University of Hong Kong <br> <sup>4</sup> Zhejiang University &emsp; <sup>5</sup> Edith Cowan University &emsp; <sup>6</sup> Nanyang Technological University <br>
<sup>*</sup> Equal contribution.

</div>

<br>

## 📄 Overview

This repository serves as the official paper archive for **LH-JSCC**, a lightweight hybrid joint source-channel coding framework designed for few-shot semantic communication in Industrial Internet of Things (IIoT). By leveraging advanced deep learning techniques, LH-JSCC significantly reduces communication overhead while maintaining high semantic fidelity, making it highly suitable for resource-constrained IIoT devices.

---

## 📝 Abstract

> Industrial Internet of Things (IIoT) has been a significant technology in modern industry, which requires timely data transmissions for emergent tasks. Conventional data transmission approaches transmit raw data, bringing about high-redundancy, low-value data bulk and higher resource consumption. Semantic communication (SemCom), a new paradigm for next-generation communications, extracts semantics for transmissions rather than raw bit data, which can save energy consumption and achieve task-oriented transmissions. However, SemCom framework deployed for IIoT faces some challenges, and existing schemes cannot be directly applied. IIoT suffers from severe interference, which poses a challenge for semantic transmissions. Furthermore, there have been limited industrial datasets for training the SemCom encoder-decoder framework. In this paper, we propose LH-JSCC, a lightweight hybrid network toward few-shot SemCom for IIoT. Specifically, we first propose a lightweight encoding backbone based on NAFNet to extract non-linear features with low cost, and we design a depthwise generalized divisive normalization (GDN) model to further reduce the computation complexity. Then, we design a hybrid module that integrates convolutional neural networks (CNNs) and Transformers to capture the global contexts and ensure that the system can be few-shot trained. Finally, we propose an SNR-aware modulation to maintain the transmission accuracy for varying channels. The experimental results demonstrate that our system outperforms the DJSCC, ADJSCC, and DeepJSCC-l++ system in terms of PSNR, SSIM, and other metrics for anomaly detection.

---

## 🔒 Code Availability

The complete source code, including model implementations, training scripts, and evaluation pipelines, will be released in the `src/` directory **upon acceptance of the paper**. We are committed to open science and will provide full instructions and pre-trained models to reproduce all experiments reported in the paper.

---

## 📖 Citation

If you find this work useful in your research, please consider citing:

```bibtex
@article{sun2026lhjscc,
  title   = {LH-JSCC: A Lightweight Hybrid Network Toward Few-Shot Semantic Communication for Industrial Internet of Things},
  author  = {Sun, Yuyi and Cheng, Tianao and Xiao, Tingting and Lu, Yijun and Lin, Zheng and He, Shibo and Ni, Wei and Luo, Jun},
  journal = {Under Review},
  year    = {2026}
}
```

---

## 📧 Contact

For any inquiries regarding this work, please contact:

- **Tianao Cheng** — [chengtianao@stu.hznu.edu.cn](mailto:chengtianao@stu.hznu.edu.cn)

---

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
