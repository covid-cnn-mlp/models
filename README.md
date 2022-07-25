# Model overview

This model is adaptable to classification tasks using image and tabular data. 

This model is submitting to The British Journal of Radiology.

# Train
## Sample code
### Tabular
```python train.py --model MLP --criterion CrossEntropyLoss --optimizer Adam --epochs 50 --batch_size 64 --augmentation yes```

### Image
```python train.py --model DenseNet --criterion CrossEntropyLoss --optimizer Adam --epochs 50 --batch_size 64 --augmentation yes```

### Image and tabular
```python train.py --model DenseNet+MLP --criterion CrossEntropyLoss --optimizer Adam --epochs 50 --batch_size 64 --augmentation yes```

# Test
## Sample code
```python test.py```

Note that this code is implemented to use afeter running codes of train.py

# Enviroment
CUDA version 11.3 or 11.4

PyTorch version 1.10
