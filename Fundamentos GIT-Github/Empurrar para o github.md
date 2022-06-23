# Empurrar o Commit :pushpin:



Quando terminamos de fazer todas as alterações e não vamos mais modificar nada depois disso vamos então "Empurrar" para o git hub após isso o código estara na plataforma.

##### Antes de tudo!!

quando rodarmos o push ele pedirá um login e uma senha, então vamos seta-los

 Rode:

​     `git config --global user.name "nick do GitHub para facilitar sua vida"`

 A senha se torna um problema um pouco mais sério, na polataforma da DIO o video se encontra um pouco desatualizado e pesquisando um pouco vi que o padrão de login e senha foi modificado e no lugar da senha temos que adicionar uma key, gerada no próprio GitHub, por parâmetros de segurança

 Para isso vá no seu perfil do Git hub e adentre nos seguintes locais no Menu **Settings** => **Developer Settings** => **Personal Access Token** => **Generate New Token** (insira a sua senha caso peça)  preencha o formulário e gere a key e salve -- SALVE ISSO!!

 A key gerada sera sua senha nesses casos.

 Por algum motivo ele sempre pede essa key a cada push que eu faço mesmo minha maquina estando adicionada mas ainda vou procurar a solução



##### Feito isso

 Rode:

​    `git push origin main`

escreva seu username e o token como senhae seja feliz, seu código esta no Git Hub 