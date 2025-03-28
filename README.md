# EDA Black Friday

<p align="center">
  <img src="https://oimparcial.com.br/app/uploads/2020/11/blackfriday.2-1-1024x576.jpg" alt="image">
</p>

## Estrutura de Projeto
```plaintext
eda-black-friday/
├── code/                   # Contém os Jupyter notebooks com a análise exploratória e as perguntas do negócio
├── data/                   # Contém as bases JSON
├── pyproject.toml          # Arquivo de configuração utilizado pela biblioteca uv
└── README.md               # Esse arquivo
```

## Sobre o dataset
O dataset que contém dados de vendas em um e-commerce na Black Friday, com os seguintes atributos:
- 550.068 observações (compras realizadas)
- 7 colunas:
  - usuario
  - produto
  - genero
  - idade
  - produto_categoria
  - valor
  - estado_civil


## Input files:
- 7 arquivos no formato json

<br> 

----

## Instruões de Setup
### Pré-Requisitos

Certifique-se de ter instalado em sua máquina:

- Python versão 3.12
- uv (instale usando o comando `pipx install uv` ou `pip install uv`)
- Visual Studio Code

<br>

1. Clone o repositório e mude o diretório
```bash
git clone https://github.com/kajinmo/eda-black-friday
cd eda-black-friday
```

<br>

2. Crie um ambiente venv e instale as dependências com `uv`
```bash
uv sync
```

<br>

3. Ative o ambiente virtual
```bash
source .venv/Scripts/activate
```

<br>

4. Abra o VSCode
```bash
code .
```

<br>

5. Configurar o VSCode para usar o ambiente virtual

- Abrir o Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on macOS).
- Procure por "`Python: Select Interpreter`".
- Escolha o interpretador dentro da pasta `.venv` (e.g., .venv/bin/python or .venv\Scripts\python.exe).

6. Agora você está pronto para rodar o código na sua máquina!