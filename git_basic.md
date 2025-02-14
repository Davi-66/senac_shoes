# comandos básicos do git

git config --global user.name "Seu Nome" -> Inclui a credencial do seu nome
git config --global user.email "seu_email@example.com" -> Inclui a credencial do seu email

git init -> Inicializa o repositório local.

git status -> exibe se os arquivos/ pastas estão adicionados ao repositório.
git add nome_do_arquivo -> você adiciona o arquivo ao repositório local.
git add -> você adiciona todos os arquivos modificados/criados no repositório local.

git branch -M main -> altera o nome da branch principal de master para main.
git commit -m "Menssagem de atualização" -> cria um commit para que seja realizado um novo versionamento.

git log -> lista todos os commits que foram realizados.
git log --oneline --graph --decorate -> forma compacta de exibir os commits.
git remote add origin https://exemplo.com/repositório ->realiza a sincronização do repositório local com o remoto.

git push -u origin main -> envia as informações do repositório local para o remoto.