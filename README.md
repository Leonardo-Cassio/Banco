# 🚀 Banco de Dados 
Tarefa do curso DSM da FATEC Dr. Thomaz Novelino de Modelagem de Banco de Dados, na qual foi preciso desenvolver um sistema fictício de uma banco de dados completo.
[Uploading At
Microsoft Visual Studio Solution File, Format Version 12.00
# SQL Server Management Studio Solution File, Format Version 19.00
VisualStudioVersion = 15.0.28307.421
MinimumVisualStudioVersion = 10.0.40219.1
Project("{4F2E2C19-372F-40D8-9FA7-9D2138C6997A}") = "Scripts do SQL Server1", "Scripts do SQL Server1\Scripts do SQL Server1.ssmssqlproj", "{10D45C77-09BF-4EAC-90D3-859F7555D191}"
EndProject
Global
	GlobalSection(SolutionConfigurationPlatforms) = preSolution
		Default|Default = Default|Default
	EndGlobalSection
	GlobalSection(ProjectConfigurationPlatforms) = postSolution
		{10D45C77-09BF-4EAC-90D3-859F7555D191}.Default|Default.ActiveCfg = Default
		{80BC934B-C94D-4442-973A-2FCBE19C6C1C}.Default|Default.ActiveCfg = Default
	EndGlobalSection
	GlobalSection(SolutionProperties) = preSolution
		HideSolutionNode = FALSE
	EndGlobalSection
	GlobalSection(ExtensibilityGlobals) = postSolution
		SolutionGuid = {481B639A-B23B-4CAF-8F93-CA39293B323E}
	EndGlobalSection
EndGlobal
ividade de Banco de Dados.ssmssln…]()


## 🛠️ Construído com:

SQL Server Management Studio Management Studio 19;
Lucidchart;
Draw.io;

### 1 - Cenário: Se passando por uma empresa/usuário crie 01 cenário descrevendo a necessidade de um sistema (exemplos: sistema comercial, biblioteca, bancário e etc). Faça um texto bem detalhado onde seja possível identificar quem são as entidade, atributos e relacionamentos. É obrigatório ter no mínimo 05 entidades e todos os tipos de atributos (simples, compostos, multivalorados, derivados e atributos chave) e relacionamentos (UM PARA UM (1:1), UM PARA MUITOS (1:N) e MUITOS PARA MUITOS (N:N)). 

## ✒️ Cenário: Desenvolvimento de um Sistema para Gerenciamento Escolar:

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

### Tabela - Aluno:
![Captura de tela 2023-11-29 133259](https://github.com/Leonardo-Cassio/Banco/assets/143566209/9dc2754a-126f-4ee4-bd58-47600dec3571)

### Tabela - Professor:
![Captura de tela 2023-11-29 133318](https://github.com/Leonardo-Cassio/Banco/assets/143566209/1dd7401d-01e5-4e1a-ad0f-41750312d169)

### Tabela - Disciplina:
![Captura de tela 2023-11-29 133338](https://github.com/Leonardo-Cassio/Banco/assets/143566209/44f980ea-c28b-4ca9-b2f3-46501a9494e4)

### Tabela - Turma:
![Captura de tela 2023-11-29 133401](https://github.com/Leonardo-Cassio/Banco/assets/143566209/d3182c01-f633-4c8e-a92d-493a394d5b88)

### Tabela - Situação:
![Captura de tela 2023-11-29 133423](https://github.com/Leonardo-Cassio/Banco/assets/143566209/8aaadaec-b549-4473-bad8-3ad20efbae18)

### Tabela - Aluno_Turma: 
![Captura de tela 2023-11-29 133439](https://github.com/Leonardo-Cassio/Banco/assets/143566209/8192184f-3c23-44df-b151-4b6cdcfae44c)

### Tabela - Professor_Turma:
![Captura de tela 2023-11-29 133456](https://github.com/Leonardo-Cassio/Banco/assets/143566209/7bf9e5a6-dbbe-4475-96be-c2a9f4569842)

### Tabela - Disciplina_Professor
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

## ✒️ Autores:

Leonardo Cassio dos Santos.

## 🎁 Expressões de gratidão:

* Conte a outras pessoas sobre este projeto 📢
* Convide alguém da equipe para uma cerveja amanteigada 🍺 
* Obrigado publicamente 🤓.





