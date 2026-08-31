# RodBytePublicador

Hospedagem pública das imagens dos carrosséis do Instagram [@rodbyte](https://instagram.com/rodbyte).

A Graph API do Instagram não aceita upload de arquivo: ela busca cada imagem por URL. Este repositório existe para dar essa URL. Nada aqui é código de produção, é só o material publicado.

## Organização

Uma pasta por publicação, nomeada `<data-do-post>-<slug>`:

```
carrosseis/
  2026-08-30-auditoria-skills-claude-code/
    slide-01.jpg ... slide-09.jpg
    legenda.md
    README.md
```

Os slides são numerados na ordem de exibição do carrossel. O publicador monta as URLs a partir dessa numeração, então renomear ou pular número muda a ordem no post.

## Formato dos arquivos

| Item | Valor |
|---|---|
| Dimensões | 1080 x 1440 (aspect 3:4) |
| Formato | JPEG, qualidade 90 |
| Peso | entre 60KB e 200KB por slide |
| Limite da API | 8MB por imagem, 10 imagens por carrossel |

Os PNGs de origem, em 2160 x 2880, ficam no projeto local e não sobem para cá: seriam pesados demais sem ganho, já que o Instagram recomprime tudo.

## Como usar a URL

A base para o publicador é o caminho da pasta em `raw.githubusercontent.com`:

```
https://raw.githubusercontent.com/barbabittencourt-dot/RodBytePublicador/main/carrosseis/<pasta-da-publicacao>
```

Use sempre `raw.githubusercontent.com`. O endereço de `github.com/.../blob/...` devolve uma página HTML, e a API rejeita.

## Publicações

| Data | Publicação | Slides |
|---|---|---|
| 2026-08-30 | [Auditoria de skills no Claude Code](carrosseis/2026-08-30-auditoria-skills-claude-code) | 9 |
