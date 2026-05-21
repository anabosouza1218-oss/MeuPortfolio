# Portfólio — Tomas Oliveira de Souza

Portfólio pessoal desenvolvido em HTML, CSS e JavaScript puro. Single-page, sem frameworks, sem dependências externas.

**Live:** [anabosouza1218-oss.github.io/MeuPortfolio](https://anabosouza1218-oss.github.io/MeuPortfolio/)

---

## Seções

- **Hero** — apresentação com animação de partículas e cursor customizado
- **Projetos** — cards com preview via screenshot, links para repositório e live demo
- **Skills** — stack técnica com barras animadas por IntersectionObserver
- **Sobre** — bio e logo
- **Experiência** — timeline de formação e experiência profissional
- **Contato** — links para GitHub, LinkedIn, WhatsApp e email

## Tecnologias

HTML · CSS · JavaScript · Canvas API · Web Crypto API

## Modo Admin

O portfólio tem um sistema de edição protegido por senha (hash SHA-256). Para acessar:

1. Clique em qualquer botão ✏️ ou tente editar qualquer seção
2. Digite a senha no modal que aparecer
3. Com o modo admin ativo, é possível editar textos, adicionar, editar e deletar projetos
4. Clique em **Sair** no badge roxo para encerrar a sessão

> A senha é armazenada como hash SHA-256 na variável `ADMIN_HASH` no script. Para trocar, gere o hash da nova senha em [emn178.github.io/online-tools/sha256](https://emn178.github.io/online-tools/sha256.html) e substitua o valor.

## Estrutura

```
MeuPortfolio/
└── dev_portfolio.html   # arquivo único — tudo em um só lugar
```

## Como rodar

Abra `dev_portfolio.html` direto no navegador. Não precisa de servidor.

Para publicar no GitHub Pages, suba o arquivo para um repositório e ative Pages na branch `main`.

---

Desenvolvido por **Tomas Oliveira de Souza** · Rio Branco, AC
