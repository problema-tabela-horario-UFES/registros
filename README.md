# registros

O repositório conta com os registros de progressão no entendimento e proposta da criação das tabelas horários para os casos de computação na UFES.

Os trabalhos foram feitos pelos alunos Arthur Maciel e Danilo Lima, orientados pela professora Maria Claudia Boeres (Goiabeiras) e o professor Edmar Kampke (Alegre)
## Divisão
A pasta [matrizes-curriculares](matrizes-curriculares) contém os registros dos curriculos, definimos as siglas:
- PPC - Projeto Pedagógico de Curso
- MC - Matriz Curricular

- CC - Ciencia da Computação
- EC - Engenharia da Computação
- SI - Sistema de Informação

- AL - Alegre
- SM - São Mateus
- VIX - Vitória

## Links

* [google drive](https://drive.google.com/drive/folders/12Drq0Jv8mt9e-phKMLmNfnNaRLxRpQOq?usp=drive_link
) 

* [sheets levantamento de restricoes](https://docs.google.com/spreadsheets/d/1TxKvE5Tfy_ddtX-ulsqgl2VmR8h3QQGBAN28thCgRsU/edit?usp=drive_link)

* [sheets levantamento meta-heuristicas](https://docs.google.com/spreadsheets/d/1kmr_gH0fOdM2Z7gFkwq_mB8QJOT6ui_0ewCSHS_zeBE/edit?usp=drive_link)

* [sheets atas de reunião](https://docs.google.com/spreadsheets/d/17JHNarbx6ZqITuA7XzEnVd4771mvH0gyhKeKgEAjl2A/edit?usp=drive_link)
  
* [GRASP - codigo erika](https://bitbucket.org/erikasegatto/timetabling-cb-ctt/src/master/)

* [GRASP - codigo walace](https://github.com/walacesrocha/Timetabling)

* [Toy comparative](https://docs.google.com/document/d/1BVEhoAVFfhL6kZLvTfYOciLUZN-4p5TR-_LpIsmrc1Q/edit?usp=sharing) 

# Atas de Reunião

### 11/09
#### Resumo
Discussão do problema tabela horário e suas diversas modelagens. 
Edmar contou a história dos casos na UFES.
#### To-do
1. Estudar sobre as restrições estabelecidas de outros estudos. 
2. Fazer uma tabela comparativa (com as aparições indicando os artigos). 
3. Olhar sobre a organização no github na próxima reunião

### 18/09
#### Resumo
Apresetamos as tabelas de levantamento das restrições individualmente e as discutimos. 
Criamos uma organização no github.

#### To-do
"1. Unificar as tabelas de levantamento de restricoes e deixar bem explicadas, visualizar nos surveys outras as referencias
2. criar uma proposta de restrições para UFES (explorar as ja usadas e indicar novas)
3. adicionar os trabalhos no mendeley
4. ((EXTRA)) fazer o levantamento com relacao as heuristicas"

### 25/09
#### Resumo
1Apresentamos as tabelas de restrições dos trabalhos analisados que foram preenchidas com mais informações, 
apresentamos também um início de restrições que podem ser usadas para nosso caso da Ufes
#### To-do
1. Fazer o merge das tabelas
2. Fazer um levantamento dos tipos de cada restrição da tabela
3. Pensar a maneira de apresentar as restrições para os coordenadores.
4. Entrar em contanto com a Luciana (Edmar e Cláudia), depois que a 3. estiver pronta
5. Ajustar os artigos no mendeley
6. ((EXTRA)) fazer o levantamento com relacao as heuristicas1
### 02/10
#### Resumo
"Apresentamos o merge das tabelas, mostrando o levamentamento das restrições, adição das notinhas. Apresentamos a criação do formulário para avaliação das restrições. 

*OBS. lembrar de perguntar nas entrevistas como é feito o processo de construção atualmente (se utiliza algum programa auxiliar, quem faz, como faz?)"*

#### To-do
1. Iniciar no github o relatorio passo a passo do desenvolvimento (trazer desde o inicio) 
2. Corrigir o forms (adicionar uma seçao para dados pessoais) e corrigir para de 0-5 e adicionar exemplos e descrição das restrições), adicionar no drive e no github
3. Buscar as matrizes de todos os cursos de computação (alegre, goiabeiras, sao mateus)

### 09/10
#### Resumo
Mostramos o formulário e o github prontos e definimos as próximas etapas. 

#### To-do
1. Elaborar o texto de email para enviar aos professores (incluir o forms)
2. (Edmar e Claudia) Revisar o texto e enviar para os professores: Rosane, Flávio, Zambom (Vix), Luciana (SM), Marcelo, Dayan, Rodrigo e Geraldo (Alegre).
3. Estudar sobre a construção da solução na dissertação da erika (buscar o código)
4. ((EXTRA)) fazer o levantamento com relacao as heuristicas

### 23/10
#### Resumo
Enviamos o formulário sobre as restrições para o e-mail dos professores (Goiabeiras: Rosane, Zambon e Flavio; Sao Mateus: Luciana; Alegre: Dayan. Marcelo, Geraldo, Rodrigo).
Enviamos e-mail individual para a Luciana, perguntando sobre a coordenação atual de São Mateus e pedindo para indicar outros professores para auxiliar

#### To-do
1. Baixar e rodar o código da Erika verificando se a saida está como o esperado
2. Compreender o funcionamento do código (dica: ler capítulo 7 da dissertação da Erika)
3. Demais tarefas Extras definidas anteriormente

### 13/11
#### Resumo
Fizemos uma revisão geral com o retorno da professora Claudia, apontando e discutindo sobre alguns pontos das respostas do formulário. Trouxemos como proposta para criar as instâncias uma formatação que separe por campi (vitoria, alegre, sao mateus) e por periodo impar(materias do 1,3,5,7,9 periodos)/par(materias do 2,4,6,8 periodos) , assim criariamos 7 instancias:

* toy
* ale-impar
* ale-par
* sm-impar
* sm-par
* vix-impar
* vix-par

#### To-do
1. Criar um roteiro para realizar entrevistas (definir os topicos)
2. Tentar marcar e realizar entrevistas com os professores (definir os horarios disponiveis entre os alunos)
3. Fazer um resumo das respostas dos formulários (verificar planilha) e registrar as decisões de alteração
4. Começar a elaborar como serão nossas instancias, criar uma instancia toy base, anotar quais as diferenças faremos com relação ao ITC 
5. 

### 27/11
#### Resumo

#### To-do
1. Realizar as reuniões que conseguir marcar e trazer as observações anotadas
2. Ir adaptando a instancia TOY da ufes
3. Estudar os algoritmos construtivos (Arthur), explicar a construção criada no trabalho do LNS (Danilo)
4. Estudar as grades curriculares (Verificar quais e quantas disciplinas usam os laboratorios)

