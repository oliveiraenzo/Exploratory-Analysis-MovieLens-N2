# 📊 Atividade N2 - 1º Bimestre

Este repositório contém a solução da Atividade Avaliativa N2 do 1º Bimestre da disciplina de Análise de Dados. O objetivo é realizar uma análise exploratória do conjunto de dados [MovieLens (Small)](https://grouplens.org/datasets/movielens/) e responder a algumas perguntas sobre o comportamento dos usuários e as características dos filmes avaliados.

---

## 📁 Estrutura do Projeto

atividade-n2-movielens/ 
├── data/ # Arquivos do dataset 
├── notebook/ 
│ └── atividade_n2_movielens.ipynb 
├── requirements.txt 
└── README.md

---

## ✅ Critérios Avaliados e Respostas

### 📌 Questão 1 – Análise Exploratória

#### **(a) Existe alguma correlação entre o ano de lançamento do filme e sua avaliação média?**  
📈 **Resposta:**
Analisando os dados, foi possível calcular a média das avaliações dos filmes agrupados por ano de lançamento. Observou-se uma **correlação fraca e negativa** entre o ano de lançamento e a média das avaliações (correlação de aproximadamente `-0.350`). Isso indica que **filmes mais antigos tendem a ter médias um pouco mais altas**, possivelmente por serem clássicos ou já filtrados pelo tempo (só os mais relevantes ainda recebem avaliações).

---

#### **(b) Qual o grupo mais disperso, o de usuários que avaliaram ou o de usuários que rotularam filmes?**  
📊 **Resposta:**
A análise revelou que os usuários que avaliaram os filmes apresentam uma **dispersão maior em comparação aos que rotularam**. Isso foi evidenciado pelo desvio padrão mais elevado no número de avaliações por usuário, indicando uma variação maior na quantidade de interações individuais. Além disso, a distribuição dos dados mostrou que há usuários que avaliaram um número significativamente maior de filmes em relação à média, enquanto no caso das tags, a variação foi menor e mais concentrada em um intervalo reduzido. O histograma e o boxplot reforçaram essa conclusão ao ilustrar uma amplitude maior nas avaliações do que nos rótulos atribuídos.  

---

#### **(c) Qual a categoria rotulada mais frequente?**  
🏷️ **Resposta:**
A análise revelou que a tag mais frequente no dataset é **'IN NETFLIX QUEUE'**, que apareceu 131 vezes. Isso indica que esta é a categoria mais utilizada pelos usuários para rotular filmes no sistema. O gráfico de barras mostra claramente a distribuição das tags mais populares, com 'IN NETFLIX QUEUE' destacando-se significativamente em relação às demais.

---

#### **(d) Como estão distribuídas as avaliações ao longo do tempo?**  
⏳ **Resposta:**
A distribuição das avaliações ao longo do tempo pode mostrar um aumento gradual, um pico em anos específicos ou uma oscilação dependendo de vários fatores, como o número de lançamentos de filmes populares e a participação dos usuários nas avaliações.

---

### 📌 Questão 2 – Perguntas Individuais (40 pontos)

Cada membro do grupo escolheu uma das quatro tabelas do conjunto de dados (`movies.csv`, `ratings.csv`, `tags.csv`, `links.csv`) e elaborou **duas perguntas com suas respectivas respostas** no notebook principal.

---

#### **Quantos gêneros diferentes de filmes existem na base de dados movies.csv ?**
⏳ **Resposta:**
Total de gêneros únicos: 20

---

#### **Qual é o gênero mais frequente entre os filmes cadastrados?**
⏳ **Resposta:**
O gênero mais frequente é 'Drama', com 4361 filmes.

---

#### **Qual é a distribuição temporal da criação de tags?**
⏳ **Resposta:**
A distribuição temporal da criação de tags revela como a interação dos usuários com o sistema evolui ao longo do tempo. A análise de picos ou quedas pode fornecer insights valiosos sobre o comportamento do usuário e ajudar a entender tendências de uso de tags em diferentes períodos.

---

#### **Quais filmes receberam mais tags diferentes?**
⏳ **Resposta:**
Filme com ID 296: Recebeu 173 tags diferentes.
Filme com ID 2959: Recebeu 48 tags diferentes.
Filme com ID 924: Recebeu 40 tags diferentes.
Filme com ID 293: Recebeu 32 tags diferentes.
Filme com ID 1732: Recebeu 31 tags diferentes.

---

#### **Qual a relação entre número de tags e número de usuários por filme?**
⏳ **Resposta:**
Existe uma correlação positiva entre o número de usuários que marcaram um filme e o número total de tags recebidas. Alguns filmes são outliers, recebendo muitas tags de poucos usuários (indicando usuários muito ativos).

---

#### **Qual é a estrutura e as estatísticas básicas do dataset de links de filmes?**
⏳ **Resposta:**
O dataset possui 9742 exemplos/amostras/linhas e 3 atributos/variáveis/colunas.

---

#### **O conjunto de dados contém registros duplicados de movieId?**
⏳ **Resposta:**
Não há registros duplicados na coluna movieId.

---

### 📌 Questão 3 – Compartilhamento no Git (20 pontos)

Este repositório contém toda a atividade resolvida em um único arquivo Jupyter Notebook, conforme solicitado.

📎 Link para este repositório: **[https://github.com/seu-usuario/atividade-n2-movielens](https://github.com/seu-usuario/atividade-n2-movielens)**

---

## 💻 Requisitos

Veja `requirements.txt` para instalar as dependências necessárias:

```bash
pip install -r requirements.txt
