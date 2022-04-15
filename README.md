![Imagem Compass](https://webjump.com.br/wp-content/uploads/2021/08/compassuol-logo-min.png)

<div align="center">
<h1>Desafio da Sprint 1</h1>
</div>

* ***1 - Para que serve o método Scrum?***


_R)_  O método scrum é uma metodologia ágil que serve para organizar grandes projetos, consistindo de alta produtividade, revisões periódicas e aproveitamento estrátegico da realização de tarefas pre-selecionadas para a conclusão de um objetivo final.



* ***2 - Como funciona o método Scrum?*** 


_R)_ O método scrum é dividido  em 4 grupos de pessoas, Desenvolvedores[Dev Team], P.O[Product Owner], Scrum Master e Cliente/Usuário. Resumidamente cada grupo tem o seu papel específico no scrum, sendo os desenvolvedores responsáveis pela produção diária do projeto, o P.O responsável pela organização hierarquica das tarefas e contato direto ao cliente, o Scrum Master responsável pela instrução dos desenvolvedores com suporte e feedback, e por fim o Cliente que promove o projeto juntamente com o Usuário que consome. 
A partir do momento em que o cliente determina e planeja o projeto, o P.O fica encarregado de criar o *Product Backlog* (lista de funcionalidades divididas hirarquicamente) logo após ser definido a lista, o projeto é divido em *sprints* (períodos de tempo definidos de até 1 mês) cada sprint é dividida ordenadamente começando por *Sprint Planning* ou *Planning Meeting* que é o momento pelo qual toda a equipe define oque será feito durante a sprint partindo para o *Sprint Backlog* que é o período em que as funcionalidades irão ser feitas pelo dev team, podendo ser alteradas pelo P.O. Porém todos os dias durante a sprint é feito uma *Daily Scrum* de 15 minutos para a revisão diária do desenvolvimento das funcionalidades. No final da sprint é realizado uma *Review Meeting* para revisar o andamento do produto e por fim uma *Retrospective* momento pelo qual é avaliado o processo do desenvolvimento do produto. Repetindo esse ciclo até a *entrega* do produto.  

Resumo: Project -> Planning =>  Product Backlog -> Sprints(Planning Meeting -> Sprint Backlog -> Daily Scrum -> Review Meeting => Retrospective) -> Entrega


* ***3 - O que é Git?*** 


_R)_ Git é um controlador de versões com código aberto que serve para criar repositórios locais e junta-los à um servidor em nuvem facilitando a entrega conjunta de um programa ou projeto. 



* ***4 - O que é um scrum Product Owner?***


_R)_ O Product Owner é encarregado de criar o Product Backlog definindo suas prioridades e recursos que serão desenvolvidos pela equipe. Além de ser encarregado de ter contato direto com o cliente.



* ***5 - Qual o comando para criação de um novo repositório no Git?*** 


_R)_ $git Init


* ***6 - O que é o HTTP?***


_R)_ É um protocolo de transferência de textos(dados) entre uma máquina local, navegador e um servidor web



* ***7 - Como funciona o HTTP?***


_R)_ Ocorre a troca de dados atráves de solicitações entre usuário e servidor. Geralmente os sites atuam em formato txt, img(jpeg, jpg, png...), entre outros. 



* ***8 - Com o Git Você pode propor mudanças (adicioná-las ao Index) usando um comando. Qual é esse comando?***   


_R)_ $git stash



* ***9 - O que é a Branch master e para que serve?*** 

_R)_ É o "Branch" padrão ou seja a ramificação padrão/inicial do git e serve para armazenar os dados em uma "trilha" ou "ramo" especifíca. Isso é melhor compreendido quando nos referimos a "galhos de árvore" cada um com suas folhas e seu conteúdo delas. E o branch master é o primeiro galho.



* ***10 - Quais são os comandos usados para atualizar um repositório local e fazer merge de um outro branch ao seu branch ativo?*** 

_R)_ Atualizar Repositório: 1°) $git status,  2) $git add . , 3) $git commit -m "",  4) $git pull; 

Fazer Merge de outro Branch: 1°) $git checkout master, 2°) $git merge "outro branch", 3°) $git add . , 4°) $git commit -m ""; 



* ***11 - Pensando em Bases de dados, sendo elas, Relacionais (SQL) e Não Relacionais (NoSQL). Quais alternativas abaixo estão corretas?*** 

Opções | Alternativas 
---------| --------------------------------------
    a    | MySQL = MongoDB 
    b    | PostgreSQL = Redis 
    c    | Oracle = CouchDB 
    d    | Todas as alternativas estão corretas.

