# DiabetesFlask

Usando Flask para servir modelo de Machine Learning treinado sobre dados de pacientes com e sem diabetes.

![Screenshot](https://raw.githubusercontent.com/altinodantas/diabetesflask/main/static/assets/screenshot.jpg)

## Como usar

Baixar o repositório, ativar o ambiente (env) e executar o arquivo `main.py` via linha de comando. Em seguinda, acessar o endereço http://localhost:8001 no navegador. Caso seja necessário, mudar a porta na última linha do arquivo `main.py`.

* Abrir terminal
* Clonar o repositório `git clone https://github.com/altinodantas/diabetesflask.git`
* Navegar até o diretório `diabetesflask`
* Criar ambiente virtual `python3 -m venv env`
* Ativar o ambiente `source env/bin/activate`
* Instalar dependências `python -m pip install -r requirements.txt`
* Executar `python main.py`
* Acessar http://localhost:8001

## Dependências

Caso seja necessário instalar manualmente:

```bash
python -m pip install flask flask-bootstrap flask-wtf wtforms pandas numpy scikit-learn joblib
```

Ou utilizando o arquivo `requirements.txt`:

```bash
python -m pip install -r requirements.txt
```

Para realizar um novo treinamento do modelo, basta executar o arquivo `ml/train.py`.

## Dependências

* Sklearn
* Flask

  * flask_bootstrap
  * flask_wtf
* Pandas
* joblib


#### Observação:
O projeto pode apresentar avisos de compatibilidade do scikit-learn
caso o modelo treinado tenha sido gerado em outra versão da biblioteca.
Isso não impede a execução da aplicação.

---

