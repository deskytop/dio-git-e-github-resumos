# Aula 03 - Desfazendo Alterações no Repositório Local
## 🤖 Comandos de Diretórios
Dentro da pasta de Repositório, força remoção do diretório .git
```
rm -rf .git
```
## 🖥️ Comandos GitHub
Remove o arquivo alterado da área de preparação (git status)
```
git restore (arquivo)
```
Altera mensagem do último commit feito
```
git commit --amend -m "Mensagem nova"
```
Acessa o editor de commit
```
git commit --amend
```
Ao acessar pressione " i " para inserir mensagem, e em seguida aperte "ESC" + ":" + "W" + "Q" para sair
***
Volta os arquivos dos commits posteriores ao indicado para área de preparação (git status)
```
git reset --soft (hash-commit)
```
Adiciona para árvore de trabalho, remove da área de preparação (git status/git add) os arquivos dos commits posteriores ao indicado, os torna "untracked file"
```
git reset --mixed (hash-commit)
```
ou, que é o mesmo
```
git reset (hash-commit)
```
Ignora os arquivos dos commits posteriores ao indicado e os apaga "totalmente"
```
git reset --hard (hash-commit)
```
Exibe um histórico mais detalhado dos commits, para maior controle ou recuperação profunda
```
git reflog
```
Remove o arquivo da área de preparação, os torna untracked
```
git reset (arquivo)
```
ou
```
git restore --staged (arquivo)
```
***
**[Voltar ao Início](../../README.md)**