# ClearGrade
ClearGrade Resolves Pathological Grading Ambiguity across the Pan-squamous Differentiation Continuum

## 🧔: Authors [*Corresponding author]
Pan Huang, Xinwei Zhang, Yiwen Wang, Zheng Gu, Zhenglin Ji, Binglin Ma, Lan Wang, Zilai Yao, Francesco Mercaldo, Antonella Santone, Qiye Chen, Andi Liu, Jingyao Jia, Weiqian Liao, Guoqing Fu, Kurban Ubul, Xinyu Hao, Mingrui Ma*,Chentao Li*, Xiaoyi Lv*, Jing Qin*, and Yifang Ping*

## :fire: News

- [xxx/xxx] xxx



## :rocket: Pipeline

Here's an overview of our **Continuum-aware de-ambiguation grading paradigm (ClearGrade)**:

![Figure 1](./Images/Figure_2.jpg)

**Overview of the ClearGrade framework**, i.e., a continuum-aware ambiguity-resolving pathological grading framework. (**a**). Training stage of ClearGrade. (**b**). Inference stage of ClearGrade. (**c**). Model interpretability assessment. ICALE plot of ClearGrade on AMU-CSCC. (**d**). Active semi-fuzzy clustering (ASC). (**e**). 2D representation by different biomarkers of ClearGrade on AMU-CSCC. (**f**). Pathologists can use ClearGrade to improve their ability to identify ambiguous grading cases. (**g**). Counterfactual-interaction mixing circuits. (**h**). AUC performance comparison on InterSGBench. (**i**). Region of interest grading similarity comparison with real experts. (**j**). Subjective assessment. (**k**). Internal validation in top-10 cohorts, Multi-center (MC). (**l**). Within-SCC external validation in top-20 cohorts, Multi-center (MC). (**m**). CMC rule visualization on Hancock-Oropharynx test index 62.



## :mag: TODO
<font color="red">**We are currently organizing all the code. Stay tuned!**</font>
- [x] training code
- [x] Evaluation code
- [x] Model code
- [x] Model weights
- [x] Datasets


## 🛠️ Getting Started

To get started with **ClearGrade**, follow the installation instructions below.

1.  Clone the repo

```sh
git clone https://github.com/Baron-Huang/ClearGrade
```

2. Install dependencies
   
```sh
pip install -r requirements.txt
```

3. Training on Swin Transformer-S Backbone
```sh
sh run_ClearGrade.sh
Modify: --abla_type sota --run_mode train --random_seed ${seed}
```

4. Evaluation
```sh
sh run_ClearGrade.sh
Modify: --abla_type sota --run_mode test --random_seed ${seed}
```

5. Extract features for plots
```sh
sh ClearGrade.sh
Modify: --abla_type sota --run_mode test --random_seed ${seed} --feat_extract
```

6. Interpretability plots
```sh
sh ClearGrade.sh
Modify: --abla_type sota --run_mode test --random_seed ${seed} --bag_weight
```

## :postbox: Contact
If you have any questions, please contact [Dr.Pan Huang] (panhuang@polyu.edu.hk).



