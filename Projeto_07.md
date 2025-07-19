# 📊 Projeto 07 – Descobrindo os negócios mais antigos do mundo

**🔗 Projeto completo:** [Descobrindo os negócios mais antigos do mundo](https://www.datacamp.com/datalab/w/5f0a845e-09a1-43f6-95e7-cb14aa7c0368/edit)  
**👤 LinkedIn:** [William Gesner](https://www.linkedin.com/in/william-gesner/)

---
## 🧠 Descrição do projeto:
A vinícola Staffelter Hof, fundada em 862 na Alemanha, é um exemplo de empresa que perdura ao longo dos séculos, resistindo a impérios, guerras e mudanças históricas. O que permite que empresas assim sobrevivam por tanto tempo?  
Este projeto analisa dados de empresas mais antigas do mundo coletados pelo BusinessFinancing.co.uk para descobrir padrões que contribuem para sua longevidade.

---
## 🎯 Objetivo
Usar técnicas de junção e manipulação de dados em Python para analisar empresas históricas e responder a perguntas sobre sua distribuição geográfica, categorias e presença global.

---
## 🔎 Análise
Os dados estão distribuídos em três arquivos principais:
- `businesses` e `new_businesses`: listam empresas com informações de nome, ano de fundação, categoria e país.
- `countries`: mapeia códigos de país com nome e continente.
- `categories`: descreve o significado dos códigos de categoria.

Consultas realizadas:
1. **Empresa mais antiga por continente**  
   Utilizando junções, identificamos qual é a empresa mais antiga presente em cada continente.  

2. **Países sem dados sobre empresas antigas**  
   Contamos quantos países por continente não têm dados registrados sobre empresas antigas, considerando os dois datasets (`businesses` e `new_businesses`).  

3. **Categorias mais resilientes por continente**  
   Analisamos quais categorias de negócios conseguiram permanecer ativas por mais tempo em cada continente.  

---
## ⚙️ Ferramentas Utilizadas
- **SQL** (internamente via DataCamp)
- **Técnicas de** `JOIN`, `GROUP BY`, `MIN`, `COUNT`, `IS NULL`, `CTEs`
- **Markdown** para documentação e versionamento no GitHub

---
## ✅ Conclusão
Empresas antigas estão concentradas em certas regiões e categorias, como hospitalidade e manufatura. O projeto demonstrou como a união de dados dispersos em múltiplas tabelas pode revelar insights sobre resiliência corporativa ao longo dos séculos.
