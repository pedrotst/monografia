# monografia
Projeto de monografia 

1- Instale o git para Windows https://git-for-windows.github.io/

2- faça checkout da monografia:

  ->Abra o git bash (iniciar -> git bash)
  
  ->Navegue até a pasta onde deseja colocar a pasta da monografia. Recomendo o próprio C:/ por uma questão de facilidade (cd C:/)

3- Execute o comando: git clone https://github.com/pedrotst/monografia

4- Instale o miktex http://miktex.org/download

5- Instale o texstudio http://sourceforge.net/projects/texstudio/files/texstudio/TeXstudio%202.10.4/texstudio-2.10.4-win-qt5.5.1.exe/download

Beleza, tá tudo pronto pra rodar, abra a monografia.tex pelo textstudio e mande rodar e compilar.
Se você tiver o mesmo problema que eu no arquivo hypernat.sty  siga os seguintes passos que encontrei para resolver:

You may see an error having to do with 'hypernat.sty.' To resolve this error, you can manually download the hypernat.sty file from here. Unzip the file and save the hypernat.sty file in the 'misc' folder at the end of a filepath that follows this structure: C:\Program Files\MiKTeX 2.9\tex\latex\misc. Then go to the start menu > All Programs > MikTeX 2.9 > Maintenance (Admin) > Settings (Admin). Click the "Update Formats" button. And then click the Refresh FNDB button. Click OK. You should then be able to build your LaTeX document without the 'hypernat.sty' warning.

Pronto, está tudo preparado pra começarmos a trabalhar :D

Agora, sempre que você for escrever algo, antes abra o git bash dentro da pasta da monografia e execute o comando git pull. Isto vai atualizar sua cópia local com minhas alterações, caso eu tenha feito.

E quando você terminar de escrever coisas novas faça

git add . (isso vai adicionar todos novos arquivos criados por você)

git commit -m "Alguma mensagem explicativa da alteração"

git push

E isto irá enviar todas alterações feitas por você.
