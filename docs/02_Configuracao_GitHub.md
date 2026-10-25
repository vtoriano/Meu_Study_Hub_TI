# 2. Configuração Inicial e Integração com o GitHub

## Ambiente dedicado

O ambiente do PortfolioHUB é o repositório público `vtoriano/Meu_Study_Hub_TI`, com a branch `main` como versão publicada pelo GitHub Pages.

- Repositório: https://github.com/vtoriano/Meu_Study_Hub_TI
- Página: https://vtoriano.github.io/Meu_Study_Hub_TI/

## Armazenamento de projetos

Cada projeto fica em uma pasta própria dentro de `03_Projetos_e_Certificados/`, com um `README.md` que explica o objetivo, as tecnologias, como executar e o estado do projeto.

```text
03_Projetos_e_Certificados/
├── README.md                   # índice de projetos e certificados
└── <Nome_do_Projeto>/
    ├── README.md
    └── ...arquivos do projeto
```

O índice `03_Projetos_e_Certificados/README.md` lista todos os projetos, e a página do portfólio (`index.html`) aponta para eles.

## Padrões

- Nomes de pastas sem espaço nem acento, usando `_` entre as palavras.
- Commits no formato `tipo: descrição` (ver `CONTRIBUTING.md`).
- Versões marcadas com tags: `v1.0`, `v1.1` e, nesta etapa, `v2.0` (PortfolioHUB).
- GitHub Pages publicando a branch `main`, pasta raiz.

## Checklist

- [ ] Repositório público com descrição e tópicos (About → engrenagem)
- [ ] README principal atualizado com a seção PortfolioHUB
- [ ] Pelo menos um projeto novo em `03_Projetos_e_Certificados/` com README
- [ ] Pasta `docs/` publicada
- [ ] Tag `v2.0` criada
