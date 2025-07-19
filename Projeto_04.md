# 📊 Projeto 04 – Analisando as Emissões de Carbono da Indústria com SQL

**🔗 Projeto completo:** [Analisando as Emissões de Carbono da Indústria](https://www.datacamp.com/datalab/w/d75d33c6-b838-4b79-b6b3-a01ebeb3a27e/edit)  
**👤 LinkedIn:** [William Gesner](https://www.linkedin.com/in/william-gesner/)

---

## 🧠 Descrição

Mais de **75% das emissões globais de gases de efeito estufa** estão associadas a produtos – desde alimentos até calçados e eletrodomésticos. Essas emissões incluem desde a geração de calor para fabricação até o transporte, sendo atribuídas a **etapas específicas do ciclo de vida dos produtos**.

Com base em dados públicos da [Nature](https://www.nature.com/articles/s41597-022-01178-9), este projeto explora a emissão de carbono medida em **PCF (Product Carbon Footprint)** — representando as emissões de CO₂ equivalente atribuídas a cada produto.  

Os dados estão armazenados em um banco de dados PostgreSQL e a análise será realizada com SQL.

---

## 🎯 Objetivo

Explorar um conjunto de dados sobre emissões de carbono e responder:

- Quais setores industriais possuem a **maior pegada de carbono**?
- Quantas **empresas únicas** estão listadas por setor?
- Qual é o **total de emissões** por grupo industrial no **ano mais recente disponível**?

---

## 📊 Análise

A tabela analisada é `product_emissions`, contendo colunas como:

- `product_name`, `company`, `industry_group`, `carbon_footprint_pcf`
- Percentuais de emissão por etapa: upstream, operations e downstream.

---

## 🛠️ Ferramentas Utilizadas

- **SQL** com banco de dados **PostgreSQL**
- **DataCamp Workspace** para execução das queries
- **Markdown** para documentação e versionamento no GitHub

---

## 🧩 Tarefas realizadas

- Filtrar o ano mais recente disponível no dataset.
- Calcular o **número de empresas únicas** por grupo industrial.
- Somar e **arredondar a pegada total de carbono** por grupo.
- Classificar os setores com maiores emissões.

---

## 📌 Conclusão

Este projeto fornece insights sobre quais setores industriais são mais responsáveis pelas emissões de carbono relacionadas aos produtos que fabricam. Os dados ajudam a entender **padrões de impacto ambiental** e a direcionar esforços para **redução de emissões** nas áreas mais críticas da indústria global.
