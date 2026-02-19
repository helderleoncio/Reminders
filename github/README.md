# Comandos Essenciais do Git

Um guia de referência com os principais comandos do Git, organizados por categorias.

## 🌱 Básicos

* `git init`: Criar um novo repositório.
* `git clone`: Copiar um repositório existente.
* `git status`: Ver alterações pendentes.
* `git add .`: Adicionar alterações à área de preparação (staging).
* `git commit -m "mensagem"`: Salvar suas alterações com segurança.

---

## 🔄 Sincronização

* `git pull`: Trazer alterações do repositório remoto.
* `git push`: Enviar alterações ao repositório remoto.
* `git remote add <url>`: Conectar seu repositório local com o remoto.
* `git fetch`: Baixar as alterações, mas sem mesclá-las.

---

## 🌿 Branches

* `git branch`: Listar, criar ou excluir branches.
* `git switch <nome-da-branch>`: Mudar de branch.
* `git merge <nome-da-branch>`: Mesclar alterações de outra branch.
* `git branch -d <nome-da-branch>`: Excluir uma branch.

---

## ↩️ Desfazer Alterações

* `git restore <arquivo>`: Desfazer alterações em um arquivo.
* `git reset HEAD <arquivo>`: Remover um arquivo da área de preparação.
* `git revert <id-commit>`: Criar um commit que reverte outro.

---

## 🚀 Avançado

* `git log --oneline --graph --all`: Ver histórico de commits resumido e visual.
* `git stash`: Salvar alterações temporariamente sem fazer um commit.
* `git stash pop`: Restaurar alterações salvas.
* `git rebase <branch>`: Reaplicar commits de uma branch em outra para um histórico limpo.
* `git cherry-pick <id-commit>`: Aplicar um commit específico em outra branch.