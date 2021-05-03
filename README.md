## Band Representation-Based Semi-Supervised Low-Light Image Enhancement: Bridging the Gap Between Signal Fidelity and Perceptual Quality (TIP'2021)

[Wenhan Yang](https://flyywh.github.io/index.html), 
[Shiqi Wang](https://www.cs.cityu.edu.hk/~shiqwang/), 
[Yuming Fang](https://sites.google.com/site/leofangyuming/), 
Yue Wang,
and [Jiaying Liu](http://www.icst.pku.edu.cn/struct/people/liujiaying.html) 

[[Paper Link]](http://39.96.165.147/Pub%20Files/2021/ywh_tip21_2.pdf)
[[Project Page]](https://github.com/flyywh/TIP-2021-Deep-Recursive-Band-Network)

### Abstract

It has been widely acknowledged that under-exposure causes a variety of visual quality degradation because of intensive noise, decreased visibility, biased color, etc. To alleviate these issues, a novel semi-supervised learning approach is proposed in this paper for low-light image enhancement. More specifically, we propose a deep recursive band network (DRBN) to recover a linear band representation of an enhanced normal-light image based on the guidance of the paired low/normal-light images. Such design philosophy enables the principled network to generate a quality improved one by reconstructing the given bands based upon another learnable linear transformation which is perceptually driven by an image quality assessment neural network. On one hand, the proposed network is delicately developed to obtain a variety of coarseto-fine band representations, of which the estimations benefit each other in a recursive process mutually. On the other hand, the extracted band representation of the enhanced image in the recursive band learning stage of DRBN is capable of bridging the gap between the restoration knowledge of paired data and the perceptual quality preference to high-quality images. Subsequently, the band recomposition learns to recompose the band representation towards fitting perceptual regularization of high-quality images with the perceptual guidance. The proposed architecture can be flexibly trained with both paired and unpaired data. Extensive experiments demonstrate that our method produces better enhanced results with visually pleasing contrast and color distributions, as well as well-restored structural details.

#### If you find the resource useful, please cite the following :- )

```
@ARTICLE{Yang_2021_TIP_DRBN,
  author={Yang, Wenhan and Wang, Shiqi and Fang, Yuming and Wang, Yue and Liu, Jiaying},
  journal={IEEE Transactions on Image Processing}, 
  title={Band Representation-Based Semi-Supervised Low-Light Image Enhancement: Bridging the Gap Between Signal Fidelity and Perceptual Quality}, 
  year={2021},
  volume={30},
  number={},
  pages={3461-3473},
  doi={10.1109/TIP.2021.3062184}}
```
<img src="teaser/teaser_DRBN.png" > 

## Installation:
(TBD)


## Contact

If you have questions, you can contact `yangwenhan@pku.edu.cn`.
A timely response is promised, if the email is sent by your affliaton email with your signed name.
