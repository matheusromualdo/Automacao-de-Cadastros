# 🐍 Product Registration Automation with Python - EN

This project was developed during the **Python Bootcamp** offered by [Hashtag Treinamentos](https://www.hashtagtreinamentos.com/).  
It automates the login and product registration process in a web system using **PyAutoGUI** and **Pandas**.

## 🚀 Features

- Automatically opens the browser
- Logs into the system
- Automatically fills out the form with data from a `.csv` file
- Bulk registration of multiple products

## 🧰 Technologies Used

- [Python](https://www.python.org/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/)
- [Pandas](https://pandas.pydata.org/)

## 📁 Files

- `main.py`: main automation script
- `produtos.csv`: product database to be registered

## 🔧 Requirements

- Python installed on your machine (version 3.7+)
- Install the necessary libraries:

```bash
pip install pyautogui pandas
```

## 📝 How to Use

1. Make sure the `produtos.csv` file is in the same directory as `main.py`.
2. Run the script with:

```bash
python main.py
```

3. The script will open the browser, access the system, and begin registering the products from the spreadsheet automatically.

⚠️ **Important**:  
This project uses fixed coordinates for clicks with `pyautogui`, so you may need to adjust the `x, y` positions according to your screen/resolution.

## 📷 Sample Spreadsheet (`produtos.csv`)

```csv
codigo,marca,tipo,categoria,preco_unitario,custo,obs
001,Nike,Sneakers,Sports,299.90,199.90,Top quality
002,Adidas,Sneakers,Casual,249.90,149.90,
...
```

## 🤝 Acknowledgements

Project based on the content from the **Python Bootcamp by Hashtag Treinamentos** 💙




# 🐍 Automacao de Cadastro de Produtos com Python - PT-BR

Este projeto foi desenvolvido durante o **Intensivão de Python** promovido pela [Hashtag Treinamentos](https://www.hashtagtreinamentos.com/).  
Ele automatiza o processo de login e cadastro de produtos em um sistema web usando as bibliotecas **PyAutoGUI** e **Pandas**.

## 🚀 Funcionalidades

- Abertura automática do navegador
- Acesso ao sistema de login
- Preenchimento automático do formulário com dados de um arquivo `.csv`
- Cadastro em lote de diversos produtos

## 🧰 Tecnologias Utilizadas

- [Python](https://www.python.org/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/)
- [Pandas](https://pandas.pydata.org/)

## 📁 Arquivos

- `main.py`: script principal de automação
- `produtos.csv`: base de dados com os produtos a serem cadastrados

## 🔧 Requisitos

- Python instalado na máquina (versão 3.7+)
- Instalar as bibliotecas necessárias:

```bash
pip install pyautogui pandas
```

## 📝 Como usar

1. Certifique-se de que o arquivo `produtos.csv` está no mesmo diretório do `main.py`.
2. Execute o script com:

```bash
python main.py
```

3. O script vai abrir o navegador, acessar o sistema e começar a cadastrar os produtos da planilha automaticamente.

⚠️ **Importante**:  
Este projeto usa coordenadas fixas para cliques com `pyautogui`, então pode ser necessário ajustar as posições `x, y` de acordo com sua tela/resolução.

## 📷 Exemplo da Planilha (`produtos.csv`)

```csv
codigo,marca,tipo,categoria,preco_unitario,custo,obs
001,Nike,Tênis,Esportivo,299.90,199.90,Top de linha
002,Adidas,Tênis,Casual,249.90,149.90,
...
```

## 🤝 Agradecimentos

Projeto criado com base no conteúdo do **Intensivão de Python da Hashtag Treinamentos** 💙

