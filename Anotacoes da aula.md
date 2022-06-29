##### Comandos do Git

Listar pasta: dir

Navegar entre as pastas: cd  + nome da pasta

Limpar tela: control L

Dois pontos volta

Criar pasta: mkdir nome da pasta

Criar arquivo na pasta: echo hello > hello.txt

Deletar arquivos da pasta criada: del

Deletar a pasta toda: rmdir nome da pasta /S /Q

 Git-init começa o repositório

Git-add mover arquivos e começar o uso

Git-commit criar commit

Trazer repositório da nuvem: git clone + link pasta

Status do git: git status

Adicionar arquivo no git: git add .  o ponto significa adicionar todos os itens novos da pasta no git

Comitar: git commit -m para colocar comentario, abrir aspas

Para mandar as alterações pro repositório da nuvem: git push origin main



##### Objetos do git

Blobs: contem metadados do git. Não guarda dados do arquivo, só o sha1 do arquivo

Trees: armazenam blobs. Monta toda a estrutura de onde estão localizados os arquivos. Podem apontar pra blobs ou outras árvores. Elas tem um sha1 também, se mudar uma virgula dos arquivos, o sha da blob muda e o sha da arvore também

Commits: junta tudo e da sentido a alteração que está sendo feita. Voce pode escrever mensagem aqui, fica o nome do autor e tem um timestamp, a data e hora de quando foi criado. Também tem sha1... se você alterar uma blob, gera um sha1 daquela blob... tem uma arvore apontando pra ela, logo, muda também os metadados daquela arvore, e o commit aponta pra uma arvore que pode apontar pra outras arvores. Alteração sempre reflete aqui. Não tem como uma pessoa alterar o código de um arquivo sem que isso fique muito claro no histórico de commits

 

 