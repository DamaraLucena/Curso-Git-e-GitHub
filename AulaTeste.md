# Aula Teste Git e GitHub Da Dio

## Anotações da Aula de primeiros comandos

- git init
- git add "\*"
- git add.
- git commit -m "commit inicial"
- git status

## Comandos GitHub

### Comando para desconectar email e nome já cadastrados no git

- git config --global --unset user.email
- git config --global --unset user.nickname

### Comando para adcionar um email e um usuario ao Git

- git config user.email "email cadastrado no github"
- git config user.name "Nome de usuario do github"
- git config --list

### Enviar um repositório existente a partir da linha de comando

- git remote add origin git@github.com:DamaraLucena/Curso-Git-e GitHub.git
- git branch -M main
- git push -u origin main
- git push origin mastar
- git pull origin master(Puxar repositorio antigo, caso ele seja alterado)
