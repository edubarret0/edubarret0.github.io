Projeto: edubarret0.github.io

Organização proposta e atualizações aplicadas:

- `/templates/header.html` e `/templates/footer.html` — fragmentos HTML reutilizáveis.
- `/assets/js/site.js` — utilitários para incluir templates, carregar markdown e controlar o tema (localStorage).
- `/pages/*.html` — páginas agora mínimas; carregam conteúdo de `/content/*.md` usando `marked`.
- `/content/*.md` — conteúdo em Markdown para cada página.

Como testar localmente:

1. Inicie um servidor estático na raiz do projeto (recomendado: Python 3)

```bash
python3 -m http.server 8000
```

2. Abra `http://localhost:8000/pages/projetos.html` e verifique o carregamento do conteúdo e o botão de tema.

Notas:
- A página usa `https://cdn.jsdelivr.net/npm/marked/marked.min.js` para renderizar Markdown.
- Se preferir, `marked` pode ser baixado para `assets/js/marked.min.js` e referenciado localmente.
