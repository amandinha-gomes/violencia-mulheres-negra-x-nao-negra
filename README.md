# Análise da Violência Letal Contra Mulheres no Brasil (2000–2022)

Este projeto tem como objetivo analisar a taxa de homicídios de mulheres negras em comparação com mulheres não negras no Brasil, com foco especial no estado de São Paulo. A análise foi feita com Python e as visualizações foram geradas para destacar desigualdades regionais e temporais.

## 🔍 Objetivos
- Comparar a evolução da taxa de homicídios de mulheres negras e não negras ao longo dos anos.
- Analisar a desigualdade racial de gênero no estado de São Paulo.
- Visualizar a diferença de taxas entre os estados brasileiros em 2022.
- Sensibilizar para a importância de dados abertos no combate à violência de gênero e raça.

## 📁 Dados Utilizados
- Base de dados: IPEA | Atlas da Violência
- Período analisado: 2000 a 2022
- Variáveis principais:
  - nome (sigla do estado)
  - período (ano)
  - valor (taxa de homicídio por 100 mil mulheres)

## 🛠️ Tecnologias e Ferramentas
- Python 3
- pandas
- matplotlib
- seaborn
- Google Colab

## 📈 Resultados
### 1. Evolução da taxa de homicídios no estado de São Paulo
Gráfico comparativo entre mulheres negras e não negras no período de 2000 a 2022: <br>
📉 Observação: Há uma tendência de queda nas taxas para ambos os grupos, porém as mulheres negras mantêm taxas superiores ao longo de todo o período analisado.

### 2. Diferença entre as taxas de homicídios (2022)
Visualização da diferença entre as taxas de homicídio de mulheres negras e não negras em cada estado do Brasil em 2022: <br>
🗺️ Estados como Roraima, Rondônia e Mato Grosso apresentaram as maiores desigualdades. <br>

## 🔬 Análises Estatísticas
- 🧪 Teste t de Student:
  - Estatística t = 1.619
- Valor-p = 0.1150
  - ➤ Conclusão: A diferença entre as médias de SP para negras e não negras não é estatisticamente significativa a 5%.

- 📊 Regressão linear (tendência temporal em SP):
  - Mulheres negras: coeficiente = -0.274 → tendência de queda
  - Mulheres não negras: coeficiente = -0.150 → tendência de queda
 
## ✅ Conclusões
- As mulheres negras apresentam taxas consistentemente maiores do que mulheres não negras.
- Em alguns estados, como RR, RO e MT, a desigualdade é ainda mais acentuada.
- Em São Paulo, observamos uma redução na taxa geral, mas a diferença entre os grupos permanece ao longo dos anos.
- A análise estatística sugere tendência de melhora, mas a desigualdade estrutural persiste.

