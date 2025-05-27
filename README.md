
# Resumo | Git e GitHub

Repositório para armazenar atalhos e anotações sobre Git e GitHub.

## ✍️Comandos GitBash

### ⚙️Config
| Comandos | Função |
|------|--------|
|`git config` | Mostra todas opções de config |
|`git config —global credential.helper (cache/store)` | Salva credencial - cache salva temporário store salva permanente |
|`git config —global credential.helper`| P/ ver se a credencial esta como cache ou store |
|`git config —global —show-origin credential.helper`| Mostra o caminho da pasta |

### Geral
| Comandos | Função |
|------|--------|
|`clear` | Ou **Ctrl+L** limpa o terminal |
|`touch` | Cria arquivo ou pasta vazia |

### Git
| Comandos | Função |
|------|--------|
|`git init` | Cria um repositório |
|`git status` | Mostra arvore de trabalho/index |
|`git log` | Mostra os logs dos commits realizados |
|`git clone (URL)` | Clona repositório Git p/ um novo |
|`git clone (URL) --branch (nome branch) --single-branch`|Clona branch|
|`git pull` | Busca alterações no repo remoto p/ atualizar o local |
|`git push` | Força as alterações do repo local p/ o remoto |
|`git push -u origin main` | Envia alterações p/ repositório remoto // -u é abreviação p/ setupstream |

### ➕Add
| Comandos | Função |
|------|--------|
|`git add (nome)`| Colocando nome da pasta ou arquivo adiciona apenas o mesmo p/ lista de commits |
|`git add .`| Adiciona todas as pastas e arquivos novos p/ serem commitados |

### Commit
| Comandos | Função |
|------|--------|
|`git commit`|Grava alterações no repo local|
|`git commit -m""`|M é de mensagem deste commit, que deve ser colocada dentro das aspas|
|`git commit --amend`|Edita a msg do commit (p/ sair pressionar Esc escrever : W)|
|`git commit --amend -m""`|Corrige a msg do commit|
|`git commit reflog`|Mostra log de todos commits|

### 🔗Remote
| Comandos | Função |
|------|--------|
| `git remote add origin (URL)`| Link do local com o remoto |
|`git remote remove origin`| Remove qualquer origin que tenha |
|`git remote rm origin`| Força a remoção de um origin |

### 🔙Reset
| Comandos | Função |
|------|--------|
| `git reset --soft (hash do commit)` | Restaura os arquivos que já existiam no commit selecionado sem apagar os novos arquivos |
|`git reset --mixed (hash)`|É o default do reset, Restaura o commit e deixa untracked os arquivos que foram adicionados posteriormente|
|`git reset --hard (hash)`|Desfaz todos novos arquivos depois do commit selecionado|
|`git reset (nome)`|Nome do arquivo ou pasta, tira o arquivo do commit|

### ↩️Resotore
| Comandos | Função |
|------|--------|
|`git restore (nome)` | Restaura arquivo que esta no remoto |
|`git restore --staged (nome)`||

### 🪢Branch
Ramificação do projeto, utilizada para testar novos recursos no seu código, branch principal será a main (antiga master). O main vai continuar apontando para o ultimo commit feito, e a branch vai criar novos commits que não estão ligados ao original.

| Comandos | Função |
|------|--------|
|`git branch -M main`| Força renomeação de master p/ main|
|`git branch`|Lista as branches do repositório|
|`git checkout (nome branch)`|Acessa a branch selecionada|
|`git branch -d (nome)`|Deleta branch selecionada|
|`git checkout -b (nome branch)` | Cria/Troca para branch selecionada |
|`git branch -v`| Lista o último commit de cada branch|
|`git merge (nome da branch)`| Mescla a branch selecionada a main|
|`git diff (branch1) (branch2)`|Retorna arquivos que estão diferentes|
|`git merge (branch)`|Mescla uma branch a main|

### Tabela de Nomenclaturas de Versão e Estágios de Desenvolvimento
| Nomenclatura Padrão | Outras Variações Comuns | Uso Principal | Quando Usar | Versionamento Após a Nomenclatura?
|-----|-----|-----|-----|-----|
|Pré-alpha|`pre-alpha, milestone`|Fase inicial de desenvolvimento, conceitos ou protótipos muito instáveis.|Quando o desenvolvimento está apenas começando, funcionalidades básicas não estão prontas, e há grande instabilidade. Apenas para devs.|`0.0.1-pre-alpha.1`|
|Alpha|`alpha, a`|Primeira fase de testes internos ou com um grupo muito restrito de usuários.|Quando as funcionalidades básicas estão implementadas, mas há muitos bugs e funcionalidades incompletas. Foco em encontrar bugs.|`0.1.0-alpha.1`|
|Beta|`beta,b`|Segunda fase de testes com um público maior, focado em usabilidade e feedback.|Quando a maioria das funcionalidades está implementada e testada, mas ainda pode haver bugs e pequenos ajustes de UI/UX.|`0.5.0-beta.1`|
|Release Candidate|`RC, rc`|Versão quase final, com potencial de ser a versão de lançamento se não houver bugs críticos.|Quando o software está funcionalmente completo e estável, mas precisa de um último ciclo de testes para garantir a qualidade final.|`1.0.0-rc.1`|
|Release (GA)|`GA`|Versão final e estável, disponível para o público em geral.|Quando o software passou por todas as fases de teste e está pronto para uso em produção.|`1.0.0`|
|Patch|`fix`|Pequenas correções de bugs, segurança ou melhorias sem novas funcionalidades.|Após o lançamento de uma versão estável, para corrigir problemas encontrados em produção.|`1.0.1`|
|Major/Minor|`update, feature`|Novas funcionalidades significativas ou pequenas (respectivamente), quebram ou não compatibilidade.|Para lançamentos de novas funcionalidades ou grandes mudanças no software.|`1.1.0`

### Extras
| Comandos | Função |
|------|--------|
|`git fetch`|Baixa alterações mas ainda não quer mesclar|
|`rm -rf .git`|Força remoção do git|
|`touch .gitkeep`|Força o git a reconhecer um diretório vazio|
|`git stash`|Arquiva modificações|
|`git stash list`|Lista modificações arquivadas|
|`git stash pop`|Traz as modificações e exclui a alteração mais recente|
|`git stash apply`|Mantem a modificação na lista p/ uso posterior|


## Autores

- [@CaioBonalume](https://github.com/CaioBonalume)


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://google.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/caio-bonalume-87b1974b/)

