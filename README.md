# EDA Black Friday

<p align="center">
  <img src="https://oimparcial.com.br/app/uploads/2020/11/blackfriday.2-1-1024x576.jpg" width="30%">
</p>

## Estrutura de Projeto
```plaintext
eda-black-friday/
├── README.md
├── pyproject.toml              # Arquivo de configuração utilizado pela biblioteca uv
├── data/                       # Dados brutos
│ └── black_friday_.json
├── src/                        # Códigos-fonte
│ └── analysis.ipynb            # Análise exploratória e perguntas do negócio
│ └── plot_config.py            # Classe de visualização
```

## Objetivos do Projeto
Este projeto teve como principais objetivos:

- Simular uma análise de dados com base em um conjunto fictício de vendas de um e-commerce durante a Black Friday, respondendo a perguntas hipotéticas do time de negócios (perfil de clientes, desempenho de produtos etc.).

- Praticar conceitos de Programação Orientada a Objetos (POO) através da criação de uma classe dedicada à plotagem de gráficos. Isso permitiu:
  - Evitar repetição de código na geração de visualizações.
  - Centralizar ajustes de estilo (cores, rótulos, formatação).
  - Facilitar a manutenção e reutilização em análises futuras.
  - Organizar o código de forma mais limpa e legível.

<br> 

## Tecnologias e Conceitos Aplicados
Bibliotecas Principais
- pandas (tratamento e manipulação de dados)
- pylab, matplotlib e seaborn (criação de gráficos)

Programação Orientada a Objetos (POO)
- Criação de uma classe (PlotUtils) para centralizar a geração de gráficos
- Vantagens:
  - Reutilização de código (evitando duplicação)
  - Manutenção simplificada (definir parâmetros repetitivos e ajustes de estilo em um único local)
  - Legibilidade (código modular e organizado)

<br>

## Sobre o dataset
O dataset contém os seguintes atributos:
- 550.068 observações (compras realizadas)
- 7 colunas:
  - usuario
  - produto
  - genero
  - idade
  - produto_categoria
  - valor
  - estado_civil

<br>

## Input files
- 7 arquivos no formato json

<br> 

## Instruções de Setup
0. Pré-Requisitos
    - Python versão > 3.12
    - Biblioteca uv (instale usando o comando `pipx install uv` ou `pip install uv`)


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

- Abrir o Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on macOS)
- Procure por "`Python: Select Interpreter`"
- Escolha o interpretador dentro da pasta `.venv` (e.g., .venv/bin/python or .venv\Scripts\python.exe)