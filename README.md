# Banco de Dados 
Tarefa do curso DSM da FATEC Dr. Thomaz Novelino de Modelagem de Banco de Dados, na qual foi preciso desenvolver um sistema fictício de uma banco de dados completo.

## 🛠️ Construído com:

SQL Server Management Studio Management Studio 19
Lucidchart
Draw.io

## Cenário: Desenvolvimento de um Sistema para Gerenciamento Escolar

Um administrador de uma instituição de ensino com uma base de alunos em constante crescimento, enfrentamos desafios complexos no gerenciamento de informações acadêmicas e administrativas. Para otimizar nossos processos internos, precisamos de um Sistema de Gerenciamento de Escola abrangente, capaz de lidar com todos os aspectos da administração escolar.

### Entidades:

1. Aluno:
   - Atributos: Nome, Data de Nascimento, Endereço, Número de Identificação do Aluno (chave), Número de Telefone, E-mail.
2. Professor:
   - Atributos: Nome, Especialização, Data de Contratação, Salário, Número de Identificação do Professor (chave), Número de Telefone, E-mail.
3. Disciplina:
   - Atributos: Nome da Disciplina, Carga Horária, Número de Identificação da Disciplina (chave), Descrição.
4. Turma:
   - Atributos: Número da Turma (chave), Ano Letivo, Horário, Sala de Aula, Número de Alunos.
5. Situação:
   - Atributos: Número da Situação (chave), Data de Divulgação, Resultado, número de Identificação do Aluno (chave).

### Relacionamentos:

1. Aluno - Turma (Um para Muitos): Um aluno pode estar matriculado somente em uma turma e uma turma pode ter vários alunos matriculados.
2. Professor - Turma (Muitos para Muitos): Um professor pode ser designado para várias turmas e uma turma pode ter vários professores.
3. Aluno - Situação (Um para Um): Um aluno pode ter somente um resultado.
4. Professor - Disciplina (Um para Muitos): Um professor pode lecionar várias disciplinas, mas uma disciplina só pode ter um professor responsável.

## Modelagem Conceitual
https://drive.google.com/file/d/1Llp5YLOZUAhTarLqguZRPn2uBij0Q2FT/view?usp=sharing









