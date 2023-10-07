
# DIO | Resumos Git e GitHub

Armazenar informações de do curso versiamento de código com git e GitHub [Digital innovation One] (dio.com)


## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub] (https://docs.github.com/)

## 💻 Resumos das Aulas

| Aulas | Resumos |
| Gravando alterações no repositório| 


Git init
git clone
cat config
ls
git status
git remote add origin
git commit 
mkdir (colocar o nome da pasta que deseja criar na frete)
para abrir uma pasta é necessário colocar cd e o nome da pasta
git log

## Criar uma nova pasta
  - mkdir
  - cd + nome da pasta
  - git init
  - cd .git (para entrar na pasta e executar o ls)

## Trabalhando com branches
- De maneira simplista, uma branch é uma ramificação do seu projeto.
  - É um ponteiro móvel para um commit no histórico do repositório;
  - Quando você cria uma nova Branch a partir de outra existente, a nova se inicia apontando para o mesmo commit da branch que estava quando foi criada
  - main
  - commit 0 commit 1 commit 2
  - criar e deletar branches de maneira fácil
  - Pode criar um teste que olhará para a commit 3 que depois pode passar a ser main "principal"
  - git fetch origin main (serve para ver as diferenças da branches e usar depois a git diff main origin/main
  - para trazer as mudanças deve usar a giit merge oring/main serve para baixar as informações
  - caso queira clonar várias branches de uma branch, copia o http e cola no git clone com o link e depois indicar qual a branch que quer --branch --single-branch
  - git statsh arquiva a ação anterior de modificação e pode criar uma nova
  - git checkout -b teste-2 (criar uma nova)
  - git stash list as modificações que já foram realizadas
  - git stash pop para mostear a mais recente
  - git stash apply
