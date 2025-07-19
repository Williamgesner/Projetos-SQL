# 📊 Projeto 09 – Fatores que impulsionam o desempenho do aluno
**🔗 Projeto completo:** [Fatores que impulsionam o desempenho do aluno](https://www.datacamp.com/datalab/w/ae86199f-40de-49df-8da6-bfbb48faee6f/edit)  
**👤 LinkedIn:** [William Gesner](https://www.linkedin.com/in/william-gesner/)

---

## 📌 Descrição
No ambiente educacional competitivo de hoje, entender os fatores que influenciam o sucesso dos alunos é mais importante do que nunca. Assim como os sistemas urbanos precisam se adaptar às necessidades da população, escolas também precisam entender o que impulsiona o desempenho acadêmico. Este projeto analisa um banco de dados rico em detalhes sobre a vida estudantil — como sono, frequência, tutoria e atividades extracurriculares — para entender como esses fatores impactam as notas em exames.

## 🎯 Objetivo
Utilizar SQL para explorar fatores que afetam diretamente o desempenho dos alunos, identificando os principais elementos que contribuem para altas notas em provas.

## 🔎 Análise
O banco de dados `student_performance` contém as seguintes colunas:
- `attendance`
- `extracurricular_activities`
- `sleep_hours`
- `tutoring_sessions`
- `teacher_quality`
- `exam_score`

Consultas realizadas:

1. **Mais estudo e atividades extracurriculares impactam o desempenho?**  
   Verificamos como estudar mais de 10 horas por semana, aliado à participação em atividades extracurriculares, afeta a média das notas.  

2. **Existe um ponto ideal de horas de estudo?**  
   Categorias analisadas: 1-5, 6-10, 11-15 e 16+ horas por semana, com foco na média de desempenho por grupo.  

3. **Classificação dos alunos com base no desempenho (sem exibir notas)**  
   Aplicação de função de janela (`RANK()`) para atribuir posições por desempenho na prova. Empates recebem a mesma classificação.  

## ⚙️ Ferramentas Utilizadas
- SQL
- Funções de agregação (`AVG`, `GROUP BY`)
- Funções de janela (`RANK()`)
- Filtros e ordenações
- Lógica de categorização de faixas (`CASE WHEN`)

## ✅ Conclusão
O projeto demonstrou, com base em dados, como fatores comportamentais como quantidade de estudo, sono e envolvimento extracurricular podem impactar diretamente o desempenho acadêmico. A análise permite tomar decisões informadas para ajudar estudantes a melhorarem suas estratégias de aprendizado.

