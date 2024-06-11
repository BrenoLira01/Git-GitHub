
# Git e Github

Respositório pra estudos de Git e Github.

## Como pegar, enviar e clonar:

pegar: ```git pull```

enviar: ```git push```

clonar: ```git clone URL do repositório```

## Configurações globais: 

```
git config --global user.name "seu nome no github"

git config --global user.email "seu email"

git config --global init.defaultBranch main
``` 

Ver configurações: ```git config --global --list```

## criando repositórios:

Transformar uma pasta em repositório: ```git init```

adicionar a um repositório remoto:

```
git init

echo "# leiame" > README.md

git add .

git commit -m "primeiro commit"

git remote add origin URL
git branch -M main
git push -u origin main
```

## Branch


 clonar uma branch: ```git clone URL --branch feature-l --single-branch```

 Criar uma nova branch: ```Switched to a new branch 'novaBranch'```

 Mudar de branch: ```git checkout nome da branch``` 

 Saber quantas branch tem: ```git branch``` 

 Excluir uma branch: ```git branch -d nome da branch```

 Mesclar brachs: ```git merge teste```