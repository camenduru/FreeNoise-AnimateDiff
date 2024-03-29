# FreeNoise-AnimateDiff

This repository is the official implementation of [FreeNoise](https://arxiv.org/abs/2310.15169) in [AnimateDiff](https://arxiv.org/abs/2307.04725).

**[FreeNoise: Tuning-Free Longer Video Diffusion via Noise Rescheduling](https://arxiv.org/abs/2310.15169)**
</br>
Haonan Qiu,
Menghan Xia*,
Yong Zhang,
Yingqing He,
Xintao Wang,
Ying Shan,
Ziwei Liu*
<p style="font-size: 0.8em; margin-top: -1em">*Corresponding Author</p>

**[AnimateDiff: Animate Your Personalized Text-to-Image Diffusion Models without Specific Tuning](https://arxiv.org/abs/2307.04725)**
</br>
Yuwei Guo,
Ceyuan Yang*,
Anyi Rao,
Yaohui Wang,
Yu Qiao,
Dahua Lin,
Bo Dai
<p style="font-size: 0.8em; margin-top: -1em">*Corresponding Author</p>
<br>

<img src=__assets__/animations/sample5_wo.gif>
<p>w/o Noise Rescheduling</p>
<br>

<img src=__assets__/animations/sample5.gif>
<p>w Noise Rescheduling</p>

## Run

Set up following the codebase [AnimateDiff](https://github.com/guoyww/AnimateDiff). Currently do not support the MotionLoRA.
```bash
  python scripts/animate.py
```

## BibTeX
```
@misc{qiu2023freenoise,
      title={FreeNoise: Tuning-Free Longer Video Diffusion Via Noise Rescheduling}, 
      author={Haonan Qiu and Menghan Xia and Yong Zhang and Yingqing He and Xintao Wang and Ying Shan and Ziwei Liu},
      year={2023},
      eprint={2310.15169},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

@article{guo2023animatediff,
  title={AnimateDiff: Animate Your Personalized Text-to-Image Diffusion Models without Specific Tuning},
  author={Guo, Yuwei and Yang, Ceyuan and Rao, Anyi and Wang, Yaohui and Qiao, Yu and Lin, Dahua and Dai, Bo},
  journal={arXiv preprint arXiv:2307.04725},
  year={2023}
}
```

## Acknowledgements
Codebase built upon [AnimateDiff](https://github.com/guoyww/AnimateDiff).
