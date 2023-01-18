# Boas Vindas ao Repositório de exercicios em Python

## Neste epositório você vai encontrar exercícios para treinar conceitos da linguagem Python.

<br>

## Como posso começar?
<details>
<summary> Passo a Passo </summary>

1. Tenha o Python instalado em sua máquina.

> Para esses exercícios, você precisará ter instalado o [🐍 Python], [🚚 Pip] e [📚 Venv]

2. Clone este repositório

```bash
git clone 
```

3. Entre na pasta gerada

```bash
cd python-exercises
```

4. Crie o ambiente virtual que será utilizado para instalar as dependências

```bash
python3 -m venv .venv
```

5. Ative o ambiente virtual que foi criado

```bash
source .venv/bin/activate
```

6. Instale os requerimentos deste repositório 

```bash
python3 -m pip install -r dev-requirements.txt
```

7. Execute todos os testes do repositório (note que, enquanto não houver implementação nas funções, os testes falharão!)

```bash
python3 -m pytest
```

8. Execute os testes de um arquivo específico (note que, enquanto não houver implementação nas funções, os testes falharão!)

```bash
python3 -m pytest tests/<caminho/para/o/arquivo/de/teste>
```

9. Execute apenas um teste específico de um arquivo específico (note que, enquanto não houver implementação nas funções, os testes falharão!)

```bash
python3 -m pytest tests/<caminho/para/o/arquivo/de/teste>::<nome_da_função_do_teste>
```

</details>

---