_R)_ Letra (d)



* ***12 - O que é MongoDB?*** 

_R)_ É um banco de dados tradicional(Não relacional) 




* ***13 - O que é o MySQL?*** 

_R)_ É um banco de dados relacional




* ***14 - Qual a diferença entre git e github?***

_R)_ Git atua em repositórios locais e com código aberto. Já o github atua em repositórios em nuvem e é um servidor dedicado. 




* ***15 - Quais os dois verbos http que podemos utiizar para realizar um update? Explique a diferença entre eles.*** 

_R)_  1°) PUT (Atualização de um Recurso Inteiro); 2°) PATCH(Atualização de um recurso específico/único)




* ***16 - Qual o status code que pode ser usado na criação de um novo usuário?*** 

_R)_  Se for usado o método GET e POST, poderá ser retornado o status code de 200 [ Operação Bem Sucedida ]  e o de 300 [ Redirecionamento ] para um novo local após o cadastro.




* ***17 - Quais são os três status code que podem ser utilizados para realizar o delete?***

_R)_ 1°) 200 (Operação Bem Sucedida); 2°) 202 (Operação Aceita) e 3°) 404 (Erro)



* ***18 - Qual a extensão ".xxx" contêm as definições da tabela?*** 

Opções | Alternativas 
---------| --------------------------------------
    a       | Commands.myi  
    b    | Commands.frm
    c    | Commands.myd  
    d    | {mysqlDirectory}/data

_R)_ letra (b) 

Explicação:  Extensões .myi(indíces); .myd(dados da tabela) e (d) é um diretório não uma extensão.  



* ***19 - A pasta "C:\ProgramData" é uma pasta oculta, portanto, você deve digitá-la no endereço do Windows Explorer para chegar lá. Nessa pasta de dados, quais opções apresentam o caminho correto para acessar os bancos de dados que foram denominados?***

Opções | Alternativas 
---------| --------------------------------------
    a    |  /{database_name_folder}/{database_tables_and_files}.  
    b    | C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.frm 
    c    | C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.ibd  
    d    | C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\data-recovery 

_R)_ Letra (c) 

Explicação: Assim que haja uma criação de uma nova database, é criado uma pasta especifíca para ela, dentro da pasta principal do MySQL com o formato tradicional .ibd

OBS: A versão que consta na questão é do MySQL server 5.6, então a aplicação do caminho é sempre atualizada a versão instalada no computador. 



* ***20 - Qual a extensão ".xxx" que contêm os dados da tabela?*** 

_R)_ Extensão .myd(Dados de Tabela)



* ***21 - Qual comando usa-se para extração de arquivos em MongoDB durante a instalação?***

_R)_ --dbpath "\Pasta Desitino\db"



* ***22 - Para que usamos o MongoDB?*** 

_R)_ É uma base de dados não relacional de código aberto, sendo bastante utilizada pela sua praticidade e agilidade em relação a armazenamento de grandes quantidades dados, por consequência um melhor aproveitamento e rapidez em consultas.  



* ***23 - Exemplifique para que serve os metódos http 1xx, 2xx, 3xx, 4xx e 5xx. De uma forma macro (geral)!***

_R)_ 1xx = Informacional  ; 2xx = Conexão Sucedida ; 3xx = Redirecionamento; 4xx = Erro Client; 5xx = Erro Servidor;  



* ***24 - Conta pra gente como foi sua experiência na Sprint#01 do programa de bolsa @node.js_mar22 e quais suas expectativas a partir de agora:*** 

_R)_ Um dos melhores momentos de aprendizado de toda minha vida, pois estou me forçando todos os dias a aprender coisas novas, sair da minha zona de conforto na qual eu me interessava apenas pelos mesmos assuntos, me desafiar constantemente a ver um conteúdo que eu amo que é programar e o funcionamento por trás das tecnologias que eu uso todos os dias. Além disso a equipe toda do programa é simplesmente incrível tanto na paciência quanto no respeito e profissionalidade criando um ambiente muito motivacional, que por consequência cria um ar de trabalho bem feito quando eu termino algum curso ou reviso um material, proporcionando um esforço bem aproveitado. E por fim toda a equipe de alunos que fazem parte do processo faz eu me sentir que pertenço a um grupo de pessoas dedicadas e com um objetivo em comum. 

Minhas expectativas é que as próximas sprints sejam tão boas e desafiadoras quanto a passada, porém agora com muito mais controle do processo pois me familiarizei e adptei à metodologia da empresa. E por fim poder usufruir mais dessa oportunidade, para me desenvolver cada vez mais como profissional e estudante. 

