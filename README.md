<<<<<<< HEAD
# anomaly-detection

- Anomaly detection  
  1. vanilla CNN (supervised)
  2. resnet18 (supervised)

- Dependencies
  - Python 3.6+
  - PyTorch==1.3
  - Dataset: [MVTec Anomaly Detection Dataset]
  
  
### Dataset structure

```
./data   
│
├── bottle
│   ├── ground_truth
│   ├── train
│   └── test
│
├── carpet
├── leather
├── grid

```

### Train model
* Run the following command.
```
python train.py --target bottle --model resnet18 -c 0 --lr 0.001
```
  
### Reference
1. [bayesian-optimization python library]


[MVTec Anomaly Detection Dataset]: https://www.mvtec.com/company/research/datasets/mvtec-ad/
[bayesian-optimization python library]: https://github.com/fmfn/BayesianOptimization
   
=======
# active-learning-with-ensemble
>>>>>>> 7be7dc7e4e043845c8e9ed2b41b674c577f67a26
