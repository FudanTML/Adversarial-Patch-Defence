# Adversarial-Patch-Defence
## Problem Statement
A majority of prior work has focused on attacking with and defending against either small or imperceptible changes to the input. Recent work by Brown et al. [1] and Karmon et al. [2] have studied adversarial examples under a new threat model - an attacker that crafts perturbations that are not bounded by an $\epsilon$ value but are bounded to a small region or location in the image. Therefore, a form of localised and visible contiguous perturbation of image pixels emerged, known as Patch Attacks. Simultaneously, the detection and defence of practical patch attacks have gained the utmost popularity in the community concerning the security threat of CNNs. However, how to efficiently defend against this attack is still an open question. In this project, we would like you to focus on the project related to adversarial patch defense:

## Project Goals
- Adversarial patch defences based on saliency maps: Adversarial patches are observed to increase high-frequency perturbations in local regions of an image and generally do not overlap with salient objects. In localized attacks, dense clustering around perturbations is often observed in saliency, while in contrast, the output without the attack is affected by the entire image rather than a small local area, which is helpful to detect the location of patch attacks [3-4]. It is worth mentioning that none of these two empirical defences was effective enough to mitigate generalpatch attacks. In this project, we encourage you to develop saliency-based defences method and analysis saliency maps.

## Code
You may follow the following as an example
- [LGS](https://github.com/Muzammal-Naseer/local_gradients_smoothing)

## Reference
[1] Brown T B, Mané D, Roy A, et al. Adversarial patch[J]. arXiv preprint arXiv:1712.09665, 2017  
[2] Karmon D, Zoran D, Goldberg Y. Lavan: Localized and visible adversarial noise[C]//International Conference on Machine Learning. PMLR, 2018: 2507-2515.  
[3] Hayes J. On visible adversarial perturbations & digital watermarking[C]//Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops. 2018: 1597-1604.  
[4] Naseer M, Khan S, Porikli F. Local gradients smoothing: Defense against localized adversarial attacks[C]//2019 IEEE Winter Conference on Applications of Computer Vision (WACV). IEEE, 2019: 1300-1307.  
