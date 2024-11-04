
# Projeto Git e Github da DIO

Um projeto apenas para guardar os resumos de Git e Github

[Digital Inovation One](dio.me)

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
|$git add [nome e extensão do arquivo]|adiciona o novo arquivo ao commit|
|$git add .|adiciona todos os arquivos da pasta para o commit|
|$git status|verificar a integridade dos arquivos, se estão prontos para envio ou não|
|$git version|Checar a Versão|
|$git push origin [branch]|branch principal: main, pode ser criada uma branch secundária|
|$git pull| é usado para atualizar o repositório local com as alterações mais recentes do repositório remoto|
|$git rm [arquivo] |remover arquivo do pc |
|$git rm -r [diretorio]|remover diretório|
|$git log |histórico|
|$git branch [nome da branch]|criar nova branch|
|$git checkout master|voltar para a branch inicial|
|$git branch -d nomeDoBranchLocal|deletar toda uma brench local|
|$git push origin --delete nomeDoBranchRemoto|deletar toda uma brench remota|
|$git echo [arquivo ou pasta a ignorar] > .gitignore|manda o arquivo para uma área para ser ignorado|

## 🔍 Referências

- [Comandos Git (esses e muito mais)](https://gist.github.com/leocomelli/2545add34e4fec21ec16)
- [DIO](dio.me)
