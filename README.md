# Human-Physical-Activity-HPA-dataset

A time series dataset containing daily step counts collected by the **SJTU Health** Team. 

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

## 📖 Dataset Overview

This repository hosts anonymized step count data collected by the SJTU Health team. The dataset is intended for academic research in time series forecasting, human behavior analysis, and health data mining.

### 📂 Data Structure

The dataset contains anonymized daily step records from **2017 to 2023**, covering approximately **4,594 users**.

### File Organization
The data is organized by year. For research requiring high continuity, a subset of high-quality data is provided in the `ContinuousData/` folder.

### Columns Description
The data files typically follow this structure:

| Column | Description |
| :--- | :--- |
| `Date` | The date of the record (YYYY-MM-DD). |
| `Type` | Source device type (e.g., Android, iOS, Wearables). |
| `Steps` | The recorded step count. |

---

## 🏃 About SJTU Health

The data originates from the **SJTU Health** initiative, a long-term community health program at Shanghai Jiao Tong University.

### History & Community
SJTU Health was started in **May 2015** by a group of enthusiasts, with the leadership and support from the SJTU Faculty and Staff Union. Over the years, more than **1,100 online/offline sports activities** were organized, with over **50,000 participations**. Thousands have benefited from this community effort, by sustained outdoor physical activities, in a self-disciplined way, or with the help of other community members.

> **Principal Investigator:** [Prof. Weiqiang Sun](https://icisee.sjtu.edu.cn/jiaoshiml/sunweiqiang.html)  
> [Google Scholar](https://scholar.google.com/citations?hl=zh-CN&user=2ezpfqcAAAAJ)


### Operation Model
The initiative operates through a self-owned online platform named **SJTU-Health**.
* **Data Collection:** Step count data is collected via smart phones or wearable devices (e.g., Garmin, Huawei sport watches) and synced to the platform on a regular basis.
* **Activity Organization:** Regular online activities, each with daily or accumulative step count goals, are organized on a weekly or monthly basis.
* **Team Dynamics:** Participants join small groups where team leaders facilitate communication. A consensus has been reached that every team member should fulfill their own daily goal and help others do the same.

---

## ⚖️ License & Citation

This dataset is released under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license.

### Academic Use Only
This dataset is strictly for academic and non-commercial research.

### Mandatory Citation
If you use this dataset in your research, please **cite at least one of the following papers and this repository**:

```bibtex
@article{shi2025amulti,
  author = {Shi, Keqin and Ding, Zhihua and Chen, Zhen and He, Hao and Sun, Weiqiang and Hu, Weisheng},
  title = {A multi-scale time series forecasting framework with temporal hierarchical information fusion and reconciliation: A multi-scale time series forecasting framework...},
  year = {2025},
  issue_date = {Jun 2025},
  publisher = {Kluwer Academic Publishers},
  address = {USA},
  volume = {39},
  number = {4},
  issn = {1384-5810},
  url = {[https://doi.org/10.1007/s10618-025-01103-9](https://doi.org/10.1007/s10618-025-01103-9)},
  doi = {10.1007/s10618-025-01103-9},
  journal = {Data Min. Knowl. Discov.},
  month = may,
  numpages = {26}
}

@article{chen2024step,
  title={Step Count Print: A Physical Activity-Based Biometric Identifier For User Identification and Authentication},
  author={Chen, Zhen and Shi, Keqin and Sun, Weiqiang},
  journal={IEEE Transactions on Biometrics, Behavior, and Identity Science},
  year={2024},
  publisher={IEEE}
}

@article{yujia2025understanding,
  author={Yu, Jia and Ding, Mengjun and Sun, Weiqiang and Hu, Weisheng and Wang, Huiru},
  journal={IEEE Transactions on Computational Social Systems}, 
  title={Understanding the Human Behavior of Participation in Community Sports Organizations}, 
  year={2025},
  volume={12},
  number={5},
  pages={2999-3010},
  doi={10.1109/TCSS.2025.3532924}
}

@article{ding2024growing,
   author = {Ding, Mengjun and Yu, Jia and Sun, Weiqiang},
   year = {2024},
   month = {10},
   pages = {},
   title = {Growing simplicial complex with face dimension selection and preferential attachment},
   volume = {34},
   journal = {Chaos: An Interdisciplinary Journal of Nonlinear Science},
   doi = {10.1063/5.0210960}
}

@article{shi2023inferring,
   author = {Shi, Keqin and Chen, Zhen and Li, Xuejing and Xiao, Zhifei and Sun, Weiqiang and Hu, Weisheng},
   title = {Inferring Activity Patterns from Sparse Step Counts Data with Recurrent Neural Networks},
   year = {2023},
   issue_date = {January 2023},
   publisher = {Association for Computing Machinery},
   address = {New York, NY, USA},
   volume = {4},
   number = {1},
   url = {https://doi.org/10.1145/3560468},
   doi = {10.1145/3560468},
   journal = {ACM Trans. Comput. Healthcare},
   month = feb,
   articleno = {4},
   numpages = {20}
}

```
