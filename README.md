# Build Python Environment for M1 MacBookPro

Ref: https://qiita.com/c60evaporator/items/aef6cc1581d2c4676504#%E3%83%91%E3%82%BF%E3%83%BC%E3%83%B31miniforge%E3%81%AB%E3%82%88%E3%82%8B%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB

# Prerequisites

# Create Virtual Env
```
conda create --name [env name] python=3.9
```
- `[env name]`: practice

## Create Virtual Env using Package List
```
conda env create -f [filename].yml
```

### Actication
```
source activate [env name]
```

### Check the env list
```
conda list
```

### Delete the env
```
conda remove -n [env name] --all

