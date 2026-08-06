# Starter — Site para salão / barbearia

Base em Astro para sites de negócios locais de beleza.
Todo o conteúdo vive em ficheiros de dados — não é preciso editar componentes.

## Arrancar um projeto novo

1. Clonar este repositório e renomear a pasta
2. `npm install`
3. Apagar `.git` e ligar ao repositório do cliente
4. Seguir a checklist abaixo

## Checklist de personalização

### Dados
- [ ] `src/data/salao.json` — nome, contactos, morada, horários, legal, SEO
- [ ] `src/data/servicos.json` — preçário
- [ ] `src/data/conteudo.json` — textos de todas as secções

### Marca
- [ ] `src/styles/tokens.css` — bloco MARCA: 6 cores + 2 fontes
- [ ] Instalar fontes via Fontsource (`npm install @fontsource/...`)
- [ ] `src/layouts/Layout.astro` — atualizar os imports das fontes

### Imagens
- [ ] `public/logo.svg`, `logo-simples.svg`, `favicon.svg`
- [ ] `src/assets/hero.jpg` — horizontal,