&bull;&nbsp;Para levar da sua máquina caso não exista o repositorio no github:

```git init```

&bull;&nbsp; Caso instale o hub https://github.com/github/hub utilize o comando abaixo:

```hub create```

Este comando vai criar a pasta em que estiver (Ex: teste) no github e **não** vai precisar mais criar repositório no github

&bull;&nbsp;criar repositório no github (**Opcional** caso tenha instalado o hub)

&bull;&nbsp;criar/modificar arquivos locais

```git add .```

ou

```ga .```

&bull;&nbsp;colocar um comentário (**Não** use caracteres especiais ou acentos)

```git commit -m "Comentario"```

ou

```gc -m "Comentario"```

&bull;&nbsp; Caso tenha instalado o hub **não** vai precisar digitar o comando abaixo:

```git remote add origin https://github.com/nome/repositorio.git``` (**Opcional** caso tenha instalado o hub)

```git push -u origin master```

ou

```gp origin master```

&bull;&nbsp;Atualizar do github para sua máquina

```git pull```

---

&bull;&nbsp;Para trazer do github a sua máquina e levar de volta caso exista o repositorio no github e o mesmo tenha conteúdo:

&bull;&nbsp;criar pasta local

```git clone https://github.com/nome/repositorio.git```

&bull;&nbsp;criar/modificar arquivos locais

```git add .```

ou

```ga .```

&bull;&nbsp;colocar um comentário (**Não** use caracteres especiais ou acentos)

```git commit -m "Comentario"```

ou

```gc -m "Comentario"```

```git push```

&bull;&nbsp;Atualizar do github para sua máquina

```git pull```

---

&bull;&nbsp;Verificar status:

```git status```

ou

```gst```

---

&bull;&nbsp;Verificar quem fez as alterações (Log / Registro):

```git log```

---

&bull;&nbsp;Ramificações (Branch), são "linhas do tempo paralelas" onde os arquivos que estiverem nelas só serão vistos por quem está trabalhando nestas ramificações

&bull;&nbsp;criar ramificação

```git branch nome_da_ramificacao```

&bull;&nbsp;listar ramificações existentes

```gb -l```

&bull;&nbsp;entrar na ramificação

```git checkout nome_da_ramificacao```

ou

```gco nome_da_ramificacao```

&bull;&nbsp;voltar para a "master"

```gco master```

&bull;&nbsp;integrar as modificações da ramificação na master (Obs: tem que estar na master)

```git merge --no-ff nome_da_ramificacao```

&bull;&nbsp;excluir a ramificação

```git branch -d nome_da_ramificacao```

&bull;&nbsp;ramificação que cria o github.io - Github Pages

```gh-pages```

---

Para não levar um arquivo criar um arquivo com o nome .gitignore com a sintaxe:

\# comentário

\*.ext (onde o .ext é a estensão do arquivo que não quer levar) 
