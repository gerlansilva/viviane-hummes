# Portfólio acadêmico — Viviane Hummes

Versão baseada nos arquivos fornecidos pelo usuário, preservando biografia, fotografias, projetos e catálogo de publicações. O visual foi ajustado com cabeçalho azul, fonte Open Sans e temas de pesquisa em tags coloridas. A página de produção inclui busca por título e mantém os links DOI existentes.

## GitHub
Crie um repositório (por exemplo, `viviane-hummes-site`) e envie **os arquivos desta pasta na raiz**, não o ZIP. Ao criar o repositório, conecte o projeto existente `vivianehummes` do Cloudflare Pages ao GitHub (Settings / Builds & deployments, conforme a interface disponível), ou configure um novo Pages apontando para esse repositório.

## Cloudflare Pages
- Projeto que corresponde ao domínio informado: `vivianehummes` (confirme no painel antes da implantação).
- Para integração GitHub: **Framework preset** `None`, **Build command** vazio, **Build output directory** `/` (raiz).
- Para implantação via Wrangler, com acesso autenticado à conta Cloudflare: `npx wrangler pages deploy . --project-name vivianehummes`.
- **Importante:** não use `everaldo-site` como nome do projeto; esse nome constava incorretamente no `wrangler.jsonc` original.

## Publicações
A versão atual preserva o catálogo estático que já veio no material original, com as URLs DOI disponíveis; não reivindica sincronização automática em tempo real. Novos registros ORCID exigem atualização de conteúdo ou implementação futura de API.

## Estado da publicação
Este pacote está preparado para GitHub/Cloudflare, mas sua publicação requer acesso ao repositório GitHub e à conta Cloudflare Pages. A criação deste ZIP não modifica o site online.
