# Impera Glass — Vidraçaria

Site institucional da **Impera Glass Vidraçaria**, em Itapoã, Brasília&nbsp;–&nbsp;DF.

🔗 **Site:** https://guiavicar.github.io/impera-glass/

## Sobre

Vidraçaria especializada em box de banheiro, espelhos sob medida, portas e janelas
de vidro, guarda-corpo e fachadas comerciais. Atende Brasília e todo o Distrito Federal.

- **WhatsApp / telefone:** (61) 99801-6346
- **Endereço:** Quadra 01, Conjunto B — Fazendinha, Itapoã, Brasília&nbsp;–&nbsp;DF, 71596-156
- **Horário:** segunda a sábado, até às 18h
- **Google:** nota 5,0 com 10 avaliações

## Identidade visual

A paleta do site foi extraída diretamente do logotipo:

| Token | Cor | Origem no logo |
|---|---|---|
| `--ink` | `#0B0B0C` | fundo preto |
| `--line` | `#252626` | moldura |
| `--silver-hi` → `--silver-low` | `#E9EAEA` · `#CDCDCD` · `#9A9C9C` · `#55575A` | wordmark metálico |
| `--glass-deep` → `--glass-hi` | `#1C3C3B` · `#4D6B69` · `#ABBBBB` · `#CDE3E1` | painel de vidro do monograma |

Tipografia: **Cormorant Garamond** (títulos) e **Inter** (texto).

## Estrutura

```
.
├── index.html
├── assets/
│   ├── css/style.css
│   ├── js/main.js
│   └── img/logo.jpg
└── README.md
```

Site estático, sem build. Para rodar localmente:

```bash
python3 -m http.server 8000
```

E abrir http://localhost:8000

## Publicação

Hospedado no GitHub Pages a partir da branch `main`, pasta raiz.
