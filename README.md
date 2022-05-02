# GLNet_TCYB2022
Runmin Cong, Ning Yang, Chongyi Li, Huazhu Fu, Yao Zhao, Qingming Huang, and Sam Kwong, Global-and-local collaborative learning for co-Salient object detection, IEEE Transactions on Cybernetics, 2022.

Project: https://rmcong.github.io/proj_GLNet.html

# Code and Results of GLNet:
  - Coming soon......
* Results:
  - We provide the resutls of our GLNet on Cosal2015, iCoseg, and MSRC. 
```
Baidu Cloud: https://pan.baidu.com/s/1sXBc4H3fKK8Y8ceaU4AjSQ  Password: 0224
```
* Pretrained model:
  - We provide our testing code. If you test our model, please download the pretrained model, unzip it, and put the checkpoint `model_GLNet.pth` to `Checkpoints/trained/` folder 
  and put the pretrained backbone `backbone_v.pth` to `Checkpoints/warehouse/` folder.
  - Pretrained model download:
```
Baidu Cloud: https://pan.baidu.com/s/1sXBc4H3fKK8Y8ceaU4AjSQ  Password: 0224
```

# Pytorch
* Pytorch implementation of GLNet

## Requirements

* Python 3.7
* Pytorch 1.5.1
* torchvision

## Data Preprocessing
* We resize the images of original test datasets. Please download the resized data, and put the data to `Data/` folder.
* Resized test datasets:
```
Baidu Cloud: https://pan.baidu.com/s/1sXBc4H3fKK8Y8ceaU4AjSQ  Password: 0224
```

## Test
```
python test.py
```

* You can find the results in the `'Outputs/'` folder.

# If you use our GLNet, please cite our paper:

    @article{GLNet,
        title={Global-and-local collaborative learning for co-Salient object detection},
        author={Cong, Runmin and Yang, Ning and Li, Chongyi and Fu, Huazhu and Zhao, Yao and Huang, Qingming and Kwong, Sam},
        journal={IEEE Trans. Cybern.},
        year={early access, doi: 10.1109/TCYB.2022.3169431},
        publisher={IEEE}
    }

# Contact Us:
If you have any questions, please contact Runmin Cong (rmcong@bjtu.edu.cn) or Ning Yang (ningyang@bjtu.edu.cn).
