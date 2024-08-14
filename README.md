<div>
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo clara" width="300" style="display: inline-block; vertical-align: top; margin-right: 10px;">
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo dark" width="300" style="display: inline-block; vertical-align: top;">
</div>

# Prevendo a Volatilidade do IBOV

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GeorgeTelles/modelo_preditivo_ibov_GARCH/blob/main/Previs%C3%A3o_Volatilidade_GARCH.ipynb)

Este projeto tem como objetivo prever a volatilidade do Índice Bovespa (IBOV) utilizando o modelo GARCH (Generalized AutoRegressive Conditional Heteroskedasticity). O modelo GARCH é amplamente utilizado em finanças para modelar e prever a volatilidade dos retornos de ativos financeiros.

## Sobre o Projeto

O IBOV é um dos principais índices de mercado de ações no Brasil e sua volatilidade é uma métrica importante para investidores e analistas financeiros. A volatilidade reflete a variação dos retornos de um ativo e pode fornecer insights valiosos sobre o risco e a dinâmica do mercado.

Para prever essa volatilidade, o projeto utiliza o modelo GARCH, que é uma extensão do modelo ARCH (AutoRegressive Conditional Heteroskedasticity). O GARCH é projetado para modelar séries temporais onde a variância dos erros não é constante ao longo do tempo, mas sim depende das variâncias passadas.

## Funcionalidades

- **Coleta de Dados:** Importação de dados históricos do IBOV para análise. O projeto pode utilizar APIs financeiras ou datasets disponíveis publicamente.
- **Pré-processamento de Dados:** Limpeza e preparação dos dados para a modelagem. Isso inclui a normalização dos retornos e a remoção de outliers.
- **Modelagem GARCH:** Implementação do modelo GARCH para prever a volatilidade. O projeto utiliza a biblioteca `arch` ou outras ferramentas semelhantes em Python.
- **Avaliação do Modelo:** Avaliação da precisão das previsões de volatilidade utilizando métricas adequadas. Comparação dos resultados com dados históricos para validar o modelo.
- **Visualização:** Geração de gráficos e relatórios para visualizar as previsões de volatilidade e analisar os resultados.

## Tecnologias e Bibliotecas Utilizadas

- **Python:** Linguagem de programação principal.
- **pandas e numpy:** Manipulação e análise de dados.
- **arch:** Biblioteca para modelagem GARCH e outras técnicas de volatilidade.
- **matplotlib e seaborn:** Visualização de dados e resultados.

![Descrição da Imagem](https://github.com/GeorgeTelles/modelo_preditivo_ibov_GARCH/blob/387b0d3ce8491dc3b5a0482fbb34114372fcaf26/newplot.png)



