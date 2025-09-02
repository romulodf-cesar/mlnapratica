# Guia de Instalação e Uso

Este projeto foi desenvolvido para iniciantes em Python e utiliza um notebook chamado `modelo1.ipynb`. Siga os passos abaixo para configurar o ambiente e começar a usar.

## 1. Instalação do Python

1. Acesse o site oficial: [python.org/downloads](https://www.python.org/downloads/)
2. Baixe a versão recomendada para seu sistema operacional.
3. Durante a instalação, marque a opção **Add Python to PATH**.
4. Finalize a instalação.

## 2. Criação do Ambiente Virtual (venv)

Abra o terminal (Prompt de Comando ou PowerShell) e navegue até a pasta do projeto:

```sh
cd caminho/para/sua/pasta
```

Crie o ambiente virtual:

```sh
python -m venv venv
```

## 3. Ativação do Ambiente Virtual

- **Windows:**

    ```sh
    venv\Scripts\activate
    ```

- **Linux/Mac:**

    ```sh
    source venv/bin/activate
    ```

Você verá o nome do ambiente (`venv`) antes do prompt, indicando que está ativo.

## 4. Sobre o Notebook `modelo1.ipynb`

O arquivo `modelo1.ipynb` é um notebook Jupyter que contém exemplos e explicações passo a passo para iniciantes em Python. Ele aborda conceitos básicos, como:

- Sintaxe do Python
- Operações matemáticas
- Estruturas de controle (if, for, while)
- Funções e variáveis

Para abrir o notebook, instale o Jupyter:

```sh
pip install notebook
```

E execute:

```sh
jupyter notebook
```

O navegador abrirá e você poderá acessar e executar os códigos do `modelo1.ipynb`.

---

**Dica:** Sempre ative o ambiente virtual antes de instalar pacotes ou executar o notebook.
