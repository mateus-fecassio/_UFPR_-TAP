Trabalho apresentado como requisito parcial à conclusão da disciplina CI062 - Técnicas Alternativas de Programação, pelos alunos:
		Anna Caroline Bozzi					GRR20173532
		Mateus Felide de Cassio Ferreira	GRR20176123


Para compilar diretamente pelo terminal sem IDE deve-se criar um direótio 'NOME' contendo todos os arquivos do trabalho, em seguida, em um diretório anterior deve-se executar os seguintes comandos no terminal: javac NOME/Trabalho.java para compilar, e para executar java Trab.Trabalho.
Já no eclipse, para importar o projeto, deve-se ir em File, Import..., General, Existing Projects into Workspace, Next, selecionar a pasta do trabalho e clicar em finish.

O trabalho consiste em um sistema de agendamento de 'sala', nele é possível você iniciar com os dados de uma antiga execução, dados um arquilo FILE, ou iniciar diretamente em um MENU:


	==========================INÍCIO DA APLICAÇÃO==========================
	O que você deseja fazer?
	Abrir dados do arquivo [OPÇÃO 1]
	Começar uma nova aplicação [OPÇÃO 2]
	=======================================================================


	========================== MENU ==========================
	1)PARA CADASTRAR USUÁRIO DIGITE 1
	2)PARA CADASTRAR RECURSO DIGITE 2
	3)PARA AGENDAMENTO DE RECURSO DIGITE 3
	4)PARA LISTAR OS USUÁRIOS DIGITE 4
	5)PARA LISTAR OS RECURSO DIGITE 5
	6)PARA LISTAR OS AGENDAMENTOS DIGITE 6
	7)PARA REMOVER UM USUÁRIO DIGITE 7
	8)PARA REMOVER UM RECURSO DIGITE 8
	9)PARA REMOVER AGENDAMENTO DIGITE 9
	10)PARA ENCERRAR DIGITE 10
	============================================================

Toda a implementação do trabalho usa o recurso de implementação em listas na linguagem Java.
O Cadastro de  usuário (1) consiste em nome, e-mail e telefone.
O Cadastro de recurso (2) consiste em informar a sala no formato, por exemplo, PA07 seguido dos recursos que podem ser: a sala ter ou não projetor e computador, etc.
O agendamento (3) consiste em verificar previamente se a sala e o usuário estão cadastrados para poder fazer o agendamento, se sim seguimos para as informações do agendamento, data, hora.
Há as opções de listagem (4/5/6) e remoção (7/8/9) de usuários, salas (e recursos) e agendamentos, respectivamente.
O enceramento (10) do programa consiste em percorrer as listas (usuários / recursos / agendamentos) individualmente e salvar em um arquivo de mesmo nome. Esse arquivo, posteriormente, será lido (caso essa seja a intenção do usuário) e o conteúdo será incluído nas listas usadas pelo programa.
