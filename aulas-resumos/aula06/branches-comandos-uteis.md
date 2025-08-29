# Aula 06 - Trabalhando com Branches - Comandos Úteis
## 🖥️ Comandos GitHub
Baixa informações do Repositório Remoto para o Local sem mesclar
```
git fetch origin main
```
Verifica diferença entre branches
```
git diff main origin/main
```
Aplica as alterações do Repositório Remoto para o Local
```
git merge origin/main
```
Clona apenas uma branch de um Repositório
```
git clone url --branch nome-da-branch --single-branch
```
Arquiva uma modificação feita para não aplica-la em uma nova branch
```
git stash
```
Mostra modificações arquivadas
```
git stash list
```
Traz as modificações arquivadas para branch e exclui alterações mais recentes da pilha
```
git stash pop
```
Mantém modificação na lista para uso posterior, traz para a branch
```
git stash apply
```
***
**[Voltar ao Início](../../README.md)**