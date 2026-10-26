# 4. Compartilhamento e Controle de Acesso com GitHub

## Controle de versão

- Todo o conteúdo do PortfolioHUB está versionado com Git no GitHub.
- Cada alteração gera um commit com mensagem descritiva.
- Marcos importantes recebem **tags**: `v1.0` (página inicial), `v1.1` (primeira alteração) e `v2.0` (PortfolioHUB).
- O histórico pode ser consultado em **Commits**, que mostra o antes e o depois de cada alteração.

## Fluxo de colaboração

1. Issue: descreve a tarefa ou sugestão.
2. Branch: cada tarefa em uma branch a partir da `main`.
3. Pull request: propõe a mudança e permite revisão.
4. Merge: só após revisão, na `main` protegida.

Detalhes e padrões estão em [CONTRIBUTING.md](../CONTRIBUTING.md).

## Compartilhamento

| Item | Como é compartilhado |
|------|----------------------|
| Código e projetos | Repositório público no GitHub |
| Página do portfólio | GitHub Pages |
| Documentos e apresentações | Google Drive/Docs, "Qualquer pessoa com o link" como Leitor |
| Vídeo | YouTube, Público ou Não listado |

## Controle de acesso

- Leitura: pública.
- Escrita: somente o dono e colaboradores convidados, com o papel mínimo necessário (ver [03_Usuarios_e_Seguranca.md](03_Usuarios_e_Seguranca.md)).
- Alterações na `main`: apenas por pull request.
- Contribuições externas: por fork e pull request, revisadas antes do merge.

## Como colaborar (resumo)

1. Fazer um fork ou receber convite como colaborador.
2. Criar uma branch, alterar e enviar.
3. Abrir um pull request.

## Prática registrada

## Prática registrada

- Issue: #1, "Ajustar seção de tecnologias no README"
- Branch: 1-ajustar-seção-de-tecnologias-no-readme (1 commit, e196869)
- Pull request: #2, com "Closes #1" na descrição
- Merge: commit f220e89 na main, pelo botão "Merge pull request", sem bypass e sem aprovação, por ser o único dono do repositório
- Branch apagada depois do merge
- Resultado: a issue fechou automaticamente

O que eu aprendi com essa prática: eu tive dificuldades e muitas duvidas, e a principal foi o botão de criar PR, e entre outras, mas aprendi que a main do GitHub bloqueia alterações diretas para exigir revisão e aprovação via Pull Request, protegendo o código principal contra erros, bugs e mudanças não autorizadas.
O que eu faria diferente na próxima vez: : subir a pasta docs na primeira vez, ela me atrasou bastante tempo
