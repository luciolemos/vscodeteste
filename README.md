# vscodeteste
Tutorial de uso do git o vscode.
//retornando à pasta "vscode_projects", dois níveis acima, na árvore de diretórios de C:\
C:\wamp\www\vscode_projects\html>cd ..
C:\wamp\www\vscode_projects>cd ..
//listando as pastas no diretório "www".
C:\wamp\www>dir
 O volume na unidade C não tem nome.
 O Número de Série do Volume é 0E89-71D8

 Pasta de C:\wamp\www

23/06/2020  12:00    <DIR>          .
23/06/2020  12:00    <DIR>          ..
18/10/2019  08:55            23.668 add_vhost.php
21/06/2020  20:07    <DIR>          blog.com
31/12/2010  08:40           202.575 favicon.ico
22/06/2020  01:51    <DIR>          gitvscode
22/06/2020  09:51    <DIR>          html_1
26/11/2019  10:41            20.404 index.php
22/06/2020  10:22    <DIR>          php_composer
22/06/2020  01:22    <DIR>          project1.com
21/06/2020  18:47    <DIR>          site.com
23/06/2020  02:34    <DIR>          teste
29/10/2019  12:57               741 testmysql.php
21/09/2015  17:30               742 test_sockets.php
23/06/2020  19:31    <DIR>          vscode_projects
20/06/2020  12:28    <DIR>          wamplangues
20/06/2020  12:28    <DIR>          wampthemes
               5 arquivo(s)        248.130 bytes
              12 pasta(s)   352.930.525.184 bytes disponíveis

//criando o diretório "vscode_git", dentro do diretório "vscode_projects".
C:\wamp\www>mkdir vscode_git

//navegando para dentro do ditretório "vscode_git"
C:\wamp\www>cd vscode_git

//carregando a pasta "vscode_git" no vscode.
C:\wamp\www\vscode_git>code .

C:\wamp\www\vscode_git>

//clonando para dentro de "vscode_git", o repositório "vscodeteste.git".
C:\wamp\www\vscode_git>git clone https://github.com/luciolemos/vscodeteste.git
Cloning into 'vscodeteste'...
remote: Enumerating objects: 19, done.
remote: Counting objects: 100% (19/19), done.
remote: Compressing objects: 100% (14/14), done.
remote: Total 19 (delta 3), reused 15 (delta 2), pack-reused 0
Unpacking objects: 100% (19/19), 2.44 KiB | 1024 bytes/s, done.

C:\wamp\www\vscode_git>