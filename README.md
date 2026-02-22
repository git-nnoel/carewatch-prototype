# 🦉 CareWatch — Protótipo Interativo

**Inteligência que cuida, tecnologia que previne.**

Protótipo interativo da plataforma CareWatch para apresentação a investidores.

## 🚀 Deploy no GitHub Pages

### Opção 1 — Pelo navegador (mais fácil)

1. Crie um repositório no GitHub (ex: `carewatch-prototype`)
2. Faça upload do arquivo `index.html` na raiz do repositório
3. Vá em **Settings → Pages**
4. Em **Source**, selecione **Deploy from a branch**
5. Selecione **main** (ou `master`) e pasta **/ (root)**
6. Clique em **Save**
7. Em ~1 minuto, estará disponível em:
   ```
   https://SEU-USUARIO.github.io/carewatch-prototype/
   ```

### Opção 2 — Via terminal

```bash
git init
git add .
git commit -m "CareWatch prototype"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/carewatch-prototype.git
git push -u origin main
```

Depois ative o GitHub Pages nas Settings do repositório.

## 📁 Estrutura

```
/
├── index.html    ← Aplicação completa (standalone, zero build)
└── README.md     ← Este arquivo
```

## ✅ Características

- **Zero build** — Sem Node.js, npm, ou webpack. Abre direto no navegador.
- **Single file** — Tudo em um único `index.html` (~65KB)
- **React 18** — Carregado via CDN (unpkg)
- **Babel standalone** — Transpila JSX no browser
- **2 rotas internas** — Landing/protótipo + Mockup do app mobile
- **Interativo** — Chat funcional, navegação entre telas, animações
- **Responsivo** — Otimizado para visualização desktop

## 🎨 Identidade Visual

- Roxo escuro `#5B2180` — cor primária
- Verde-menta `#34C77B` / `#C8F0C8` — cor de acento
- Fundo mint `#EFF5EE` — background principal
- Tipografia: DM Sans (Google Fonts)
