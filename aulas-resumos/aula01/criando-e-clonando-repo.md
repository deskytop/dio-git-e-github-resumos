# Aula 01 - Criando e Clonando Repositórios

## 🤖 Comandos Básicos de Diretórios
Comando para criar diretórios
```
mkdir (nome)
```
Comando para mudar/alternar diretório
```
cd (nome/)
```
Comando para voltar um diretório
```
cd ..
```
***
Atalho **_Ctrl + L_** , limpa terminal
***
Comando para criar um arquivo vazio
```
touch arquivo.extensao
```
## 🖥�?Comandos GitHub Básico
Inicializa um repositório local
```
git init
```
Clona um repositório remoto para o local
```
git clone (url)
```
Se acrescentar um nome ao lado da url, você muda o nome da pasta que será criada no local, caso contrário, permanecerá o nome padrão presente no GitHub
```
git clone (url) nomeAlterado
```
Verifica repositórios remotos vinculados
```
git remote -v
```
Adiciona/Vincula repositório remoto ao local
```
git remote add origin (url) 
```
## 💠 Mais comandos de diretório
Dentro de um repositório local, ao usar o comando, você entra dentro do diretório Git
```
cd .git
```
Lista o conteúdo de um diretório
```
ls
```
Exibe o conteúdo de um arquivo
```
cat (arquivo)
```
__Útil para verificar as configurações do repositório__
```
cat config
```