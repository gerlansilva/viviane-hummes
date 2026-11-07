# Viviane Hummes — site em Quarto

Site acadêmico: https://vivianehummes.pages.dev

## Como editar

- `index.qmd` — apresentação
- `publications.qmd` — lista de publicações e DOI
- `projects.qmd` — projetos
- `supervisions.qmd` — orientações
- `contact.qmd` — contato
- `_quarto.yml` — menu, busca e rodapé
- `quarto-style.css` — visual inspirado no site de Everaldo Silveira

## Visualizar localmente

Instale o [Quarto](https://quarto.org/docs/get-started/) e execute:

```bash
quarto preview
```

Para gerar o site: `quarto render`.

## Publicação

A automação GitHub Actions renderiza os arquivos Quarto, copia o resultado para a raiz do repositório e faz um commit com `[skip ci]`. Esse procedimento permite a continuidade da implantação Git do Cloudflare Pages caso o projeto esteja conectado à branch `main`, com diretório de saída raiz (`.`) e sem comando de build no Cloudflare.

A lista de publicações foi preservada a partir do catálogo HTML existente; **não** há atualização automática em tempo real pelo ORCID. Novos registros devem ser inseridos em `publications.qmd`.
