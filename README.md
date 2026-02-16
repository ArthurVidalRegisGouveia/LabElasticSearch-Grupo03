## Como executar o notebook?

1. Instale [uv](https://github.com/astral-sh/uv)
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

2. Instale o requirements.txt
```bash
uv add -r requirements.txt
```

3. Crie um kernel para utilizar no notebook jupyter
```bash
uv run python -m ipykernel install \
  --user \
  --name lab-elastic-venv \
  --display-name "Python (lab-elastic)"
```

4. Inicie o notebook 
```bash
jupyter notebook
```

5. Após entrar o notebook desejado, selecione no canto superior direito o kernel criado `Python (lab-elastic)`
