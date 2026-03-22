🎓 SQL Escola Analytics

Projeto de análise de dados de uma escola utilizando SQL.

📌 Objetivo

Simular um banco de dados educacional e extrair insights sobre desempenho de alunos, disciplinas e professores.

🧱 Estrutura do Banco
Alunos
Professores
Disciplinas
Turmas
Notas
🔍 Principais Análises
📊 Média de notas por aluno

Permite identificar desempenho geral.

🏆 Ranking de alunos

Identifica os melhores alunos com base na média.

⚠️ Alunos com baixo desempenho

Detecta alunos com média abaixo de 5.

📚 Média por disciplina

Avalia dificuldade das matérias.


CREATE TABLE RelatorioNotas AS
SELECT 
    a.id_aluno,
    a.nome_do_aluno,
    n.valor_da_nota
FROM TabelaAlunos a
JOIN TabelaNotas n 
ON a.id_aluno = n.id_do_aluno;


[(https://github.com/Brtfreitas/sql-escola-analytics/new/main?filename=README.md)]

🧠 Conceitos aplicados
JOIN (INNER JOIN)
Relacionamento entre tabelas
Criação de tabela a partir de SELECT

<img width="1447" height="978" alt="image" src="https://github.com/user-attachments/assets/ab0e28a3-696a-4fde-8c68-7cc7fece08af" />
