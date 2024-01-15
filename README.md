# Adaptive_axonal_delay
Adaptive Axonal Delay Training for Spiking Neural Networks

## **What is this repository for?**

Learnable axonal delay module with adaptive training scheduler to adjust the caps of axonal delays of each layer.

# Result
```
SHD           92.45%
NTDIDIGITS    95.09%
```

## **Usage**

Our delay module is based on [SLayer framework](https://github.com/bamsumit/slayerPytorch), after downloading the Slayer framework, 
you can easily implement our delay module and adaptive training scheduler.

## **Papers**
Axonal delay module [Paper](https://ieeexplore.ieee.org/abstract/document/9747411)

```bibtex
@inproceedings{sun2022axonal,
  title={Axonal delay as a short-term memory for feed forward deep spiking neural networks},
  author={Sun, Pengfei and Zhu, Longwei and Botteldooren, Dick},
  booktitle={ICASSP 2022-2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages={8932--8936},
  year={2022},
  organization={IEEE}
}
```

Adaptive axonal delay module [Paper](https://ieeexplore.ieee.org/abstract/document/10094768)

```bibtex
@inproceedings{sun2023adaptive,
  title={Adaptive Axonal Delays in feedforward spiking neural networks for accurate spoken word recognition},
  author={Sun, Pengfei and Eqlimi, Ehsan and Chua, Yansong and Devos, Paul and Botteldooren, Dick},
  booktitle={ICASSP 2023-2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages={1--5},
  year={2023},
  organization={IEEE}
}
```

Axonal delay for spiking spoken word recognition [Paper](https://www.frontiersin.org/articles/10.3389/fnins.2023.1275944/full)

```bibtex
@article{sun2023learnable,
  title={Learnable axonal delay in spiking neural networks improves spoken word recognition},
  author={Sun, Pengfei and Chua, Yansong and Devos, Paul and Botteldooren, Dick},
  journal={Frontiers in Neuroscience},
  volume={17},
  year={2023},
  publisher={Frontiers Media SA}}
```

SLAYER  [Paper](https://proceedings.neurips.cc/paper_files/paper/2018/hash/82f2b308c3b01637c607ce05f52a2fed-Abstract.html)

```bibtex
@InCollection{Shrestha2018,
  author    = {Shrestha, Sumit Bam and Orchard, Garrick},
  title     = {{SLAYER}: Spike Layer Error Reassignment in Time},
  booktitle = {Advances in Neural Information Processing Systems 31},
  publisher = {Curran Associates, Inc.},
  year      = {2018},
  editor    = {S. Bengio and H. Wallach and H. Larochelle and K. Grauman and N. Cesa-Bianchi and R. Garnett},
  pages     = {1419--1428},
  url       = {http://papers.nips.cc/paper/7415-slayer-spike-layer-error-reassignment-in-time.pdf},
}
```


