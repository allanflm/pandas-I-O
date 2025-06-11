# Pandas I/O: Exemplos de Leitura e Escrita de Arquivos

Este repositório contém um notebook Jupyter (`.ipynb`) com exemplos práticos de como realizar operações de entrada (Input) e saída (Output) de dados utilizando a biblioteca **Pandas** em Python. O objetivo é demonstrar a leitura e escrita de diversos formatos de arquivo, uma tarefa fundamental na rotina de qualquer profissional de dados.

---

## 🚀 Tópicos Abordados

O notebook explora as seguintes funcionalidades do Pandas para manipulação de arquivos:

-   **Leitura de Arquivos:**
    -   Arquivos CSV (`.csv`)
    -   Arquivos JSON (`.json`)
    -   Arquivos de texto com separadores (`.txt`)
    -   Planilhas Excel (`.xlsx`)
    -   Tabelas HTML diretamente de uma URL da web

-   **Escrita de Arquivos:**
    -   Salvando DataFrames em formato CSV
    -   Exportando dados para formato JSON
    -   Gravando dados em planilhas Excel

---

## 📊 Dataset

O conjunto de dados utilizado nos exemplos é o `imoveis_residenciais.csv`, que contém informações fictícias sobre imóveis residenciais, servindo como base para as demonstrações de leitura e processamento.

---

## 🛠️ Como Executar o Projeto

Para visualizar e executar o notebook em sua máquina local, siga os passos abaixo.

### Pré-requisitos

-   [Python 3.x](https://www.python.org/downloads/) instalado.
-   [Git](https://git-scm.com/downloads) instalado para clonar o repositório.

### Passos

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/allanflm/pandas-I-O.git](https://github.com/allanflm/pandas-I-O.git)
    cd pandas-I-O
    ```

2.  **Crie e ative um ambiente virtual (recomendado):**
    ```bash
    # Cria o ambiente virtual
    python -m venv venv

    # Ativa o ambiente no Windows
    .\venv\Scripts\activate

    # Ativa o ambiente no macOS/Linux
    source venv/bin/activate
    ```

3.  **Instale as dependências:**
    O projeto possui um arquivo `requirements.txt` com todas as bibliotecas necessárias.
    ```bash
    pip install -r requirements.txt
    ```

4.  **Inicie o Jupyter Lab:**
    ```bash
    jupyter lab
    ```

5.  Após iniciar o Jupyter Lab no seu navegador, abra o notebook **`Lendo e escrevendo arquivos.ipynb`** para ver e executar os exemplos.

---

## 💻 Tecnologias Utilizadas

-   **[Python](https://www.python.org/)**
-   **[Pandas](https://pandas.pydata.org/)**: Para manipulação e análise de dados.
-   **[Jupyter Lab](https://jupyter.org/)**: Para a criação e execução do notebook interativo.
-   **[Numpy](https://numpy.org/)**: Para operações numéricas.
-   **[Matplotlib](https://matplotlib.org/)** e **[Seaborn](https://seaborn.pydata.org/)**: Para visualização de dados.
-   **[Openpyxl](https://openpyxl.readthedocs.io/en/stable/)**: Dependência para o Pandas ler e escrever arquivos Excel.
