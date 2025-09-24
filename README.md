# Data Fusion

Projeto da Disciplina Fusão de Dados, utilizando a fusão do modelo GNN treinado com métricas físicas da Rede Adhoc, com métricas do protocolo RADNET, aplicado a filtro de Kalman.

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
```

* Se possuir recursos de CUDA:

```
pip install torch --index-url https://download.pytorch.org/whl/cu121
```

## Execução

Para testar o experimento basta executar os [notebooks](https://github.com/charlesluizmendes/DataFusion/blob/main/src) na ordem em que se encontram.