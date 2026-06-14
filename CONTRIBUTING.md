# Guia de Contribuição — PortfolioHUB

Obrigado pelo interesse em contribuir com o PortfolioHUB! Este documento explica como participar do projeto de forma organizada e respeitosa.

---

## 📌 Antes de Começar

- Leia o [README.md](./README.md) para entender o propósito do projeto.
- Verifique se já existe uma [issue](https://github.com/hypexxbr/portfolioHUB/issues) aberta para o que você quer fazer.
- Se não existir, abra uma antes de começar a codificar.

---

## 🔄 Fluxo de Contribuição

### 1. Fork e Clone

```bash
# 1. Faça um fork pelo botão "Fork" no GitHub

# 2. Clone seu fork localmente
git clone https://github.com/SEU_USUARIO/portfolioHUB.git

# 3. Entre na pasta do projeto
cd portfolioHUB

# 4. Adicione o repositório original como remote
git remote add upstream https://github.com/hypexxbr/portfolioHUB.git
```

### 2. Crie uma Branch

Use nomes descritivos seguindo o padrão:

```bash
git checkout -b tipo/descricao-curta
```

**Exemplos:**
- `feat/adicionar-secao-projetos`
- `fix/corrigir-link-linkedin`
- `docs/atualizar-readme`

### 3. Faça as Alterações

Mantenha o foco em uma única melhoria por branch.

### 4. Commit

Siga a convenção de mensagens de commit:

```
tipo(escopo): descrição curta no imperativo
```

| Tipo | Quando usar |
|---|---|
| `feat` | Nova funcionalidade |
| `fix` | Correção de bug |
| `docs` | Alterações na documentação |
| `style` | Formatação, sem mudança de lógica |
| `refactor` | Refatoração de código |
| `chore` | Tarefas de manutenção |

**Exemplos:**
```bash
git commit -m "docs(readme): adiciona seção de tecnologias"
git commit -m "fix(links): corrige URL do LinkedIn"
git commit -m "feat(projetos): inclui card do projeto BeboSim"
```

### 5. Push e Pull Request

```bash
git push origin tipo/descricao-curta
```

Depois, abra um Pull Request no GitHub com:
- **Título** claro e objetivo
- **Descrição** explicando o que foi feito e por quê
- Referência à issue relacionada (se houver): `Closes #número`

---

## ✅ Padrões do Projeto

- Linguagem dos commits e PRs: **português**
- Documentação em **Markdown**
- Sem armazenar dados sensíveis, tokens ou credenciais no repositório

---

## 🙋 Dúvidas

Abra uma [issue](https://github.com/hypexxbr/portfolioHUB/issues) com a tag `question` ou entre em contato pelo e-mail: celsofonttes@gmail.com
