# Site da Lastro — rascunho para revisão

Landing page da **Lastro** (assessoria de gestão financeira e administrativa
para PME) em abas navegáveis, com animações de transição.

> Rascunho de layout para o Carlos e a Yohana revisarem. Paleta, tipografia e
> textos são proposta — a identidade visual oficial ainda não existe.

## Como abrir

É um único arquivo estático, sem build. Basta abrir `index.html` no navegador
(duplo clique) ou servir a pasta:

```bash
python -m http.server 8000
# depois abra http://localhost:8000
```

As fontes (Newsreader + Libre Franklin) vêm do Google Fonts, então a primeira
carga precisa de internet.

## Abas

- **Início** — herói, princípios e o que é a Lastro
- **O que fazemos** — as três frentes (BPO, painel, diagnóstico) e a fronteira com o contador
- **Selos** — os seis selos de qualidade
- **Preços** — comparativo de custo, combo e prazos (SLA)
- **Quem somos** — a equipe

## Editar

Todo o conteúdo, estilo e script estão dentro do próprio `index.html`.
