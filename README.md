# CtrASC
An Interpretable Pan-squamous Benchmark for Resolving Pathological Grading Ambiguity across the Continuous Differentiation Spectrum 

## 🧔: Authors [*Corresponding author]
Pan Huang*, Xinwei Zhang, Yiwen Wang, Zheng Gu, Zhenglin Ji, Guoqing Fu, Mingrui Ma*, Chentao Li*, Jing Qin*, and Yifang Ping*

## :fire: News

- [xxx/xxx/xxx] xxx



## :rocket: Pipeline

Here's an overview of our **Circult-trees Rule-guided Active Semi-fuzzy Clustering (CrtASC)** method:

![Figure 1](./images/xxx.jpg)



## :mag: TODO
<font color="red">**We are currently organizing all the code. Stay tuned!**</font>
- [x] training code
- [x] Evaluation code
- [x] Model code
- [ ] Pretrained weights
- [ ] Datasets


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
If you have any questions, please contact [Dr.Pan Huang](https://scholar.google.com/citations?user=V_7bX4QAAAAJ&hl=zh-CN) (`panhuang@polyu.edu.hk`).



