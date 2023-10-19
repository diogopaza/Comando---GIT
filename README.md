# Comandos---GIT---MAVEN

<strong>git remote -v </strong> ===  mostra o endereço do repositório remoto para o qual estamos enviando nossos códigos.<br>
<strong>git branch </strong> ===  lista todas as branches presentes no repositório do seu computador.<br>
<strong>git branch -a </strong> ===  lista todas as branches presentes no repositório do seu computador e no repositório remoto.<br>
<strong>git blame nome-do-arquivo </strong> ===  mostra quem alterou cada linha de um arquivo.<br>
<strong>git config --global user.name "novoNome" </strong> === definindo o nome do usuario do GIT.<br>
<strong>git config --global user.name </strong> === verifica o nome do usuario do GIT.<br>
<h3>GIT STASH </h3>
<strong>git stash</strong> === cria uma branch temporaria contendo a versao atual do projeto e após isso vai desfazer as modificações feitas nos arquivos da sua branch atual.<em> Ou seja o git stash remove oque está no git status, as modificações na maquina local, e guarda essa modificações numa branch propria do git stash que pode ser verificada com o comando git stash list.</em><br>
<strong>git stash show</strong> ===  lista todos os arquivos modificados no ultimo stash.<br>
<strong>git stash clear</strong> ===  realiza a remoção de todos os stash’s<br>
<strong>git stash drop stash@{1}</strong> === caso você decida que não precisa mais do stash em particular, você pode fazer a exclusão com o git stash drop.<br>
<strong>git stash pop</strong> === reaplica as alterações no repositorio local.<br>
<strong> git stash list</strong> === listas dos stashs.<br>
<strong>git stash apply</strong> === você pode aplicar mais uma vez as alterações à cópia de trabalho e manter no stash.<br>
<strong>git stash save "mensagem"</strong> === é uma boa prática anotar uma descrição para seus stashes.<br>
<strong>git stash pop stash@{2}</strong> === Você pode escolher qual stash aplicar mais uma vez, passando seu identificador como o último argumento.<br>
<strong>git stash show</strong> === você pode visualizar um resumo do stash u passar a opção -p (ou --patch) para visualizar a comparação completa do stash.<br>
<strong>git stash -p</strong> === também é possível escolher fazer o stashing no único arquivo, uma coleção de arquivos, ou mudanças individuais de dentro de arquivos. Se você passar a opção -p (ou --patch) ao git stash, ele vai percorrer cada "fragmento" alterado na cópia de trabalho e perguntar se você quer fazer o stashing.<br>
<strong>git stash branch</strong> === para criar uma nova ramificação para aplicar alterações com stashing.<br>

<h3>GIT CHERRY PICK </h3>

<p>Exemplo de aplicacao do cherry pick</p>
<strong>git cherry-pick hasCommit </strong> ===  tráz para a branch atual as modificacoes do commit desejado.<br>
<p>Duas branch são usadas neste exemplo a master e a big-feature. Inicialmente a branch master tem apenas um arquivo chamado de index.html. A branch big-feature tem um arquivo index.html e um segundo arquivo chamdo de novo-index.html. Com o uso do comando <strong>git cherry-pick hashCommit</strong> é trazido para a branch atual apenas as modificacoes do commit especificado na flag do comando cherry-pick</p>
<p></p>



