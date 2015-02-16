# Instalando o Git no Linux
`$ sudo apt-get install git`

# Configurações básicas.
Digite seu nome e e-mail:

`$ git config --global user.name "Nome`

`$ git config --global user.email email@email.com`

# Criando um repositório.
Crie um diretório e dentro dele digite o seguinte comando:

`$ git init`

# Rastreando o arquivo
Podemos descobrir como está situação dos arquivos no seguinte comando:

`$ git status`

# Adicionando um arquivo ao repositório.
Digitando o `add` é possível adicionar um arquivo.

`$ git add exemplo.txt`

Agora se deseja adicionar todos os arquivos use o `.`

`$ git add .`

# Gravar as alterações no repositório. 
`$ git commit -m "Primeiro exemplo"`

# Verificar alterações realizadas
Para verificar o histórico de alterações feitas no repositório, digitamos o seguinte comando:

`$ git log`

> No terminal do linux pressione `q` para sair.

# Salvando nosso repositório nas nuvens.
Direcionando o projeto no github, aponte para uma repositório já criando.

`$ git remote add origin http://githun.com/exemplo/exemplo.git`

# Enviando as alterações para o GitHub
Já com tudo certo podemos enviar as mudanças:

`$ git push origin master`

> Digite usuário e senha.
 
