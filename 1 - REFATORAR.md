# Refatorar

A ideia de refatorar o código, tem o objetivo de deixar o código melhor.

Pegamos um código que já existe, reescrevemos ele com as mesmas funções porém de uma outra forma escrita. 

Primeiro passo, rodar o git:

````bash
$ git init
````

Adicionar todos os arquivos:

````bash
$ git add -A
````

````bash
$ git commit -m 'First commit'
````

Segundo, criar um repositório no GitHub. 

No próprio GitHub pegamos o código:

````bash
git remote add origin https://github.com/MatheusSGomes/animais-fantasticos.git
````

Isso serve para adicionar o Git remoto. 

Depois colocar no master:

````bash
git branch -M main
````

````bash
git push -u origin main
````

---

Após colocados todos os arquivos no GitHub, usamos o NPM install para instalar todos os módulos do package.json.

