Essa projeto esta sendo usado como exemplo para aprender e explorar as funcionalidades do GIT e GITHUB.
Com o passar do processo de aprendizagem colocarei algums anotaçoes neste arquivo com a finalidade de fixar alguns conceitos e ate  
mesmo alguns comandos que irei utilizar bastante durante o processo.

1.  Para iniciar o versionamente de um projeto o primeiro comando que devemos utilir é o : $ git init   
    Ao utilizarmos esse comando a gente da inicio do controle de versionamento daquele projeto em especifico. Ou seja, nos abrimos um repositorio para registrar todas as alterações daquele projeto. Importante lembrar que devemos utilizar esse comando dentro do terminal do git a partir da pasta do projeto.
2.  Apos realizar as alterações nos arquivos a serem subidos para o repositorio, iremos adicionar esses arquivos a area de Staging, que é a area onde fica todos os documentos a serem subidos no commit. A sua sintaxe é: $ git add (nome do arquivo).  
3.  Somente apos subirmos todos os documentos para area de Staging que iremos usar o comando: $ git commit -m "Legenda do Commit".
Ao realizarmos esse comando subimos o primeiro commit do repositoria para a branch "master" que é seria a linha do tempo principal do versionamento.      
4. Devemos criar um repositorio no GitHub com o mesmo nome que demos para a pasta do nosso projeto. 
5. Apos criar o repositorio, iremos realizar a conexão do nosso repositorio local para o repositorio online(remote), que é o repositorio no GitHub. Fazemos isso com o comando: $ git remote add origin (link do repositorio no GitHub disponiblizado pelo proprio GitHub).
Feito isso o nosso repositorio local ja esta conectado ao repositorio online(remote no GitHub.)
6. Para que entao enviarmos o repositorio local para o online utilizamos o codigo: $ git push -u origin main.

Entao de forma simples e resumida o processo de crir um doc, salvar e enviar ao GitHub é: 
 - $ git add (nome do arquivo) 
 - $ git commit -m "Legenda do Commit"
 - $ git push -u origin main(main é o nome da bracnh principal, portanto pode ser um nome diferente a ser utilizado.)