# Temporal Action Localization paper

## Paper & code

### weakly-supervised
- [**W-TALC**](https://arxiv.org/abs/1807.10418) (*ECCV18*) W-TALC: Weakly-supervised Temporal Activity Localization and Classification [tensorflow](https://github.com/sujoyp/wtalc-tensorflow), [pytorch](https://github.com/sujoyp/wtalc-pytorch)
- [**STPN**](http://openaccess.thecvf.com/content_cvpr_2018/html/Nguyen_Weakly_Supervised_Action_CVPR_2018_paper.html) (*CVPR18*) Weakly Supervised Action Localization by Sparse Temporal Pooling Network [tensorflow](https://github.com/bellos1203/STPN), [pytorch](https://github.com/demianzhang/weakly-action-localization)
- [**ASSG**](https://dl.acm.org/doi/abs/10.1145/3343031.3351044) (*ACM19*) Adversarial Seeded Sequence Growing for Weakly-Supervised Temporal Action Localization
- [**TSM**](http://openaccess.thecvf.com/content_ICCV_2019/html/Yu_Temporal_Structure_Mining_for_Weakly_Supervised_Action_Detection_ICCV_2019_paper.html) (*ICCV19*) Temporal Structure Mining for Weakly Supervised Action Detection
- [**STAR**](https://www.aaai.org/ojs/index.php/AAAI/article/view/4939) (*AAAI19*) Segregated Temporal Assembly Recurrent Networks for Weakly Supervised Multiple Action Detection
- [**3C-Net**](http://openaccess.thecvf.com/content_ICCV_2019/html/Narayan_3C-Net_Category_Count_and_Center_Loss_for_Weakly-Supervised_Action_Localization_ICCV_2019_paper.html) (*ICCV19*) 3C-Net: Category Count and Center Loss for Weakly-Supervised Action Localization [pytorch](https://github.com/naraysa/3c-net)
- [**CMCS**](http://openaccess.thecvf.com/content_CVPR_2019/html/Liu_Completeness_Modeling_and_Context_Separation_for_Weakly_Supervised_Temporal_Action_CVPR_2019_paper.html) (*CVPR19*) Completeness Modeling and Context Separation for Weakly Supervised
Temporal Action Localization [pytorch](https://github.com/Finspire13/CMCS-Temporal-Action-Localization)
- [**MAAN**](https://arxiv.org/abs/1905.08586) (*ICLR19*) Marginalized Average Attentional Network for Weakly-Supervised Learning [pytorch](https://github.com/yyuanad/MAAN)
- [**BaSNet**](https://arxiv.org/abs/1911.09963) (*AAAI20*) Background Suppression Network for Weakly-supervised Temporal Action Localization [pytorch](https://github.com/Pilhyeon/BaSNet-pytorch)
- [**Nguyen et al.**](http://openaccess.thecvf.com/content_ICCV_2019/html/Nguyen_Weakly-Supervised_Action_Localization_With_Background_Modeling_ICCV_2019_paper.html) (*ICCV19*) Weakly-supervised Action Localization with Background Modeling
- [**EM-MIL**](https://arxiv.org/pdf/2004.00163.pdf) Weakly-Supervised Action Localization with Expectation-Maximization Multi-Instance Learning


### fully-supervised
- [**S-CNN**](http://openaccess.thecvf.com/content_cvpr_2016/html/Shou_Temporal_Action_Localization_CVPR_2016_paper.html) (*CVPR16*) Temporal Action Localization in Untrimmed Videos via Multi-stage CNNs [caffe](https://github.com/zhengshou/scnn)
- [**P-GCN**](http://openaccess.thecvf.com/content_ICCV_2019/html/Zeng_Graph_Convolutional_Networks_for_Temporal_Action_Localization_ICCV_2019_paper.html) (*ICCV19*) Graph Convolutional Networks for Temporal Action Localization [pytorch](https://github.com/Alvin-Zeng/PGCN)
- [**C-TCN**](https://arxiv.org/abs/1908.09442) (*ICCV19*) Deep Concept-wise Temporal Convolutional Networks for Action Localization
- [**Joshua et al.**](http://openaccess.thecvf.com/content_WACVW_2020/html/w5/Gleason_Activity_Detection_in_Untrimmed_Videos_Using_Chunk-based_Classifiers_WACVW_2020_paper.html) (*WACV20*) Activity Detection in Untrimmed Videos Using Chunk-based Classifiers

## Experiments (THUMOS14)

- Thumos14 data download : [link](https://www.crcv.ucf.edu/THUMOS14/download.html)
- C3D feature : [link](https://github.com/wzmsltw/BSN-boundary-sensitive-network/issues/24)
- I3D feature : [link1](https://emailucr-my.sharepoint.com/personal/sujoy_paul_email_ucr_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fsujoy%5Fpaul%5Femail%5Fucr%5Fedu%2FDocuments%2Fwtalc%2Dfeatures&originalPath=aHR0cHM6Ly9lbWFpbHVjci1teS5zaGFyZXBvaW50LmNvbS86ZjovZy9wZXJzb25hbC9zdWpveV9wYXVsX2VtYWlsX3Vjcl9lZHUvRXMxemJIUVk0UHhLaFVrZGd2V0h0VTBCSy1feXVnYVNqWEs4NGtXc0IwWEQwdz9ydGltZT1mRmxCOTZIUTEwZw)(from [here](https://github.com/sujoyp/wtalc-pytorch)) or [link2](https://drive.google.com/file/d/1NsVN2SPYEcS6sDnN4sfv2cAl0B0I8sp3/view)(from [here](https://github.com/Pilhyeon/BaSNet-pytorch))
  - extraction code : [link2](https://github.com/piergiaj/pytorch-i3d)
```
# link2
├── THUMOS14
   ├── gt.json
   ├── split_train.txt
   ├── split_test.txt
   └── features
       ├── train
           ├── rgb
               ├── video_validation_0000051.npy
               ├── video_validation_0000052.npy
               └── ...
           └── flow
               ├── video_validation_0000051.npy
               ├── video_validation_0000052.npy
               └── ...
       └── test
           ├── rgb
               ├── video_test_0000004.npy
               ├── video_test_0000006.npy
               └── ...
           └── flow
               ├── video_test_0000004.npy
               ├── video_test_0000006.npy
               └── ...
```
- UNet : [link1](https://onedrive.live.com/?cid=b3a6589c924973b9&id=B3A6589C924973B9%2133792&authkey=!ACJJB7BMDWi3540) or [link2](https://pan.baidu.com/s/1ussSNpI1nsXc7TpuT7inVA)

### weakly-supervised

||conference|name|0.1|0.2|0.3|0.4|0.5|0.6|0.7|0.8|0.9|code|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|1|ECCV(2018)|W-TALC|55.2|49.6|40.1|31.1|22.8|-|7.6|-|-|[tensor](https://github.com/sujoyp/wtalc-tensorflow), [pytorch](https://github.com/sujoyp/wtalc-pytorch)|
|2|CVPR(2018)|STPN|52.0|44.7|35.5|25.8|16.9|9.9|4.3|1.2|0.1|[tensor](https://github.com/bellos1203/STPN), [pytorch](https://github.com/demianzhang/weakly-action-localization)|
|3|ACM(2019)|ASSG|65.6|59.4|50.4|38.7|25.4|15.0|6.6||||
|4|ICCV(2019)|TSM|||39.5||24.5||7.1|||
|5|AAAI(2019)|STAR|**68.8**|**60.0**|48.7|34.7|23.0|-|-|-|-||
|6|ICCV(2019)|3C-Net|59.1|53.5|44.2|34.1|26.6|-|8.1|-|-|[pytorch](https://github.com/naraysa/3c-net)|
|7|CVPR(2019)|CMCS|57.4|50.8|41.2|32.1|23.1|15.0|7.0|-|-|[pytorch](https://github.com/Finspire13/CMCS-Temporal-Action-Localization)|
|8|ICLR(2019)|MAAN|59.8|50.8|41.1|30.6|20.3|12.0|6.9|-|-|[pytorch](https://github.com/yyuanad/MAAN)|
|9|AAAI(2020)|BaSNet|58.2|52.3|44.6|36.0|27.0|18.6|10.4|3.9|0.5|[pytorch](https://github.com/Pilhyeon/BaSNet-pytorch)|
|10|ICCV(2019)|Nguyen et al.|60.4|56.0|**46.6**|**37.5**|26.8|17.6|9.0|3.3|0.4||
|11||EM-MIL|59.1|52.7|45.5|36.8|**30.5**|**22.7**|**16.4**|-|-||

### fully-supervised

||conference|name|0.1|0.2|0.3|0.4|0.5|0.6|0.7|0.8|0.9|code|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|1|CVPR(2016)|S-CNN|47.7|60.0|48.7|34.7|23.0|-|-|-|-|[caffe](https://github.com/zhengshou/scnn)|
|2|ICCV(2019)|P-GCN|69.5|67.8|63.6|57.8|49.1|-|-|-|-|[pytorch](https://github.com/Alvin-Zeng/PGCN)|
|3|ICCV(2019)|C-TCN|**72.2**|**71.4**|**68.0**|**62.3**|**52.1**|-|-|-|-||
|4|WACV(2020)|Joshua et al.|67.41|60.0|48.7|34.7|23.0|-|-|-|-||
