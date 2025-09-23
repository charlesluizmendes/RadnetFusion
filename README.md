# Filtro de Kalman

Fusão de Dados utilizando filtros de Kalman.

## Ambiente

### Pacotes

Podemos instalar as dependências do projeto através do comando abaixo:

```
$ pip install -r requirements.txt
```

Ou manualmente através dos seguintes comandos:

```
pip install pandas
pip install numpy
pip install torch
pip install torch-geometric
pip install scikit-learn
pip install matplotlib
pip install nbformat
```

* Se possuir recursos de CUDA:

```
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
```

## Execução

### Dataset

[1.dataset.ipynb](https://github.com/charlesluizmendes/DataFusion/blob/main/src/1.dataset.ipynb)

### Treinamento

[2.train.ipynb](https://github.com/charlesluizmendes/DataFusion/blob/main/src/2.train.ipynb)

### Inferencia

[3.inference.ipynb](https://github.com/charlesluizmendes/DataFusion/blob/main/src/3.inference.ipynb)

### Fusion

[4.fusion.ipynb](https://github.com/charlesluizmendes/DataFusion/blob/main/src/4.fusion.ipynb)

### Kalman

[5.kalman.ipynb](https://github.com/charlesluizmendes/DataFusion/blob/main/src/4.kalman.ipynb)