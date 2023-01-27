## task02-git-pedrosousa

Inicialmente entendi o motivo da utilização do Git, que é um sistema para controle de versão. Com ele é possível ter o projeto remotamente e um clone local. Com o clone local é permitido trabalhar de modo offline (fazer modificações, adicionar recursos, correções), em uma versão do projeto que parte da remota, sem que altere diretamente no repositório remoto.

Através do clone local (no computador de quemm está colaborando) consegue-se uma comunicação com o repositório remoto para salvar as alterações. Mas essa ligação entre os dois diretórios não são diretamente conectados, o processo funciona da seguinte forma: 

<img src="imagens-README/img01.png">

Primeiramente, após ter iniciado o repositório remoto ou feito o clone dele, trabalhamos no Diretório de Trabalho (ou Working Directory), tendo feito as alterações -> enviamos para a Área de preparação (ou Stanging Area) com o comando ## git add, que é como uma sala de espera antes de efetivamente enviar as alterações no repositório -> Para enviar ao Repositório local (ou Git Directory) utilizamos o comando ## git commit.

