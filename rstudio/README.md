# RStudio image

RStudio image.

A standalone deployment file using the Kubeflow Notebook Controller is available: `rstudio-example.yaml`

## Standard images

Build example from CentOS Stream 9 with Python 3.9:

```bash
make c9s-py39 RELEASE=dev DATE=20230101
```

## CUDA images

Build example from CentOS Stream 9 with Python 3.9 with CUDA:

```bash
make cuda-c9s-py39 RELEASE=dev DATE=20230101
```
