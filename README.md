# 🚀 Banco de Dados 
Tarefa do curso DSM da FATEC Dr. Thomaz Novelino de Modelagem de Banco de Dados, na qual foi preciso desenvolver um sistema fictício de uma banco de dados completo.

## 🛠️ Construído com:

SQL Server Management Studio Management Studio 19;
Lucidchart;
Draw.io;

## ✒️ 1 - Cenário: Desenvolvimento de um Sistema para Gerenciamento Escolar:

### 1 - Cenário: Se passando por uma empresa/usuário crie 01 cenário descrevendo a necessidade de um sistema (exemplos: sistema comercial, biblioteca, bancário e etc). Faça um texto bem detalhado onde seja possível identificar quem são as entidade, atributos e relacionamentos. É obrigatório ter no mínimo 05 entidades e todos os tipos de atributos (simples, compostos, multivalorados, derivados e atributos chave) e relacionamentos (UM PARA UM (1:1), UM PARA MUITOS (1:N) e MUITOS PARA MUITOS (N:N)). 

Um administrador de uma instituição de ensino com uma base de alunos, professores, disciplinas, turmas e situações em constante crescimento, enfrenta diversos desafios complexos no gerenciamento de informações acadêmicas e administrativas. Para otimizar os processos internos, ele solicitou um Sistema de Gerenciamento de Escola abrangente, capaz de lidar com todos os aspectos da administração escolar.

## ⚙️ Modelagem Conceitual:

### 2 - Modelagem Conceitual: Faça o DER completo do cenários criado. Respeite todas as regras do MER.

https://drive.google.com/file/d/1Llp5YLOZUAhTarLqguZRPn2uBij0Q2FT/view?usp=sharing

