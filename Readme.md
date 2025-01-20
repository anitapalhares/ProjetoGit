Material voltado a aprender como usar git e github
algumas dicas: 

Para subir um novo repositório:

```bash
git init
git init -b main

git add .

git status  #(opicional obrigatório)

git commit -m “nome da pasta”

git status  #(opicional obrigatório)

git branch -M “main”

cria um repositório no github e pega o link

git remote add origin  <link>

git push -u origin main

# telinha de login
```

> Windows + v para colar o link entre outros
> 

Para um repositório que você vai mudar rapidinho:

```bash
git status   # pra ver se tá tudo certo, deve mostrar que tem arquivos não salvod

git add . 

git commit -m "Nome da alteração”     

git push

git status  #pra ver se deu tudo certo
```

Pra roubar algo seu ou do seu amiguinho:
