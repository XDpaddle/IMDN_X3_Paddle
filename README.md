# IMDN
Lightweight Image Super-Resolution with Information Multi-distillation Network (ACM MM 2019)
This repository contains an op-for-op Paddle reimplementation of [Lightweight Image Super-Resolution with Information Multi-distillation Network](https://arxiv.org/pdf/1909.11856v1.pdf).
It is modified from the original source code of Pytorch implementation(https://github.com/Zheng222/IMDN)

[[arXiv]](https://arxiv.org/pdf/1909.11856v1.pdf)
##Training
DIV2K dataset is used for training

## Testing
* Runing testing:
```bash
# 
python test_IMDN_X3.py --test_hr_folder Test_Datasets/Set5/ --test_lr_folder Test_Datasets/Set5_LR/x3/ --output_folder results/Set5/x3 --upscale_factor 3
```



## Results
[百度网盘](https://pan.baidu.com/s/1DY0Npete3WsIoFbjmgXQlw)提取码: 8yqj or
[Google drive](https://drive.google.com/open?id=1GsEcpIZ7uA97D89WOGa9sWTSl4choy_O)


## Citation

If you find IMDN useful in your research, please consider citing:

```
@inproceedings{Hui-IMDN-2019,
  title={Lightweight Image Super-Resolution with Information Multi-distillation Network},
  author={Hui, Zheng and Gao, Xinbo and Yang, Yunchu and Wang, Xiumei},
  booktitle={Proceedings of the 27th ACM International Conference on Multimedia (ACM MM)},
  pages={2024--2032},
  year={2019}
}

@inproceedings{AIM19constrainedSR,
  title={AIM 2019 Challenge on Constrained Super-Resolution: Methods and Results},
  author={Kai Zhang and Shuhang Gu and Radu Timofte and others},
  booktitle={The IEEE International Conference on Computer Vision (ICCV) Workshops},
  year={2019}
}

```
