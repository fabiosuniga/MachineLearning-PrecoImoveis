# Previsão de Valores de Imóveis com Machine Learning

Este é um projeto prático de **Machine Learning** focado na construção de um modelo de **Regressão Linear**. O objetivo do script é estimar o valor de mercado de um imóvel com base nas suas características físicas e de localização, simulando um cenário real de análise de dados no mercado imobiliário.

## Tecnologias e Bibliotecas Utilizadas
- **Python 3**
- **Pandas:** Para leitura, manipulação e estruturação da base de dados.
- **Scikit-Learn:** Para a criação, treino e aplicação do modelo de Regressão Linear.
- **Jupyter Notebook:** Como ambiente de desenvolvimento e execução interativa.

## Estrutura do Repositório
- `MachineLearning(PrevisãoImovel).ipynb`: O caderno principal contendo todo o código documentado, desde a importação dos dados até a previsão final.
- `TabelaDeImoveis.xlsx`: A base de dados (dataset) em formato Excel utilizada para treinar o modelo, contendo variáveis de tamanho, acabamento, localização, entre outras.
- `requirements.txt`: Lista de dependências necessárias para replicar o ambiente do projeto.

## Como o Modelo Funciona
O algoritmo foi treinado para analisar as seguintes variáveis (features) de um imóvel:
1. **Tamanho:** Área em metros quadrados.
2. **Acabamento:** Nota qualitativa de 1 a 5.
3. **Localização:** Nota qualitativa de 1 a 5.
4. **Piscina:** Presença (1) ou ausência (0).
5. **Garagem:** Quantidade de vagas.
6. **Tipo:** Classificação entre Apartamento (0) ou Casa (1).

Após o treino, o modelo solicita a inserção de novos dados através de inputs interativos e retorna a previsão em Reais (R$).

## Como executar este projeto na sua máquina

1. **Clone este repositório:**
   ```bash
   git clone [https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git](https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git)

2. **Acesse a pasta do projeto:**
   ```bash
   cd SEU-REPOSITORIO

3. **Instale as bibliotecas necessárias:**
   ```bash
   pip install -r requirements.txt

1. **Execute o Jupyter Notebook:**
  Abra o ficheiro MachineLearning(PrevisãoImovel).ipynb no seu IDE favorito (como PyCharm, VS Code) ou via navegador executando jupyter notebook no terminal, e corra as células sequencialmente.

Projeto desenvolvido para fins de estudo e prática de conceitos de Data Science e Machine Learning.
