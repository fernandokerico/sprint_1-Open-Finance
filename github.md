#  Comandos do Git

Aqui estão os principais comandos do Git:

##  Comandos Básicos de Navegação

```bash
ls
```
> Lista os arquivos e diretórios da pasta atual.

```bash
cd 
```
> Entra no diretório especificado.

```bash
cd ..
```
> Volta para o diretório anterior.

---

##  Inicializando e Configurando o Git

```bash
git init
```
> Inicializa um repositório Git no diretório atual.

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
```
> Define o nome e e-mail do usuário para os commits.

---

##  Status e Histórico

```bash
git status
```
> Mostra o status atual dos arquivos no repositório.

```bash
git log
```
> Exibe o histórico de commits.

---

##  Adicionando

```bash
git add .
```
> Adiciona todas as mudanças para o próximo commit.

```bash
git commit -m "Mensagem do commit"
```
> Registra as mudanças no histórico do Git.

---

##  Branchs

```bash
git branch
```
> Lista todas as branchs do repositório.

```bash
git branch nome-da-branch
```
> Vai criar uma nova branch.

```bash
git switch nome-da-branch
```
> Troca para outra branch.

```bash
git merge nome-da-branch
```
> Junta a branch especificada com a branch atual.

---

##  Trabalhando com Repositórios Remotos

```bash
git clone Link_do_REPOSITORIO
```
> Clona um repositório remoto para sua máquina.

```bash
git remote add origin Link_do_Reppsitório
```
> Adiciona um repositório remoto.

```bash
git push origin main
```
> Envia os commits para o repositório remoto.

```bash
git pull origin main
```
> Atualiza o repositório local com as mudanças do remoto.

---
