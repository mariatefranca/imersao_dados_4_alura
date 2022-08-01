# Projeto de Imersão de Dados 4 da Alura

## Objetivo do Projeto
Trabalhar com dados imobiliários, associados aos dados do IBGE, para desenvolver um modelo de predição de valores de imóveis para cidade de São Paulo.

## Como Usar
Este projeto usa o `conda` para gerenciar um ambiente com os pacotes necessários.

#### Ativação do `conda`
Supondo que o Anaconda3 já esteja instalado em `C:\ProgramData\Anaconda3`, toda vez que um novo prompt de comando for aberto, o `conda` precisa ser ativado com:
```commandline
C:\ProgramData\Anaconda3\Scripts\activate.bat
```
#### Criação do Ambiente
A configuração do `conda` e criação do ambiente é necessária apenas na primeira utilização.
Para que o ambiente possa ser criado de forma mais rápida, o `conda` precisa ser configurado com os seguintes comandos:

```commandline
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Depois o ambiente pode ser criado com:

```commandline
conda env create
```

A criação pode demorar alguns minutos.

#### Ativação do Ambiente e Inicialização do Jupyter
O ambiente pode ser ativado com:

```commandline
conda activate imersao_dados_4
```

E em seguida o Jupyter pode ser inicializado com:
```commandline
jupyter notebook
```
