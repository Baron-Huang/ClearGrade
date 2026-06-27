# ClearGrade
ClearGrade resolves Pathological Grading Ambiguity across the Pan-squamous Differentiation Continuum

## 🧔: Authors [*Corresponding author]
Pan Huang, Xinwei Zhang, Yiwen Wang, Zheng Gu, Zhenglin Ji, Guoqing Fu, Francesco Mercaldo, Antonella Santone, Kurban Ubul, Binglin Ma, Mingrui Ma*, Chentao Li*, Xiuwu Bian*, Yifang Ping*, and Jing Qin*

## :fire: News

- [xxx/xxx/xxx] xxx



## :rocket: Pipeline

Here's an overview of our **Continuum-aware de-ambiguation grading paradigm (ClearGrade)**:

![Figure 1](./Images/Figure_1.jpg)



## :mag: TODO
<font color="red">**We are currently organizing all the code. Stay tuned!**</font>
- [x] training code
- [x] Evaluation code
- [x] Model code
- [x] Model weights
- [x] Datasets


## 🛠️ Getting Started

To get started with **CtrASC**, follow the installation instructions below.

1.  Clone the repo

```sh
git clone https://github.com/Baron-Huang/CtrASC
```

2. Install dependencies
   
```sh
pip install -r requirements.txt
```

3. Training on Swin Transformer-S Backbone
```sh
sh run_CtrASC.sh
Modify: --abla_type sota --run_mode train --random_seed ${seed}
```

4. Evaluation
```sh
sh run_CtrASC.sh
Modify: --abla_type sota --run_mode test --random_seed ${seed}
```

5. Extract features for plots
```sh
sh CtrASC.sh
Modify: --abla_type sota --run_mode test --random_seed ${seed} --feat_extract
```

6. Interpretability plots
```sh
sh CtrASC.sh
Modify: --abla_type sota --run_mode test --random_seed ${seed} --bag_weight
```

## :postbox: Contact
If you have any questions, please contact [Dr.Pan Huang] (panhuang@polyu.edu.hk).



