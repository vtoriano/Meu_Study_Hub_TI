# Política de Segurança

Esta política vale para o repositório **Meu_Study_Hub_TI** (PortfolioHUB) e para a página publicada com GitHub Pages.

## Versões com suporte

| Versão | Suporte |
|--------|---------|
| Branch `main` (versão mais recente) | Sim |
| Versões antigas (tags anteriores) | Não |

## Como reportar uma vulnerabilidade

- Use a aba **Security → Report a vulnerability** deste repositório (relato privado), ou
- envie um e-mail para vitorpupe.08@gmail.com com o assunto "Segurança - PortfolioHUB".

Não abra uma issue pública para falhas de segurança. Informe o que encontrou, onde e, se possível, como reproduzir. Respondo em até 7 dias.

## O que não deve ser publicado neste repositório

- Senhas, tokens, chaves de API e arquivos `.env`.
- Documentos pessoais, números de documentos e endereço residencial.
- Dados de outras pessoas sem autorização delas.

Se algo assim for enviado por engano, o segredo deve ser **revogado e trocado imediatamente**. Apagar o arquivo em um novo commit não basta, porque ele continua no histórico.

## Práticas definidas para este repositório

Estas práticas estão descritas e acompanhadas em `docs/03_Usuarios_e_Seguranca.md`:

- Autenticação em duas etapas na conta do GitHub e na conta Google.
- Proteção da branch `main` (alterações por pull request, sem force push).
- Varredura de segredos e alertas de dependências.
- Compartilhamento de arquivos do Google Drive apenas como "Leitor" para o público.
