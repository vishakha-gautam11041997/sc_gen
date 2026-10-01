<div align="center"> <h1>Scn-Genesis </h1> </div>
 <br>
<div align="center">
<img src="Data/Image/Asset 2.png"></div>

<div align="center"><b>Title</b></div><br><br>





# User Guide for Running Analysis Scripts

## Section 1: Setting Up Environments

Environments have been used in the all modules; users need to use .yml files to set these environments. 


| Environment Name | Details |
| --- | --- |
| environment.yml | For training models |



```bash
conda env create -f environment.yml
```


## Section 2: CycleGAN Module
1. Use conda environment 

```bash
conda activate environment
```

2. Download pre-trained models to run analysis

```bash
  wget zenodo
```

3. Use Train_script.ipynb for the prediction modules.

---
## Section 3: Cell type label predictor
1. Use conda environment 

```bash
conda activate environment
```

2. Download pre-trained models to run analysis

```bash
  wget zenodo
```

3. Use ML_Scripts_leave_one_out.ipynb for the ML modules.

---

