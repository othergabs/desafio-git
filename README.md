# desafio-git

## Crie um novo repositório

Acesse https://github.com/new e crie um repositório para o seu grupo. Lembre-se se deixa-lo público e marcar a opção de criar com o arquivo "README"

## Adicionando colaboradores

Adicione seus colegas como colaboradores do projeto. Clique em "Settings" > "Collaborators", busque os usuários e adicione-os

## Clonando

Agora todos devem ter uma cópia do projeto localmente, para isso copie a url do repositório, abra o terminal e execute o comando `git clone {url-do-repositório}`

![image](https://user-images.githubusercontent.com/36162825/195984347-e09171f9-4490-41c8-83c7-0fc1e86db378.png)


## Criando novas versões

Agora cada uma das pessoas do grupo deve adicionar a seguinte frase no arquivo README 

`{seu-nome-aqui} - Essa é minha nova versão no ramo principal`

### Adicione a mudança do arquivo na nova versão

`git add .`

### Crie uma nova versão 

`git commit -m "{seu-nome-aqui}: nova versão"

### Publique sua nova versão

`git push`

### Obtendo as versões geradas

A cada publicação sua e de seus colegas, o git irá gerar uma nova versão, para ficar sempre atualizado localmente asta sincronizar as mudanças entre o repositório remoto e o repositório local

`git pull`
