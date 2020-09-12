# Trabalho de Bancos De Dados


Como trabalho da disciplina de bancos de dados, será realizado o desenvolvimento de um software.


## 🛠 Ferramentas
<p align="left"><img src="https://agoncal.files.wordpress.com/2014/05/java_ee_logo_vert_v2.png" width="80"><img src="https://upload.wikimedia.org/wikipedia/commons/2/29/Postgresql_elephant.svg" width="80"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/43/Feed-icon.svg/1200px-Feed-icon.svg.png" width="80"></p>

## 💡 Ideia
A ideia do projeto consiste em um agregador de podcasts, que dará suporte pra cadastro de usuários e de podcasts, através do feed rss, permitindo que os usuários ouçam o podcast, comentar e classificar o podcast. Os usuários também podem pesquisar por podcasts. Há também os gráficos e relatórios com dados do público de cada podcast.

## 🧰 Funcionalidades
 - CRUD do podcast, onde teremos as informações: RSS Feed, nome, site, email de contato.
 - CRUD de usuários, onde teremos as informações: Nome, idade, email, senha, país, sexo.
 - Gerar dados de relatório ou gráfico do podcast, onde irá conter, classificação, quantia de inscritos, região dos ouvintes, sexo, faixa etária.
 - Feed com os podcasts os quais o usuário está inscrito.
 - Busca em podcasts através de palavras-chave ou tags.

## 📃 Descrição
Um usuário acessa o site, e caso não esteja logado aparece as opções de cadastro de novo usuário e de login do usuário. Caso o usuário queira se cadastrar, será redirecionado para uma página onde irá informar seu Nome, idade, email, senha, país e sexo, caso não tenha nenhuma informação inválida, será criada uma conta e o usuário já estará logado. Caso o usuário queira logar em sua conta, será redirecionado para uma página onde irá informar email e senha, caso corretos, irá logar na conta. Após logado, o usuário será redirecionado para a home da aplicação, onde irá aparecer todos os podcasts os quais ele está inscrito, além de um campo para buscas, um menu que contém opções de adicionar novo podcast e deslogar. Caso clique em algum dos podcasts do seu feed, ele irá ser redirecionado para uma página com todos os episódios, quantia de estrelas (classificação) do podcast, descrição, site, e-mail de contato e os comentários, além das opções de gerar gráficos e cancelar inscrição no podcast. Caso ele escolha buscar algo, irá inserir o termo de busca, e o sistema procurará por ester termo entre o nome e as tags de todos os podcasts cadastrados no banco de dados. Assim, retornará todos os correspóndentes para o usuário, permitindo que o mesmo se inscreva no podcast, ou caso esteja inscrito, que se desinscreva do podcast. Toda vez que um usuário se inscreve em um podcast, ele é adicionado à lista de inscrições do usuário, e o usuário adicionado à lista de inscritos do podcast. Também quando inscrito, é possível que o usuário comente e avalie com até 5 estrelas o podcast. Caso o usuário escolha adicionar um novo podcast será redirecionado para o CRUD de podcast, onde irá inserir as informações, caso sejam válidas o podcast será inserido no banco. Quando o usuário clicar em gerar gráficos, o sistema busca as informações de todos os inscritos nos podcasts, de forma que recebe todos os dados importantes para geração de um gráfico preciso sobre o público do podcast.

## 📖 Diagrama E-R
<img src="https://i.imgur.com/aWi46fi.png" width="800">


