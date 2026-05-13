<h1 align="center">LH-JSCC: A Lightweight Hybrid Network for<br>Few-Shot Semantic Communication in IIoT</h1>

<p align="center">
  <a href="https://img.shields.io/badge/Status-Under%20Review-yellow"><img src="https://img.shields.io/badge/Status-Under%20Review-yellow" alt="Status: Under Review"></a>
  <a href="https://img.shields.io/badge/Code-Coming%20Soon-blue"><img src="https://img.shields.io/badge/Code-Coming%20Soon-blue" alt="Code: Coming Soon"></a>
  <a href="https://img.shields.io/badge/License-MIT-green"><img src="https://img.shields.io/badge/License-MIT-green" alt="License: MIT"></a>
</p>

<p align="center">
  <strong>Yuyi Sun</strong><sup>1*</sup>&ensp;·&ensp;<strong>Tianao Cheng</strong><sup>1*</sup>&ensp;·&ensp;<em>et al.</em>
</p>

<p align="center">
  <sup>1</sup> Institution Name<br>
  <sup>*</sup> Equal contribution.
</p>

---

## 📄 Overview

This repository serves as the official paper archive for **LH-JSCC**, a lightweight hybrid joint source-channel coding framework designed for few-shot semantic communication in Industrial Internet of Things (IIoT) scenarios. It hosts the manuscript, supplementary materials, presentation slides, and poster. **The full source code will be made publicly available upon acceptance of the paper.**

---

## 📝 Abstract

Industrial Internet of Things (IIoT) has been a significant technology in modern industry, which requires timely data transmissions for emergent tasks. Conventional data transmission approaches transmit raw data, bringing about high-redundancy, low-value data bulk and higher resource consumption. Semantic communication (SemCom), a new paradigm for next-generation communications, extracts semantics for transmissions rather than raw bit data, which can save energy consumption and achieve task-oriented transmissions. However, SemCom framework deployed for IIoT faces some challenges, and existing schemes cannot be directly applied. IIoT suffers from severe interference, which poses a challenge for semantic transmissions. Furthermore, there have been limited industrial datasets for training the SemCom encoder-decoder framework. In this paper, we propose LH-JSCC, a lightweight hybrid network toward few-shot SemCom for IIoT. Specifically, we first propose a lightweight encoding backbone based on NAFNet to extract non-linear features with low cost, and we design a depthwise generalized divisive normalization (GDN) model to further reduce the computation complexity. Then, we design a hybrid module that integrates convolutional neural networks (CNNs) and Transformers to capture the global contexts and ensure that the system can be few-shot trained. Finally, we propose an SNR-aware modulation to maintain the transmission accuracy for varying channels. The experimental results demonstrate that our system outperforms the DJSCC, ADJSCC, and DeepJSCC-l++ system in terms of PSNR, SSIM, and other metrics for anomaly detection.

## 🔒 Code Availability

The complete source code, including model implementations, training scripts, and evaluation pipelines, will be released in the `src/` directory **upon acceptance of the paper**. We are committed to ensuring full reproducibility of all experimental results presented in this work.

---

## 📖 Citation

If you find this work useful in your research, please consider citing:

```bibtex
@article{sun2025lhjscc,
  title   = {LH-JSCC: A Lightweight Hybrid Network for Few-Shot Semantic Communication in IIoT},
  author  = {Sun, Yuyi and Cheng, Tianao and others},
  journal = {Under Review},
  year    = {2025}
}
```

---

## 📧 Contact

For any inquiries regarding this work, please contact:

- **Tianao Cheng** — chengtianao@stu.hznu.edu.cn

---

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
