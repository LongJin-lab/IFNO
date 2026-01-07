# Integration-Filter-Enhanced Neurodynamics Optimizer: Filtering Out High-frequency Components of Gradient Sequence Leads to Flat Equivalent Loss Landscape
This is the source code of IFNO optimizer from our paper: Integration-Filter-Enhanced Neurodynamics Optimizer: Filtering Out High-frequency Components of Gradient Sequence Leads to Flat Equivalent Loss Landscap

## Image classification experiments on CIFAR using IFNO
```shell
python image_classification.py --dataset_name "cifar100" --model_name "resnet18"
```

## Text classification experiments on MR using IFNO
```shell
python text-classification-MR.py --model_name "albert-base"
```

## Text classification experiments on R8 using IFNO
```shell
python text-classification-R8.py --model_name "albert-base"
```

## Multimodal experiments on CLIP using IFNO
```shell
python clip_classification.py
```
