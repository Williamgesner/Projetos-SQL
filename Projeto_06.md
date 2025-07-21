# 📊 Projeto 06 – Analisando hábitos de carregamento de veículos elétricos

**🔗 Projeto completo:** [Analisando hábitos de carregamento de veículos elétricos](https://www.datacamp.com/datalab/w/5e6d07a8-2702-4378-9578-fdb243580d9f/edit)  
**👤 LinkedIn:** [William Gesner](https://www.linkedin.com/in/william-gesner/)

---
## 🧠 Descrição do projeto:
Com o crescimento dos veículos elétricos (VEs), aumenta também a demanda por estações de carregamento — especialmente em garagens residenciais. Este projeto visa compreender melhor os hábitos de carregamento dos inquilinos em estações compartilhadas, ajudando os gestores de prédios a otimizarem o uso desses recursos limitados.

---
## 🎯 Objetivo
Analisar o comportamento dos usuários que utilizam estações de carregamento compartilhadas, identificando:
- A quantidade de usuários únicos por garagem.
- Os horários mais populares de uso.
- Usuários com longas sessões médias de carregamento.

---
## 🔎 Análise
O conjunto de dados está armazenado na tabela `charging_sessions`, com colunas que representam:
- Informações sobre a garagem (`garage_id`) e o usuário (`user_id`, `user_type`)
- Dados temporais (`start_plugin`, `end_plugout`, `month_plugin`, `weekdays_plugin`, etc.)
- Duração da sessão e energia consumida.

---
Consultas realizadas:
1. **Usuários únicos por garagem**  
   Identificamos o número de indivíduos únicos que utilizam estações compartilhadas por prédio, classificando do maior para o menor número de usuários.

2. **Horários mais populares de carregamento**  
   Analisamos os horários (por dia da semana e hora) com maior volume de sessões em estações compartilhadas.

3. **Usuários com carregamentos prolongados**  
   Selecionamos os usuários com duração média de carregamento superior a 10 horas, em estações compartilhadas.

---
## ⚙️ Ferramentas Utilizadas
- **SQL** (PostgreSQL)
- **DataCamp Workspace**
- **Comandos principais:** `GROUP BY`, `COUNT(DISTINCT)`, `AVG()`, `ORDER BY`, `WHERE`, `HAVING`
- **Markdown** para documentação e versionamento no GitHub

---
## ✅ Conclusão
A análise revelou padrões importantes no uso das estações compartilhadas: alguns horários são altamente concorridos e há usuários com sessões extremamente longas. Essas informações são cruciais para gerenciar a infraestrutura de carregamento de forma mais eficiente, melhorando a experiência dos residentes e evitando conflitos no uso dos pontos disponíveis.
