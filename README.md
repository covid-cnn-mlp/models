# Model overview

This model is adaptable to classification tasks using image and tabular data. 

This model is submitting to The British Journal of Radiology.

# Train
## Sample code
```python train.py --model DenseNet --criterion CrossEntropyLoss --optimizer Adam --epochs 50 --batch_size 64 --resize_size 256 --augmentation yes --load_image yes --gpu_ids 0,1,2```

# Test
## Sample code
```python test.py```

Note that this code is implemented to use afeter running codes of train.py
