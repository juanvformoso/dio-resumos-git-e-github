# Fluxo de Trabalho com Git

## Branches

- **Criar uma nova branch:**
```bash
git checkout -b nome_da_branch
```

- **Alternar entre branches:**
```bash
git checkout nome_da_branch
```

- **Mesclar branches:**
```bash
git merge nome_da_branch
```

## Pull Requests
- **Criar um pull request:**

        1. Crie uma nova branch e faça as alterações necessárias.
        2. Envie as mudanças para o repositório remoto.
        3. Abra um pull request no GitHub para revisão.

## Resolvendo Conflitos
Quando dois commits em diferentes branches alteram as mesmas linhas de código, pode ocorrer um conflito. Para resolvê-lo:

1. **Identifique os conflitos:** `git status`
2. **Edite os arquivos conflitantes para resolver o conflito.**
3. **Adicione as mudanças resolvidas:** `git add nome_do_arquivo`
4. **Finalize o merge:** `git commit`
