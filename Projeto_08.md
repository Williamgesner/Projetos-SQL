# 📊 Projeto 08 – Explorando tendências em nomes de bebês americanos

**🔗 Projeto completo:** [Explorando tendências em nomes de bebês americanos](https://www.datacamp.com/datalab/w/9e752c37-a830-48be-9da6-5cd7b847eb96/edit)  
**👤 LinkedIn:** [William Gesner](https://www.linkedin.com/in/william-gesner/)

---

## 📌 Descrição
Como os gostos americanos por nomes de bebês mudaram desde 1920? Quais nomes resistiram ao tempo e quais refletem tendências mais recentes? Este projeto explora 101 anos de dados da Previdência Social dos EUA para responder a essas perguntas — habilidade essencial para quem analisa tendências, seja em marketing ou em decisões pessoais como nomear um filho.

## 🎯 Objetivo
Aplicar técnicas de categorização, classificação e análise de recorrência para entender padrões e popularidade em nomes de bebês americanos ao longo de um século.

## 🔎 Análise
Os dados foram filtrados para incluir apenas nomes que foram dados a mais de 5.000 bebês em um determinado ano. O dataset contém as seguintes colunas:
- `year`
- `first_name`
- `sex`
- `num`

Consultas realizadas:
1. **Classificação de nomes como “Clássico” ou “Moderno”**  
   Um nome é considerado **"Clássico"** se aparecer em **50 anos ou mais**, e **"Moderno"** caso contrário.  

2. **Top 20 nomes masculinos mais populares**  
   Identificamos os 20 nomes masculinos mais populares considerando a soma total de ocorrências. Também verificamos a posição do nome "Paul".  

3. **Nomes femininos presentes em 1920 e 2020**  
   Descobrimos quais nomes femininos aparecem tanto no início quanto no fim da série histórica.  

## ⚙️ Ferramentas Utilizadas
- SQL (internamente via DataCamp)
- Técnicas de `GROUP BY`, `CASE`, `COUNT`, `SUM`, `RANK`, `FILTER`, `JOIN`, `UNION` e manipulação de DataFrames

## ✅ Conclusão
O projeto revelou como nomes clássicos permanecem relevantes mesmo após um século, enquanto outros surgem conforme tendências culturais. A categorização de dados temporais se mostrou poderosa para identificar nomes perenes versus passageiros.
