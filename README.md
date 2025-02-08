# TPLytics: A Comprehensive Survey on Third-Party Library Detection

**Authors**: [Abhinav Jamwal](https://scholar.google.com/citations?user=NsOedN0AAAAJ&hl=en), [Sandeep Kumar](https://scholar.google.co.in/citations?user=PDz0F-YAAAAJ&hl=en)


---

Third-party libraries (TPLs) play a crucial role in modern software development by providing reusable components, saving time, and reducing development costs. However, the increasing reliance on TPLs raises concerns about security vulnerabilities, dependency management, and privacy risks. These libraries' accurate detection and analysis are paramount for ensuring robust software systems.

This repository presents a curated collection of resources, including research papers, tools, datasets, and methodologies focused on third-party library detection. The aim is to provide researchers and practitioners with a comprehensive guide to understanding this domain's state of the art. We regularly update this repository with the latest advancements and open-source implementations.

---

## Table of Contents
- [Motivation](#motivation)
- [Detection Approaches](#detection-approaches)
    - [Static Analysis](#static-analysis)
    - [Dynamic Analysis](#dynamic-analysis)
    - [Hybrid Approaches](#hybrid-approaches)
- [Tools and Frameworks](#tools-and-frameworks)
- [Datasets](#datasets)
- [Challenges in the Field](#challenges-in-the-field)
- [Future Directions](#future-directions)
- [References](#references)

---

## Motivation

The reliance on third-party libraries has become integral to modern software development, offering faster development cycles and robust functionality. However, this dependence introduces challenges such as:
- **Security Vulnerabilities**: TPLs often serve as an attack vector for malicious activities.
- **Privacy Risks**: Libraries may expose sensitive user data to third parties.
- **Dependency Management**: Ensuring compatibility and reducing version conflicts is crucial.
- **Legal and Licensing Issues**: Understanding and complying with library licenses is critical to avoid legal repercussions.

A systematic understanding of TPL detection techniques enables better management, enhanced security, and improved software quality.

---

## Detection Approaches



[**Pay Your Attention on Lib! Android Third-Party Library Detection via Feature Language Model**](https://aoa0.github.io/pubs/saner25.pdf) [SANER 2025]  
   *Dahan Pan*, *Yi Xu*, Runhan Feng, Donghui Yu, Jiawen Chen, Ya Fang, Yuanyuan Zhang†  
   [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://aoa0.github.io)

 [**Privacy Settings of Third-Party Libraries in Android Apps: A Study of Facebook SDKs**](https://usableprivacy.org/static/files/rodriguez_pets_2025.pdf) [PETS 2025]  
   David Rodriguez, Joseph A. Calandrino, Jose M. Del Alamo, Norman Sadeh  
   [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DavidRodriguezTorrado/PrivacySDKSettingsAnalyzer)

[**How Does Code Optimization Impact Third-party Library Detection for Android Applications?**](https://dl.acm.org/doi/10.1145/3691620.3695554) [ASE 2024]   
Zifan Xie, Ming Wen, Tinghan Li, Yiding Zhu, Qinsheng Hou, Hai Jin  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CGCL-codes/LibHunter)

[**Measuring Compliance Implications of Third-party Libraries' Privacy Label Disclosure Guidelines**](https://doi.org/10.1145/3658644.3670371) [ACM CCS 2024]  
Yue Xiao, Chaoqi Zhang, Yue Qin, Fares Fahad S Alharbi, Luyi Xing, Xiaojing Liao  

[**Homogeneous graph neural networks for third-party library recommendation**](https://doi.org/10.1016/j.ipm.2024.103831) [Information Processing & Management, 2024]  
Duantengchuan Li, Yuxuan Gao, Zhihao Wang, Hua Qiu, Pan Liu, Zhuoran Xiong, Zilong Zhang  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dacilab/HGNRec)

[**Neural Library Recommendation by Embedding Project-Library Knowledge Graph**](https://doi.org/10.1109/TSE.2024.3393504) [IEEE Transactions on Software Engineering, 2024]  
Bo Li, Haowei Quan, Jiawei Wang, Pei Liu, Haipeng Cai, Yuan Miao, Yun Yang, Li Li  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Limber0117/PyRec)

[**AndroLibZoo: A Reliable Dataset of Libraries Based on Software Dependency Analysis**](https://ieeexplore.ieee.org/abstract/document/10555749) [MSR 2024]  
Jordan Samhi, Tegawendé F. Bissyandé, Jacques Klein  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JordanSamhi/AndroLibZoo)

[**Ossfp: Precise and Scalable C/C++ Third-Party Library Detection Using Fingerprinting Functions**](https://doi.org/10.1109/ICSE48619.2023.00034) [ICSE 2023]  
Jiahui Wu, Zhengzi Xu, Wei Tang, Lyuye Zhang, Yueming Wu, Chengyue Liu, Kairan Sun, Lida Zhao, Yang Liu  








### Static Analysis

Static analysis examines the software's source code or binary files without executing the application. This approach leverages techniques such as:
- Signature-based matching of library files.
- Pattern recognition in code dependencies.

**Examples of tools and techniques**:
- **LibRadar**: Detects libraries in Android APKs using hash-based techniques.
- **Androguard**: Performs reverse engineering of APK files for library identification.

Static analysis is lightweight and efficient but may miss dynamically loaded or obfuscated libraries.


### Dynamic Analysis
Techniques that evaluate libraries during runtime.

### Hybrid Approaches
A combination of static and dynamic techniques.

---

## Tools and Frameworks
An overview of tools used for third-party library detection, including their strengths and limitations.

---

## Datasets
Details of publicly available datasets for research on third-party library detection.

---

## Challenges in the Field
A discussion on the current challenges in third-party library detection:
- Scalability for large-scale apps.
- Detecting obfuscated or encrypted libraries.
- Maintaining up-to-date library databases.

---

## Future Directions
Potential areas for further research:
- Leveraging machine learning for automated detection.
- Developing real-time detection systems.
- Enhancing privacy-preserving mechanisms during detection.

---

## References
A list of all research papers, tools, and other resources cited in this repository.

---

## Contribution
We welcome contributions! If you have research papers, tools, or datasets to add, feel free to open an issue or submit a pull request.
