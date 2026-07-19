# ClearGrade
ClearGrade Resolves Pathological Grading Ambiguity across the Pan-squamous Differentiation Continuum

## 🧔: Authors [*Corresponding author]
Pan Huang, Xinwei Zhang, Yiwen Wang, Zhenglin Ji, Zheng Gu, Francesco Mercaldo, Antonella Santone, Qiye Chen, Andi Liu, Weiqian Liao, Jingyao Jia, Guoqing Fu, Kurban Ubul, Binglin Ma, Mingrui Ma*, Chentao Li*, Jing Qin*, Xiaohan Xing*, and Yifang Ping*

## :fire: News

- [xxx/xxx/xxx] xxx



## :rocket: Pipeline

Here's an overview of our **Continuum-aware de-ambiguation grading paradigm (ClearGrade)**:

![Figure 1](./Images/Figure_2.jpg)



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



