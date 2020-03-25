# Temporal-Action-Detection-paper

## Paper & code

### weakly-supervised
- **W-TALC** (*ECCV18*) W-TALC: Weakly-supervised Temporal Activity Localization and Classification [pytorch](https://github.com/sujoyp/wtalc-pytorch), [tensorflow](https://github.com/sujoyp/wtalc-tensorflow)
- **STPN** (*CVPR18*) Weakly Supervised Action Localization by Sparse Temporal Pooling Network [tensorflow](https://github.com/bellos1203/STPN), [pytorch](https://github.com/demianzhang/weakly-action-localization)
- **STAR** (*AAAI19*) Segregated Temporal Assembly Recurrent Networks for Weakly Supervised Multiple Action Detection
- **3C-Net** (*ICCV19*) 3C-Net: Category Count and Center Loss for Weakly-Supervised Action Localization [pytorch](https://github.com/naraysa/3c-net)
- **CMCS** (*CVPR19*) Completeness Modeling and Context Separation for Weakly Supervised
Temporal Action Localization [pytorch](https://github.com/Finspire13/CMCS-Temporal-Action-Localization)
- **MAAN** (*ICLR19*) Marginalized Average Attentional Network for Weakly-Supervised Learning [pytorch](https://github.com/yyuanad/MAAN)
- **BaSNet** (*AAAI20*) Background Suppression Network for Weakly-supervised Temporal Action Localization [pytorch](https://github.com/Pilhyeon/BaSNet-pytorch)


### fully-supervised
- **SCNN** (*CVPR16*)
- **Joshua et al.** (*WACV20*) Activity Detection in Untrimmed Videos Using Chunk-based Classifiers
- **P-GCN** (*ICCV19*) 
- **C-TCN** (*ICCV19*)

## Score (THUMOS14)

### weakly-supervised

||conference|name|0.1|0.2|0.3|0.4|0.5|0.6|0.7|0.8|0.9|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|1|ECCV(2018)|W-TALC|55.2|49.6|40.1|31.1|22.8|-|7.6|-|-|
||CVPR(2018)|STPN|
|2|AAAI(2019)|STAR|68.8|60.0|48.7|34.7|23.0|-|-|-|-|
|3|ICCV(2019)|3C-Net|59.1|53.5|44.2|34.1|26.6|-|8.1|-|-|
|4|CVPR(2019)|CMCS|57.4|50.8|41.2|32.1|23.1|15.0|7.0|-|-|
|5|ICLR(2019)|MAAN|59.8|50.8|41.1|30.6|20.3|12.0|6.9|-|-|
|6|AAAI(2020)|BaSNet|58.2|52.3|44.6|36.0|27.0|18.6|10.4|3.9|0.5|

### fully-supervised

||conference|name|0.1|0.2|0.3|0.4|0.5|0.6|0.7|0.8|0.9|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|1|CVPR(2016)|SCNN|47.7|60.0|48.7|34.7|23.0|-|-|-|-|
|2|WACV(2020)|Joshua et al.|67.41|60.0|48.7|34.7|23.0|-|-|-|-|
|3|ICCV(2019)|P-GCN|69.5|67.8|63.6|57.8|49.1|-|-|-|-|
|4|ICCV(2019)|C-TCN|72.2|71.4|68.0|62.3|52.1|-|-|-|-|
