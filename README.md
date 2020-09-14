# active-learning-with-ensemble

- Active-learning with ensemble  
  1. Train ensemble models.
  2. Evaluate uncertainty using ensemble models.
  3. Selects unlabeled samples with the highest uncertainty.

- Dependencies
  - Python 3.6+
  - PyTorch==1.6
  - Dataset: [MVTec Anomaly Detection Dataset]
  

### Train model
* Run the following command.
```
python trainActiveLearning.py --target bottle --model resnet18 -c 0 --lr 0.001
```

