# Voxel

This is a heavily stripped down version of the DinoV2 repo meant to easily integrate into the Voxel codebase.

# DINOv2: Learning Robust Visual Features without Supervision

**[Meta AI Research, FAIR](https://ai.facebook.com/research/)**

Maxime Oquab,
Timothée Darcet,
Théo Moutakanni,
Huy V. Vo,
Marc Szafraniec,
Vasil Khalidov,
Patrick Labatut,
Armand Joulin,
Piotr Bojanowski

[[`Paper #1`](https://arxiv.org/abs/2304.07193)] [`Paper #2`](https://arxiv.org/abs/2309.16588)] [[`Blog`](https://ai.facebook.com/blog/dino-v2-computer-vision-self-supervised-learning/)] [[`Demo`](https://dinov2.metademolab.com)] [[`BibTeX`](#citing-dinov2)]

PyTorch implementation and pretrained models for DINOv2. For details, see the papers: **[DINOv2: Learning Robust Visual Features without Supervision](https://arxiv.org/abs/2304.07193)** and **[Vision Transformers Need Registers](https://arxiv.org/abs/2309.16588)**.

DINOv2 models produce high-performance visual features that can be directly employed with classifiers as simple as linear layers on a variety of computer vision tasks; these visual features are robust and perform well across domains without any requirement for fine-tuning. The models were pretrained on a dataset of 142 M images without using any labels or annotations.

https://github.com/facebookresearch/dinov2/assets/60359573/f168823e-7922-415a-b429-578badf5c356

<div align="center">
  Visualization of the three first principal components of the patch features of all frames, mapped to RGB values.
</div>

## License

DINOv2 code and model weights are released under the Apache License 2.0. See [LICENSE](LICENSE) for additional details.

## Contributing

See [contributing](CONTRIBUTING.md) and the [code of conduct](CODE_OF_CONDUCT.md).

## Citing DINOv2

If you find this repository useful, please consider giving a star :star: and citation :t-rex::

```
@misc{oquab2023dinov2,
  title={DINOv2: Learning Robust Visual Features without Supervision},
  author={Oquab, Maxime and Darcet, Timothée and Moutakanni, Theo and Vo, Huy V. and Szafraniec, Marc and Khalidov, Vasil and Fernandez, Pierre and Haziza, Daniel and Massa, Francisco and El-Nouby, Alaaeldin and Howes, Russell and Huang, Po-Yao and Xu, Hu and Sharma, Vasu and Li, Shang-Wen and Galuba, Wojciech and Rabbat, Mike and Assran, Mido and Ballas, Nicolas and Synnaeve, Gabriel and Misra, Ishan and Jegou, Herve and Mairal, Julien and Labatut, Patrick and Joulin, Armand and Bojanowski, Piotr},
  journal={arXiv:2304.07193},
  year={2023}
}
```

```
@misc{darcet2023vitneedreg,
  title={Vision Transformers Need Registers},
  author={Darcet, Timothée and Oquab, Maxime and Mairal, Julien and Bojanowski, Piotr},
  journal={arXiv:2309.16588},
  year={2023}
}
```
