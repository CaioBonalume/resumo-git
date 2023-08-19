
# Resumo | Git e GitHub

Repositório para armazenar atalhos e anotações sobre Git e GitHub.

## ✍️Comandos GitBash

### Config
```
• git config - todas opções de config
• git config —global credential.helper (cache/store)- Salva credencial - cache salva temporário store salva permanente
• git config —global credential.helper - Para ver se a credencial esta como cache ou store
• git config —global —show-origin credential.helper - Mostra o caminho da pasta
```

### Geral
```
• clear - Ou Ctrl+L limpa o terminal
• touch - cria arquivo ou pasta vazia
• git status - Mostra arvore de trabalho/index
• git log - Mostra os logs dos commits realizados
• rm -rf .git - Força remoção do git
• git restore (nome) - Restaura arquivo que esta no remoto
• git clone - Clona repositório Git para um novo diretório local.
• git pull - Busca alterações no repo remoto para atualizar o local
• git push - Força as alterações do repo local para o remoto
• touch .gitkeep - Força o git a reconhecer um diretório vazio
• git add (nome) - Colocando nome da pasta ou arquivo adiciona apenas o mesmo para lista de commits
• git add . - Adiciona todas as pastas e arquivos novos para serem commitados
```

### Commit
```
• git commit - Grava alterações no repo local.
• git commit -m"" - M é de mensagem deste commit, que deve ser colocada dentro das aspas
• git commit --amend - Edita a msg do commit (p/ sair Esc: W)
• git commit --amend -m"" - Corrige a msg do commit
• git commit reflog - Mostra log de todos commits
```

### Reset
```
• git reset --soft (hash do commit) - Restaura os arquivos que já existiam no commit selecionado sem apagar os novos arquivos
• git reset --mixed (hash) - É o default do reset, Restaura o commit e deixa untracked os arquivos que foram adicionados posteriormente
• git reset --hard (hash) - Desfaz todos novos arquivos depois do commit selecionado
• git reset (nome) - Nome do arquivo ou pasta, tira o arquivo do commit
```

### Resotore
```
• git restore --staged (nome) - 
```

```

```

## Autores

- [@CaioBonalume](https://github.com/CaioBonalume)


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://google.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/caio-bonalume-87b1974b/)

