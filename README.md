# Learning to optimize: Training deep neural networks for wireless resource management.
Python code to reproduce our works on DNN research for SPAWC 2017. 

Demo.py contains the whole process from data generation, training, testing to plotting for 10 users' IC case, even though such process done on a small dataset of 25000 samples, 94% accuracy can still be easily attained in less than 100 iterations.

In test.py, we do the testing stage for Table I: Gaussian IC case in the paper, the testing are based on the pre-trained models. To train models from scratch, please follow the instructions in the paper and read the demo.py for reference.

All codes have been tested successfully on Python 3.6.0.

### Setup
- Install python 3.6

### Running application
1. Install pip dependencies 
```
pip install -r requirements.txt
```
2. run the python files
```
python3 demo.py
```

```
python3 test.py
```

References: 
[1] Haoran Sun, Xiangyi Chen, Qingjiang Shi, Mingyi Hong, Xiao Fu, and Nikos D. Sidiropoulos, "Learning to Optimize: Training Deep Neural Networks for Interference Management," in IEEE Transactions on Signal Processing, vol. 66, no. 20, pp. 5438-5453, 15 Oct.15, 2018.


----
June 2019. Add files to generate the IMAC model in the IMAC_model folder.

----
Jan. 2021. Thanks @RameshPaul for providing the up-to-date TensorFlow 2 setup!

----
## [Update] Welcome to check out our recent work on "Learning to Continuously Optimize Wireless Resource In Episodically Dynamic Environment"

### paper available at https://arxiv.org/abs/2011.07782 (short version to appear in ICASSP 2021)
### code available at https://github.com/Haoran-S/TSP_CL

