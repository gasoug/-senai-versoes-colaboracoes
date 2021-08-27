# Senai versões colaborações
### Principais comandos utilizados para gerenciar o versionamento deste código ###
- ```git init``` para inciar a edição localmente;
- em seguida fazer configurações globais: ```git config --global user.name "usuario" e git config --global user.email "seu email do github"```;
- ```git remote add origin 'link https do repositório'```;
- criar ou alterar um arquivo existente e em seguida dar o comando ```git status``` para listá-los;
- em seguida o comando ```git add .``` para adicionar todos os arquivos localmente;
- ```git status``` novamente para verificar se os arquivos foram adicionados mudando assim seu status de vermelho para verde;
- ```git commit -m "algum comentario"``` para deixar salvo as alterações que foram adicionadas localmente;
- por último enviar para o link do repositório com o comando ```git push -u origin master```;
- para criar uma branch sem fazer alterações na trunk(master) basta digitar o comando ```git checkout -b nome da branch``` (obs: o ```git push -u origin master``` deverá ser substituído por ```git push -u origin "nome da branch"``` sem as aspas);
- para voltar pra master, basta utilizar o comando ```git checkout master```;
- baixar informações de outra branch ```git pull origin "branch que quer baixar o conteúdo"``` sem as aspas;
- para mesclar ambas as branchs, ```git merge "nome da branch"```;

**Faça bom uso!**
