
## passo - criar repo
Criar repositorio no git hub.
    Copiar a URL do repositorio.

## segundo passo - configurar projeto dentro do repo
Dentro da raiz da pasta do projeto EXECUTAR
    - git init
    - git branch -M main 
    - git remote add origin $_URL_DO_GITHUB

Para validar executar:
    git remote
        devera aparecer ˜origin˜


## terceiro passo - verificando e comitando alteraçoes

Dentro do diretorio do projeto eu dou um git status, isso vai mostrar em vermelho o que nao foi comitado.
    git status
    # ADICIONAR TODOS ARQUIVOS ou ARQUIVO ESPECIFICO na fila pra comitar
    - git add .

    - git commit -m "aqui coloca mensagem que foi comitada no git da minha maquina."
    # Coloca aqui onde vai subir o codigo.

    - git push origin main

## Para clonar um repositorio
    - git clone https://github........

## para puxar um recurso do repositorio
    - git pull origin main

## trabalhando com branch
    - git checkout -b $_NOME_DA_BRANCH
    eu troco para outra brench

    - git branch
    mostra as branches abertas

    - git merge $_NOME_DA_BRANCH QUE ESTOU PUXANDO

    Depois preciso subir as alteracoes para a main dnovo.



