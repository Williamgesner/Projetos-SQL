# 📊 Projeto 05 – Quando foi a era de ouro dos videogames

**🔗 Projeto completo:** [Quando foi a era de ouro dos videogames](https://www.datacamp.com/datalab/w/d2188f42-7407-4956-a729-ba56872a6d03/edit)  
**👤 LinkedIn:** [William Gesner](https://www.linkedin.com/in/william-gesner/)

## 📌 Descrição
Este projeto analisa críticas, notas de usuários e dados de vendas dos 400 jogos mais populares lançados desde 1977. O objetivo é investigar se houve uma “era de ouro” dos videogames — anos em que os jogos foram mais bem avaliados — e entender o lado comercial por trás da indústria.

## 🎯 Objetivo
Descobrir quais anos tiveram os jogos com melhor recepção de crítica e público, além de analisar os jogos mais vendidos. Para isso, aplicamos junções, filtros, agrupamentos, ordenações e lógica de conjuntos com SQL.

## 🔎 Análise
Os dados são distribuídos em quatro tabelas:

- **`game_sales`**: informações de vendas por jogo (nome, plataforma, editora, desenvolvedor, unidades vendidas e ano de lançamento).
- **`reviews`**: nome, notas de críticos e usuários segundo o Metacritic.
- **`users_avg_year_rating`**: média de notas dos usuários por ano.
- **`critics_avg_year_rating`**: média de notas dos críticos por ano.

Com esses dados, foi possível:
- Identificar os anos com maiores médias de avaliação.
- Avaliar a convergência/divergência entre críticas e notas de usuários.
- Relacionar os jogos mais vendidos com suas avaliações.
- Unir tabelas para extrair insights mais completos sobre performance e recepção.

## ⚙️ Ferramentas Utilizadas
- **SQL** (com foco em **JOINs**, **GROUP BY**, **ORDER BY**)
- **Ambiente de prática:** [DataCamp Workspace](https://www.datacamp.com/datalab)
- **Markdown** para documentação e versionamento no GitHub

## ✅ Conclusão
Analisando os dados de vendas e avaliações ao longo das décadas, conseguimos identificar os períodos com melhor recepção crítica e popular. Este projeto mostra como SQL pode ser uma ferramenta poderosa na análise cruzada de diferentes perspectivas (negócio e opinião pública), com aplicações reais no setor de entretenimento digital.
