Esta consulta realiza um JOIN entre as tabelas de alunos e notas, retornando:

ID do aluno
Nome do aluno
Nota obtida
🔗 Executar online

-- Relatório de notas por aluno
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
