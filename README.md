# Previsão de Preços

Esse projeto foi feito para fins de estudos de ML utilizando Python. O modelo treinado é capaz de prever os preços de pizzas a partir da medida de seu diâmetro (cm). 

---

## Estrutura do projeto

```bash
├── datasets/             # Diretório reservado para datasets
│   └── pizzas.csv        # Dataset de preços a partir dos diâmetros
├── .gitignore            # Arquivos ignorados pelo Git
├── app.py                # Código principal
├── README.md             # Documentação do projeto
├── requirements.txt      # Dependências do projeto
└── testes.ipynb          # Notebook Python para testes de treinamento
```

---

## Módulos utilizados
- **Pandas**: Leitura do Dataset
- **Scikit Learn**: Treinamento do modelo
- **Streamlit**: Renderização da página web

---

## Como utilizar

1. Instale as dependências
    ```bash
    pip install -r requirements.txt
    ```

2. Execute o projeto com Streamlit
    ```bash
    streamlit run app.py
    ```
Agora é só testar as previsões de preço feitas pelo modelo.