![Captura de tela 2023-11-29 131045](https://github.com/Leonardo-Cassio/Banco/assets/143566209/a9acae7a-374d-4431-bad6-e5369ee9f832)

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

## ⚙️ Modelagem Lógica:

### 3 - Modelagem Lógica: Faça o Modelo Lógico do cenário criado, demonstre os tipos de dados esperado em cada atributo (varchar, int e etc), demonstre também de forma clara as chaves primários e estrangeiras e a relação entre as tabelas.

https://lucid.app/lucidchart/f9197f18-6e76-493f-8e97-4a7a53cd98b3/edit?viewport_loc=-414%2C-424%2C2643%2C1228%2C0_0&invitationId=inv_addc2376-79ae-4ac0-8a55-72f930d4f1ff

![Captura de tela 2023-11-29 132504](https://github.com/Leonardo-Cassio/Banco/assets/143566209/613b6712-1fbe-4f71-9ab7-82ce04387d26)

## 📦 Dados:

### 4 - Dados: Faça a inserção de dados em todas as tabelas (ao menos 20 dados em cada tabela).

### 1º Tabela - Aluno:
![Captura de tela 2023-11-29 133259](https://github.com/Leonardo-Cassio/Banco/assets/143566209/9dc2754a-126f-4ee4-bd58-47600dec3571)

### 2º Tabela - Professor:
![Captura de tela 2023-11-29 133318](https://github.com/Leonardo-Cassio/Banco/assets/143566209/1dd7401d-01e5-4e1a-ad0f-41750312d169)

### 3º Tabela - Disciplina:
![Captura de tela 2023-11-29 133338](https://github.com/Leonardo-Cassio/Banco/assets/143566209/44f980ea-c28b-4ca9-b2f3-46501a9494e4)

### 4º Tabela - Turma:
![Captura de tela 2023-11-29 133401](https://github.com/Leonardo-Cassio/Banco/assets/143566209/d3182c01-f633-4c8e-a92d-493a394d5b88)

### 5º Tabela - Situação:
![Captura de tela 2023-11-29 133423](https://github.com/Leonardo-Cassio/Banco/assets/143566209/8aaadaec-b549-4473-bad8-3ad20efbae18)

### 6º Tabela - Aluno_Turma: 
![Captura de tela 2023-11-29 133439](https://github.com/Leonardo-Cassio/Banco/assets/143566209/8192184f-3c23-44df-b151-4b6cdcfae44c)

### 7º Tabela - Professor_Turma:
![Captura de tela 2023-11-29 133456](https://github.com/Leonardo-Cassio/Banco/assets/143566209/7bf9e5a6-dbbe-4475-96be-c2a9f4569842)

### 8º Tabela - Disciplina_Professor
![Captura de tela 2023-11-29 133510](https://github.com/Leonardo-Cassio/Banco/assets/143566209/0efef958-41f1-4a1e-8467-2b09d22d8be4)

## 🛠️ Modelo CRUD (Create; Read; Update; Delete):

### 5 - CRUD: Faça a demonstração por meio de prints do CRUD dentro do SGBD (Inserção de dados, Leitura de Dados, Deleção e Alteração de Dados).

### Inserção de Dados:
![Captura de tela 2023-11-27 205100](https://github.com/Leonardo-Cassio/Banco/assets/143566209/cb7cb460-722f-4ea1-9ced-33f9c4ed9a98)

### Leitura de Dados:
![Captura de tela 2023-11-27 205121](https://github.com/Leonardo-Cassio/Banco/assets/143566209/722872ac-fa6c-4995-9f59-22d427160d7b)

### Atualização de Dados:
![Captura de tela 2023-11-27 205223](https://github.com/Leonardo-Cassio/Banco/assets/143566209/1ebbb527-4d78-4a9e-9878-63b9570e2eab)

### Exclusão de Dados:
![Captura de tela 2023-11-27 205307](https://github.com/Leonardo-Cassio/Banco/assets/143566209/0df6abe9-3ae2-4777-967a-0921b24de15c)

## ✒️ Relatórios:

### 6 - Relatórios: Utilizando a Seleção, Filtro e Ordenação crie 10 consultas para exibir os dados do seu Banco de Dados demonstrando principalmente a relação entre as tabelas.

### 1º consulta: Selecionar todos os alunos:
![Captura de tela 2023-11-29 141326](https://github.com/Leonardo-Cassio/Banco/assets/143566209/bc873503-b4f2-436e-84e8-10bb4bc7c073)

### 2º consulta: Selecionar todos os professores ordenados em ordem alfabética pelo nome:
![Captura de tela 2023-11-29 141416](https://github.com/Leonardo-Cassio/Banco/assets/143566209/b9b19328-5cdc-48f8-a70b-c860d6273b77)

### 3º consulta: Selecionar todas as disciplinas com carga horária superior a 60 horas:
![Captura de tela 2023-11-29 141452](https://github.com/Leonardo-Cassio/Banco/assets/143566209/5bb5520c-1b11-45ec-90ac-026de602befb)

### 4º consulta: Selecionar todas as turmas do ano letivo de 2023:
![Captura de tela 2023-11-29 141532](https://github.com/Leonardo-Cassio/Banco/assets/143566209/884d5f25-8994-4bbc-9842-d3c76ba9f29a)

### 5º consulta: Selecione todos os professores cujo nome contenha a letra 'E':
![Captura de tela 2023-11-29 141645](https://github.com/Leonardo-Cassio/Banco/assets/143566209/9e2c07c7-0a2f-4430-ad0d-f085e364ab63)

### 6º consulta: Selecionar o nome e a data de nascimento de todos os alunos ordenados dos mais velhos aos mais jovens:
![Captura de tela 2023-11-29 141934](https://github.com/Leonardo-Cassio/Banco/assets/143566209/d85cdba2-4b25-40b1-9e6d-c25ff74e40de)

### 7º consulta: Selecionar todas as situações dos alunos de uma determinada turma:
![Captura de tela 2023-11-29 142048](https://github.com/Leonardo-Cassio/Banco/assets/143566209/0e02f0e4-f4bb-472f-8b41-6495fe099b78)

### 8º consulta: Selecionar o nome dos alunos e suas respectivas turmas:
![Captura de tela 2023-11-29 142130](https://github.com/Leonardo-Cassio/Banco/assets/143566209/82dc60a1-7a00-4152-904a-96f53af28ae3)

### 9º consulta: Selecionar o nome e a especialização dos professores:
![Captura de tela 2023-11-29 142203](https://github.com/Leonardo-Cassio/Banco/assets/143566209/badc54e4-7f75-441b-87e7-2c81a70368b2)

### 10º consulta: Selecionar os professores e as turmas que eles lecionam:
![Captura de tela 2023-11-29 142235](https://github.com/Leonardo-Cassio/Banco/assets/143566209/fc6c4596-5178-4b52-90fd-5c428f125536)


## ✒️ Autores:

Leonardo Cassio dos Santos.

## 🎁 Expressões de gratidão:

* Conte a outras pessoas sobre este projeto 📢
* Convide alguém da equipe para uma cerveja amanteigada 🍺 
* Obrigado publicamente 🤓.





