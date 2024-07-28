# SegStitch: Multidimensional Transformer for Robust and Efficient Medical Imaging Segmentation

Authors: [Shengbo Tan](https://github.com/goblin327), [Zeyu Zhang](https://steve-zeyu-zhang.github.io/), [Ying Cai](https://ieeexplore.ieee.org/author/37087137422)*, Daji Ergu, Lin Wu, Binbin Hu, Pengzhang Yu, [Yang Zhao](https://yangyangkiki.github.io/)

*Corresponding author

[[Paper Link]()]

Medical imaging segmentation plays a significant
role in the automatic recognition and analysis of lesions. State-of-
the-art methods, particularly those utilizing transformers, have
been prominently adopted in 3D semantic segmentation due to
their superior performance in scalability and generalizability.
However, plain vision transformers encounter challenges due
to their neglect of local features and their high computational
complexity. To address these challenges, we introduce three
key contributions: Firstly, we proposed SegStitch, an innovative
architecture that integrates transformers with denoising ODE
blocks. Instead of taking whole 3D volumes as inputs, we adapt
axial patches and customize patch-wise queries to ensure seman-
tic consistency. Additionally, we conducted extensive experiments
on the BTCV and ACDC datasets, achieving improvements up to
11.48% and 6.71% respectively in mDSC, compared to state-of-
the-art methods. Lastly, our proposed method demonstrates out-
standing efficiency, reducing the number of parameters by 36.7%
and the number of FLOPS by 10.7% compared to UNETR.
This advancement holds promising potential for adapting our
method to real-world clinical practice. 

![flop10](https://github.com/user-attachments/assets/2f2e679c-1933-41b1-84af-513e25791c2d)

![qkv3](https://github.com/user-attachments/assets/18803fe5-c9ec-4e67-9980-7479d3f810ac)

## Code will be released later. Stay tuned.

# Citation

For academic use, please cite:
```
TBD
```

# Contact us

Please do not hesitate to open an issue. You don't want to send us an email since you probably not getting prompt feedback.
