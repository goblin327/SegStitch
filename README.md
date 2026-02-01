# SegStitch: Multidimensional Transformer for Robust and Efficient Medical Imaging Segmentation

#Authors: [Shengbo Tan](https://github.com/goblin327), [Zeyu Zhang](https://steve-zeyu-zhang.github.io/)†,Daji Ergu, [Ying Cai](https://ieeexplore.ieee.org/author/37087137422)*,  Lin Wu, Binbin Hu, Pengzhang Yu, [Yang Zhao](https://yangyangkiki.github.io/)

#*Corresponding author. †Project lead.

# SegStitch: Multidimensional Transformer for Robust and Efficient Medical Imaging Segmentation

Authors:  
[Shengbo Tan](https://github.com/goblin327),  
Zeyu Zhang,  
Daji Ergu,  
Zhang Yi,  
Junjie Hu,  
[Ying Cai]*,  
Xinran Wang,  
[Yang Zhao].

*Corresponding author.

[[**Paper Link**](https://arxiv.org/pdf/2408.00496)] [[Papers With Code]()]

Medical image segmentation is a critical step in lesion identification and analysis.
However, existing methods still face significant challenges when segmenting elongated organs accurately.
To address this issue, we propose a novel segmentation approach.
First,3D medical images are divided into a set of independent image patches.
Next, we design a Dual-Granularity Attention (DGA) block.
This block employs a shared self-attention mechanism for feature extraction.
It establishes interactions across different image patches, thereby enhancing the modeling of long-range dependencies.
Finally, to mitigate the noise introduced by image patch partitioning, an Ordinary Differential Equation (ODE) block is introduced.
This block smoothly connects individual image patches to generate a complete 3D segmentation result.
The proposed method effectively alleviates the difficulties of elongated organ segmentation and significantly improves model stability.
Experimental results demonstrate that, compared with existing methods, the proposed approach improves the mean Dice similarity coefficient (mDSC) by 11.48\% on the Synapse dataset and by 6.71\% on the ACDC dataset.
Meanwhile, the number of model parameters is reduced by 36.7\%, indicating strong potential for clinical applications.
To support reproducibility, the source code has been released on GitHub at: \url{https://github.com/goblin327/SegStitch}.

![flop10](https://github.com/user-attachments/assets/2f2e679c-1933-41b1-84af-513e25791c2d)

![qkv3](https://github.com/user-attachments/assets/18803fe5-c9ec-4e67-9980-7479d3f810ac)

### Code will be released later. Stay tuned.

## Citation

For academic use, please cite:
```
@article{tan2024segstitch,
  title={SegStitch: Multidimensional Transformer for Robust and Efficient Medical Imaging Segmentation},
  author={Tan, Shengbo and Zhang, Zeyu and Cai, Ying and Ergu, Daji and Wu, Lin and Hu, Binbin and Yu, Pengzhang and Zhao, Yang},
  journal={arXiv preprint arXiv:2408.00496},
  year={2024}
}
```

## Contact us

Please do not hesitate to open an issue. You don't want to send us an email since you probably not getting prompt feedback.
