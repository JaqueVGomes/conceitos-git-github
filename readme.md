# Conceitos de Git e Github
Este arquivo tem como objetivo armazenar os comandos básicos para utilização do Git e Github 

## Configuração inicial 
Rode os comeandos abaixo no terminal (cmd) do seu computador 
``` bash

git config --global user.name "Jaqueline V. Gomes"
git config --global user.email jaqueline.mengon@fatec.sp.gov.br
```

## Comandos do Git 
Para iniciar o Git em uma pasta do computador utilizamos o init. 
**IMPORTANTE:** Só é executado 1 vez. 
```bash 
git init 
```

Para vincular o projeto ao Github utilizamos o comando remote, basta o repositório estar criando no Github e seguir a segunda opçãp da lista de comandos que aparece no site. 
**Importante:** Depois do remote deve ser executados os outros 2 comandos da página. 
```bash
git remote add origin < url_repositorio_github >
```

Para verificar a situaçãop do repositório (pasta) usamos o status a qualquer momento. 
```bash 
git status
```
Quando o status mostrar arquivos em vermelho é necessário rodar o add para adicionar os arquivos a serem salvos. 
Para add usar 
```bash 
git add .
```

Para commit (salvar)
```bash 
git commit -m "escrever o que quer comunicar/lembrar"
```

Para baixar as alterações que estão apenas no Github utilizamos o pull. 
**Importante:** Sempre deve baixar a ultima versão da nuvem antes de enviar a atual do computador
```bash 
git pull
```

Para enviar os commits do pc para o Github utilizamos o push.
```bash 
git push
```

