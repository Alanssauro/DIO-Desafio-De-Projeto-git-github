# Chave SSH paara o git ( ou para outras funcionalidades) :secret:



 Abra o terminal e ja com o git devidamente instalado.

#### Rode o seguinte comando:

  `ssh-keygen -t ed25519 -C "email"`



- `ssh-keygen` é o gerador de código
- `ed25519` é o parâmetro da criptografia
- `-C` atenção para o C maiúsculo pois se n dara erro e voce pode ficar perdido por alguns instantes (experiencia própria)
- `"email"` usar o mesmo email que ultiliza no git hub para poder ter um melhor fonte de comparação

 Após isso ele ira gera um par de chaves, uma privada e uma pública, adicione a publica no Github e volte no terminal para adicionar a sua entidade 

#### Rode o código

  `eval $(ssh-agent -s)`



#####              IMPORTANTE!!! 

​             Rodar o código do agente dentro da pasta criada com os ed25519

  `ssh-add ed25519`



