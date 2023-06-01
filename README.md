# FineRewards

![](https://img.enderfga.cn/img/image-20230530225419079.png)

This is the codebase for our [paper](https://arxiv.org/abs/2305.19599) **Boosting Text-to-Image Diffusion Models with Fine-Grained Semantic Rewards**

Please refer to the three repositories in the "**Acknowledgements**" section for environment setup. All experiments are conducted using the FineRewards-RAFT.ipynb notebook.

**Caption Reward** can be calculated using the "get_cap_reward" function.

**SAM Reward** can be calculated using the "get_sam_reward" function.

## Acknowledgements

[IDEA-Research](https://github.com/IDEA-Research)/**[Grounded-Segment-Anything](https://github.com/IDEA-Research/Grounded-Segment-Anything)**

[lm-sys](https://github.com/lm-sys)/**[FastChat](https://github.com/lm-sys/FastChat)**

[OptimalScale](https://github.com/OptimalScale)/**[LMFlow](https://github.com/OptimalScale/LMFlow)**

## Citation

If you find our code helpful, please cite our paper:

```latex
@misc{fang2023boosting,
      title={Boosting Text-to-Image Diffusion Models with Fine-Grained Semantic Rewards}, 
      author={Guian Fang and Zutao Jiang and Jianhua Han and Guangsong Lu and Hang Xu and Xiaodan Liang},
      year={2023},
      eprint={2305.19599},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

