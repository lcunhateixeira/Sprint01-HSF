# Hospital Sem Fila (HSF-API)

Este MVP faz parte do Sprint 01 da Disciplina **Desenvolvimento Full Stack Básico** 

O objetivo deste MVP é apresentar uma solução para que as pessoas possam ter uma idéia da fila para atendimento nos sistemas de saúde (Hospitais, Postos de Saúde, Unidades de Pronto Atendimento etc...).

---
## Como executar 


Será necessário ter todas as libs python listadas no `requirements.txt` instaladas.
Após clonar o repositório, é necessário ir ao diretório raiz, pelo terminal, para poder executar os comandos descritos abaixo.

> É fortemente indicado o uso de ambientes virtuais do tipo [virtualenv](https://virtualenpython -m venv .v.pypa.io/en/latest/).

```
(env)$ pip install -r requirements.txt
```

Este comando instala as dependências/bibliotecas, descritas no arquivo `requirements.txt`.

Para executar a API  basta executar:

```
(env)$ flask run --host 0.0.0.0 --port 5000
```

Abra o [http://localhost:5000/#/](http://localhost:5000/#/) no navegador para verificar o status da API em execução.
