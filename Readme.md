Material para lembrar como usar git e github

Veja mais no Curso da Alura ou com o vídeo da Rafaella Balerini

Para subir um novo repositório:

```bash

git init -b main

git add .

git status  #(opicional)

git commit -m “nome da pasta”

git status  #(opicional)

cria um repositório no github e pega o link

git remote add origin  <link>

git push -u origin main

# telinha de login do git com o github 
```

> Windows + v para colar o link entre outros (é o ctrl c)

Para um repositório que você vai mudar rapidinho:

```bash
git status   # pra ver se tá tudo certo, deve mostrar que tem arquivos não salvod

git add . 

git commit -m "Nome da alteração”     

git push

git status  #pra ver se esta tudo certo
```

Pra roubar algo seu mesmo ou do seu amiguinho:
git clone
