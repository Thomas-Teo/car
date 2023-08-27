# Pagina de Automoveis
### Glossário
[Clonar repositório](#Clonar-repositório)
[Config global](#Config-global)
[Fazer commit](#Fazer-commit)
[Visualizando o Histórico de Commits](#visualizando-o-histórico-de-commits)
## Clonar repositório

1. Abrir o terminal no vs code
2. usar **"cd 'diretorio desejado' "**
3. copiar o link do diretorio do progeto no git em https
4. usar **"git clone https://github.com/nome-usuario/repositorio.git"**

## Config global

1. usar **"git init"** para criar uma pasta que guarda as config
2. usar **"git config --global user.email "seuemail@gmail.com" "** assim configura o email
3. usar **"git config --global user.name "nome do usuario do git" "** assim configura o usuario
4. usar **"git checkout develop"** assim troca para a branch develop
5. usar a branch _develop_ para não subir o codigo direto para main e não dar erro 
## Fazer commit

1. usar **"git status"** para ver os arquivos alterados ou criados
2. usar **"git add ."** para adicionar todos ou **"git add 'nome do arquivo desejado' "**
3. usar **"git status"** para conferir se todos foram adicionados
4. usar **"git commit -m "mensagem descrevendo o commit"** assim você cria o commit com uma breve descição
5. usar **"git push origin develop"** para mandar o codigo para o github

## Visualizando o Histórico de Commits

1. usar **"git log"**