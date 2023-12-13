# Resumos Git e GitHub

Repositório dedicado a resumos, comandos e conceitos sobre versionamento de código com Git e GitHub.

## 📝 Documentação

- [Documentação Git](https://git-scm.com/): Recursos completos sobre comandos, fluxos de trabalho e conceitos fundamentais do Git.
- [Documentação GitHub](https://docs.github.com/pt): Documentação oficial do GitHub, abrangendo desde noções básicas até recursos avançados.

## 💻 Resumos

O Git é um sistema de controle de versão poderoso que permite gravar e gerenciar alterações em um repositório local. Aqui estão algumas etapas e dicas úteis para trabalhar com Git:
 ##
## Gravar Alterações em um Repositório Local com Git
## Comandos Git Básicos
#### `Configuração Inicial`

Antes de começar, é essencial configurar seu nome de usuário e endereço de e-mail no Git:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```
 ##
####  `Inicializando um Repositório Git`

Para iniciar o controle de versão em um diretório local, utilizamos o comando `git init`:
 ##
#### `Iniciar um novo repositório`
```bash
git init
```
Esse comando cria um novo repositório Git no diretório atual, preparando-o para controlar as mudanças nos arquivos.
 ##
####  `Clonar um repositório existente`

```bash
git clone URL_do_Repositório
```
Esse comando clona um repositorio existente remotamente.
 ##
####  `Adicionando Arquivos ao Stage`
Para registrar as mudanças nos arquivos e prepará-los para o commit, usamos o comando git add <arquivo>:
```bash
git add <nome_do_arquivo>               
git add .
```  
Prepara os arquivos modificados para serem incluídos no próximo commit.
 ##
####  `Criando um Commit`
Após adicionar os arquivos desejados ao stage, usamos o comando git commit para criar um commit com uma mensagem descritiva:

```bash 
git commit -m "Adiciona alterações no arquivo.txt"
```
 Isso registra as alterações no repositório Git, fornecendo um registro histórico das mudanças feitas.
 ##
####  `Verificando o Status do Repositório`
Para verificar o status atual do repositório, incluindo arquivos modificados, adicionados ao stage ou prontos para commit, utilizamos git status:

```bash
git status
```
O git status fornece informações sobre o estado dos arquivos no repositório, ajudando a acompanhar as mudanças.
 ##
#### `Visualizando o Histórico de Commits`
Para visualizar o histórico de commits no repositório, usamos o comando git log:
```bash
git log
```
O git log exibe uma lista detalhada dos commits, incluindo informações sobre o autor, data e mensagem associada a cada commit.
 ##
 #### `Criar um Novo Branch`
 
```bash
git branch <nome_do_branch>
```
Cria um novo branch onde você pode trabalhar separadamente das alterações principais.
 ##
 #### `Trocar de Branch`

```bash
git checkout <nome_do_branch>
```
Permite alternar entre diferentes branches.
 ##
####  `Mesclar um Branch no Branch Atual`

```bash
git merge <nome_do_branch>
```
Incorpora as alterações de outro branch no branch atual.
 ##
## Sincronização com Repositório Remoto
#### `Adicionar um Repositório Remoto`

```bash
git remote add origin <URL_do_repositório_remoto>
```
Conecta seu repositório local a um repositório remoto.
 ##
#### `Enviar Alterações para o Repositório Remoto`
```bash
git push origin <nome_do_branch>
```
Envia seus commits para o repositório remoto no branch especificado.
 ##
#### `Atualizar o Repositório Local com Alterações Remotas`

```bash
git pull origin <nome_do_branch>
```
Atualiza seu repositório local com as alterações do repositório remoto.
 ##

## 💻 Resumos dos comandos mais utilizados

```bash
git init                   # Inicializa um repositório Git.
git clone                  # Esse comando clona um repositorio existente remotamente.
git add <arquivo>          # Adiciona um arquivo específico para o stage.
git add .                  # Adiciona todos os arquivos alterados
git commit -m "mensagem"   # Cria um commit com os arquivos no stage.
git status                 # Verifica o estado atual do repositório.
git log                    # Exibe o histórico de commits.
git push                   # Envia seus commits para o repositório remoto no branch especificado.
git pull                   # Atualiza seu repositório local com as alterações do repositório remoto.
```
 ##

## `Conclusão`
Gravar alterações em um repositório local é o primeiro passo para gerenciar um projeto com Git. Utilizando os comandos git init, git add, git commit, git status e git log, podemos controlar e registrar as mudanças em nosso código, mantendo um histórico organizado e rastreável das alterações.


