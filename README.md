# 🔒 Kit Retenção Kids — Área de Membros — Área de Membros
Estrutura padronizada (template escalável). **Senha de acesso: 2026** (decisão intencional, não alterar).

## Arquivos
- `index.html` — login (senha).
- `area/index.html` — área do aluno (dirigida por `config.js`).
- `config.js` (raiz e /area/) — identidade do produto: marca, cores e lista de materiais.
- `area/capas/` — miniaturas (capa de cada material).
- `_redirects` — regra Netlify.

## Manutenção
Adicionar material = 1 linha em `config.js` (título + id do Drive) + a capa em `area/capas/<id>.jpg`.
Trocar identidade = mudar `cores.primary` no config (as tonalidades derivam sozinhas).

## Deploy
Netlify conectado a este repo (auto-deploy no push). Publish dir = raiz.
