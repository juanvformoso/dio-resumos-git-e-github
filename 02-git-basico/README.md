# Comandos Básicos do Git

## Configuração Inicial

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"

### Iniciar um repositório

```bash
git init

### Clonar um repositório

```bash
git clone https://github.com/usuario/repo.git

### Rastrear arquivos

```bash
git add nome_do_arquivo
git add .

### Commit de alterações

```bash
git commit -m "Mensagem descritiva do commit"

### Visualizar o histórico de commits

```bash
git log

### Visualizar status do repositório

```bash
git status
