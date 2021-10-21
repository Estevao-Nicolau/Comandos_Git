# Comandos para auxiliar no Git.
Configura o Git no terminal:
git config --global user.name “Nome”
git config --global user.email Email
git config --global core.editor nomedoeditor
git config --list

Comandos do Git:

Começa criando uma pasta, use o terminal.

mkdir ‘nome da pasta’

cd ‘nome da pasta’

git init      
“Isso cria um novo subdiretório chamado .git que contem todos os arquivos necessários de seu repositório.”

ls -la 
“ Visualiza os arquivos criado do Git”

git status 
“Verifica quais os estados que os arquivos estão”

git commit -m “ Nome do arquivo” 

“para capturar o estado de um projeto naquele momento”

git log 
“ você pode visualizar o que vem sendo feito em uma determinada branch ou avaliar as alterações de um arquivo em especial”

git log —decorate
“ Mostra mais informações ” 

git log —author=“nome”
“Vai lista todos os commit do author”

git log —graph
“Mostra em forma gráfica o que aconteceu com os bash”

git shortlog 
“Mostra por ordem alfabética os author quantos commit fizeram e quantos foram”

git shortlog -sn
“Mostra a quantidade de commit e o nome”

git diff
" Mostra a modificação do arquivo " - OBS: usar esse comando antes de dar um Commit para conferir.

git diff --name-only
" Mostra o arquivo motivicado 

git commi -am "Colocar o que fez de mudança "
"so server para arquivos existentes "

git checkout nome do arquivo
" comando para apagar e voltar antes da edição que foi feita "

git reset --soft --mixed --hard
" --softA opção moverá tudo (exceto unstagedarquivos) parastaging area
  --mixed opção moverá tudo para unstaged area
  --hard opção moverà tudo "




# Comandos_Git
