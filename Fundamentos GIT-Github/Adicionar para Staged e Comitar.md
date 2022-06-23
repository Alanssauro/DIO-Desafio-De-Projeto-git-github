# Mover para staged e "commitar"



 ### Sempre 

 Um arquivo quando é modificado ele sai de Staged e vai para Unmodified e rodando o código:



 `alan@alan-pc :  git status`

recebemos a resposta:

  `On branch main`
  `Your branch is up to date with 'origin/main'.`

  `Untracked files:`
    `(use "git add <file>..." to include in what will be committed)`
          `./`

Dizendo que existe um arquivo que fora modificado e precisa serem movidos para staged e posteriormente "comitados"

Para realizar essa função podemos rodar o seguinte código:

  `git add *`

Ao usar o "*" após o "add" ele lança todos os arquivos modificados para staged, para serem commitados

Usamos então o código:

  `git commit -m "menssagem que deseja deixa nesse commit para fins de organização do código( muito importante)"`

assim seu arquivo é commitado e esta pronto para ser puxado para o git hub
