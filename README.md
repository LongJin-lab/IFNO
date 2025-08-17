# Filtering Out High-frequency Components of Gradient Sequence Leads to Flat Equivalent Loss Landscape
This is the source code of IFSGD optimizer from our paper: Filtering Out High-frequency Components of Gradient Sequence Leads to Flat Equivalent Loss Landscape

## Image classification experiments on CIFAR using IFSGD
```shell
python image_classification.py --dataset_name "cifar100" --model_name "resnet18"
```

## Text classification experiments on MR using IFSGD
```shell
python text-classification-MR.py --model_name "albert-base"
```

## Text classification experiments on R8 using IFSGD
```shell
python text-classification-R8.py --model_name "albert-base"
```

## Multimodal experiments on CLIP using IFSGD
```shell
python clip_classification.py
```
