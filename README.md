# Capacitação MLFlow
Capacitação sobre o uso do MLFlow para versionamento de modelos de ML para modelos produtivos ou experimentações de pesquisa.


## Passo a passo:

0. Criar um ambiente virtual

```bash
python3 -m venv .venv
```

ou

```bash
conda create -n mlf_env python=3.10
```

1. Instalar as dependências

```bash
pip install -r requirements.txt
```

certifique-se de que o MLFlow está instalado

```bash
pip install mlflow
```

2. Rodar o MLFlow

```bash
mlflow server --host 127.0.0.1 --port 8080
```

3. Treinar o modelo

Experimente diferentes algoritmos e cobinações de parâmetros, faça feature engineering, etc.

4. Versionar o modelo

...

5. Verificar o modelo versionado no MLFlow UI

Acesse o link do MLFlow ```127.0.0.1:8080``` e veja o modelo versionado na aba "Experimentos"


## Links úteis:

[Documentação do MLFlow](https://mlflow.org/docs/latest/index.html)