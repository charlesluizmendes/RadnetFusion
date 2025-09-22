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
pip install torch
pip install numpy
pip install pandas
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

Primeiramente vamos criar o dataset com notebook:

[dataset.ipynb](https://github.com/charlesluizmendes/DataFusion/blob/feature/main/src/dataset.ipynb)

### Processamento

Após isso, vamos criar o modelo de previsão de Links com o notebook:

[processing.ipynb](https://github.com/charlesluizmendes/DataFusion/blob/feature/main/src/processing.ipynb)