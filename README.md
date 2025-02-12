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

### **Static Analysis and Detection**

[**Pay Your Attention on Lib! Android Third-Party Library Detection via Feature Language Model**](https://aoa0.github.io/pubs/saner25.pdf) [SANER 2025]  
   *Dahan Pan*, *Yi Xu*, Runhan Feng, Donghui Yu, Jiawen Chen, Ya Fang, Yuanyuan Zhang†  
   [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://aoa0.github.io)

   [**How Does Code Optimization Impact Third-party Library Detection for Android Applications?**](https://dl.acm.org/doi/10.1145/3691620.3695554) [ASE 2024]   
Zifan Xie, Ming Wen, Tinghan Li, Yiding Zhu, Qinsheng Hou, Hai Jin  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CGCL-codes/LibHunter)


[**Ossfp: Precise and Scalable C/C++ Third-Party Library Detection Using Fingerprinting Functions**](https://doi.org/10.1109/ICSE48619.2023.00034) [ICSE 2023]  
Jiahui Wu, Zhengzi Xu, Wei Tang, Lyuye Zhang, Yueming Wu, Chengyue Liu, Kairan Sun, Lida Zhao, Yang Liu  

[**LibKit: Detecting Third-Party Libraries in iOS Apps**](https://doi.org/10.1145/3611643.3616344) [ESEC/FSE 2023]  
Daniel Domínguez-Álvarez, Alejandro de la Cruz, Alessandra Gorla, Juan Caballero  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://zenodo.org/records/7042015)

[**JSLibD: Reliable and Heuristic Detection of Third-Party Libraries in Miniapps**](https://dl.acm.org/doi/abs/10.1145/3605762.3624428) [CCS 2023]  
Junjie Tao, Jifei Shi, Ming Fan, Yin Wang, Junfeng Liu, Ting Liu 

[**LibDB: An Effective and Efficient Framework for Detecting Third-Party Libraries in Binaries**](https://doi.org/10.1145/3524842.352844) [MSR 2022]  
Wei Tang, Yanlin Wang, Hongyu Zhang, Shi Han, Ping Luo, Dongmei Zhang  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DeepSoftwareAnalytics/LibDB)

[**Detecting Third-Party Libraries for Privacy Leakage in Packed Android Applications**](https://doi.org/10.1109/CAC57257.2022.10054907) [China Automation Congress (CAC) 2022]  
Hua Cheng, Guang Hu, Jin Liu, Zhiwei Kang, Chao Pan, ZiJun Zhang  

[**Lib2Desc: Automatic Generation of Security-Centric Android App Descriptions Using Third-Party Libraries**](https://link.springer.com/article/10.1007/s10207-022-00601-x) [International Journal of Information Security, 2022]  
Beyza Cevik, Nur Altiparmak, Murat Aksu, Sevil Sen 

[**Understanding and Conquering the Difficulties in Identifying Third-Party Libraries from Millions of Android Apps**](https://doi.org/10.1109/TBDATA.2021.3093244) [IEEE Transactions on Big Data, 2021]  
Yanghua Zhang, Jice Wang, Hexiang Huang, Yuqing Zhang, Peng Liu  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/imcczy/libhawkeye)
   

 

### **Privacy-Focused**

[**Privacy Settings of Third-Party Libraries in Android Apps: A Study of Facebook SDKs**](https://usableprivacy.org/static/files/rodriguez_pets_2025.pdf) [PETS 2025]  
   David Rodriguez, Joseph A. Calandrino, Jose M. Del Alamo, Norman Sadeh  
   [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DavidRodriguezTorrado/PrivacySDKSettingsAnalyzer)

[**Measuring Compliance Implications of Third-party Libraries' Privacy Label Disclosure Guidelines**](https://doi.org/10.1145/3658644.3670371) [ACM CCS 2024]  
Yue Xiao, Chaoqi Zhang, Yue Qin, Fares Fahad S Alharbi, Luyi Xing, Xiaojing Liao  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://sites.google.com/view/colainewebsites)

[**Demystifying Privacy Policy of Third-Party Libraries in Mobile Apps**](https://doi.org/10.1109/ICSE48619.2023.00137) [ICSE 2023]  
Kaifa Zhao, Xian Zhan, Le Yu, Shiyao Zhou, Hao Zhou, Xiapu Luo, Haoyu Wang, Yepang Liu

[**LibCapsule: Complete Confinement of Third-Party Libraries in Android Applications**](https://doi.org/10.1109/TDSC.2021.3075817) [IEEE Transactions on Dependable and Secure Computing, 2022]  
Jun Qiu, Xuewu Yang, Huamao Wu, Yajin Zhou, Jinku Li, Jianfeng Ma  

### **Model/Algorithm Papers**
[**Homogeneous graph neural networks for third-party library recommendation**](https://doi.org/10.1016/j.ipm.2024.103831) [Information Processing & Management, 2024]  
Duantengchuan Li, Yuxuan Gao, Zhihao Wang, Hua Qiu, Pan Liu, Zhuoran Xiong, Zilong Zhang  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dacilab/HGNRec)

[**Neural Library Recommendation by Embedding Project-Library Knowledge Graph**](https://doi.org/10.1109/TSE.2024.3393504) [IEEE Transactions on Software Engineering, 2024]  
Bo Li, Haowei Quan, Jiawei Wang, Pei Liu, Haipeng Cai, Yuan Miao, Yun Yang, Li Li  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Limber0117/PyRec)

[**Endowing Third-Party Libraries Recommender Systems with Explicit User Feedback Mechanisms**](https://doi.org/10.1109/SANER53432.2022.00099) [SANER 2022]  
Riccardo Rubei, Claudio Di Sipio, Juri Di Rocco, Davide Di Ruscio, Phuong T. Nguyen  

[**Embedding App-Library Graph for Neural Third-Party Library Recommendation**](https://dl.acm.org/doi/abs/10.1145/3468264.3468552) [ESEC/FSE 2021]  
Bo Li, Qiang He, Feifei Chen, Xin Xia, Li Li, John Grundy, Yun Yang  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/fio1982/GRec)

[**Adversarial Machine Learning: On the Resilience of Third-Party Library Recommender Systems**](https://doi.org/10.1145/3463274.34638) [EASE 2021]  
Phuong T. Nguyen, Davide Di Ruscio, Juri Di Rocco, Claudio Di Sipio, Massimiliano Di Penta  


### **Dataset**

[**AndroLibZoo: A Reliable Dataset of Libraries Based on Software Dependency Analysis**](https://ieeexplore.ieee.org/abstract/document/10555749) [MSR 2024]  
Jordan Samhi, Tegawendé F. Bissyandé, Jacques Klein  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JordanSamhi/AndroLibZoo)


### **Survey and Taxonomy**

[**Research on Third-Party Libraries in Android Apps: A Taxonomy and Systematic Literature Review**](https://doi.org/10.1109/TSE.2021.3114381) [IEEE Transactions on Software Engineering, 2021]  
Xian Zhan, Tianming Liu, Lingling Fan, Li Li, Sen Chen, Xiapu Luo, Yang Liu  


### **Usage and Risk Analysis**
[**Characterizing Usages, Updates, and Risks of Third-Party Libraries in Java Projects**](https://link.springer.com/article/10.1007/s10664-022-10131-8) [Empirical Software Engineering, 2022]  
Kaifeng Huang, Bihuan Chen, Congying Xu, Ying Wang, Bowen Shi, Xin Peng, Yijian Wu, Yang Liu  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://3rdpartylibs.github.io/)

[**Dealing with Popularity Bias in Recommender Systems for Third-Party Libraries: How Far Are We?**](https://doi.org/10.1109/MSR59073.2023.00016) [MSR 2023]  
Phuong T. Nguyen, Riccardo Rubei, Juri Di Rocco, Claudio Di Sipio, Davide Di Ruscio, Massimiliano Di Penta  

 





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
