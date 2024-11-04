
# Projeto Git e Github da DIO

Um projeto apenas para guardar os resumos de Git e Github

[DIO (Digital Inovation One)](dio.me)

## 📑 Documentação

- [Git](https://git-scm.com/doc)
- [Github](https://docs.github.com/pt)

## 🏹 Resumos das aulas

Iniciando o Github 
```
// Inicialização do programa

echo "# Teste2" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/RLGuwu/repositório.git
git push -u origin main
```

```
// Conectar programa

git remote add origin https://github.com/RLGuwu/repositório.git
git branch -M main
git push -u origin main
```

Alguns comandos: 
|Comandos|Explicação|
|--------|----------|
|$git clear|Limpa a tela de exibição|
|$git add [Nome e extensão do arquivo]|Adiciona o novo arquivo ao commit|
|$git add .|Adiciona todos os arquivos da pasta para o commit|
|$git status|Verificar a integridade dos arquivos, se estão prontos para envio ou não|
|$git version|Checar a Versão|
|$git push origin [branch]|Branch principal: main, pode ser criada uma branch secundária|
|$git pull| É usado para atualizar o repositório local com as alterações mais recentes do repositório remoto|
|$git rm [arquivo] |Remover arquivo do pc |
|$git rm -r [diretorio]|Remover diretório|
|$git log |histórico|
|$git echo [caminho ou arquivo ou pasta] > .gitignore|Manda o arquivo para uma área para ser ignorado|
|$git reset --soft [cache]|Manda todos os arquivos do commit indicado pelo cache para a área de preparação
|$git reset --mixed [cache]|Manda todos os arquivos do commit indicado pelo cache para a área anterior a da preparação, sendo assim, não reconhece os arquivos|
|$git reset --hard [cache]|Destroi todos os arquivos do commit indicado pelo cache |
|$git reset [caminho do arquivo ou pasta]|Manda o arquivo para a área de preparação|

Mexendo mais profundamente Branches 
|Comandos|Explicação|
|--------|----------|
|$git branch [nome da branch]|Criar nova branch|
|$git checkout -b [Nome da branch]|Cria e Muda a branch|
|$git checkout [Nome da branch existente]|Muda a branch|
|$git branch -d [nome da Branch Local]|Deletar toda uma branch local|
|$git push origin --delete nomeDoBranchRemoto|Deletar toda uma branch remota|
|$git branch -v|Lista todas as alterações de todas as branchs|
|$git merge [Nome da branch]|Mescla uma branch em outra principal|
|$git fetch origin main|Puxa os arquivos sem mesclar com os existentes|
|$git clone [link do github] --branch [branch] --sigle-branch|Colar uma branch expecífica remota para o local|
|$git stash|Arquiva modificações para nao levar para outra branch|
|$git stash list|Lista alterações arquivadas|
|$git stash apply|Aplica as alterações na branch|
|$git stash pop|Tira as últimas alterações na branch|


## 🔍 Referências

- [Comandos Git (esses e muito mais)](https://gist.github.com/leocomelli/2545add34e4fec21ec16)
- [DIO](dio.me)
- [Site utilizado para formar este arquivo](https://readme.so/pt/editor)