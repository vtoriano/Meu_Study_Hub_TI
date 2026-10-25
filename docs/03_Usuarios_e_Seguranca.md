# 3. Gestão de Usuários e Segurança

## Gestão de usuários no GitHub

Princípio adotado: **menor privilégio**. Cada pessoa recebe apenas a permissão de que precisa.

| Papel | O que pode fazer | Quando usar |
|-------|------------------|-------------|
| Owner (dono) | Tudo, inclusive apagar o repositório | Somente eu |
| Admin | Gerenciar configurações e usuários | Ninguém, além do dono |
| Maintain | Gerenciar o repositório sem ações destrutivas | Colaborador de confiança |
| Write | Enviar alterações e abrir pull requests | Colaborador de projeto |
| Triage | Gerenciar issues e pull requests, sem enviar código | Revisor |
| Read | Ver e clonar | Qualquer pessoa convidada só para ler |

Colaboradores atuais: _[preencher: nenhum / nome e papel]_.

Como convidar: repositório → **Settings → Collaborators → Add people** → escolher o papel.

## Políticas de segurança

| Política | Onde configurar | Status |
|----------|-----------------|--------|
| Autenticação em duas etapas na conta GitHub | Foto de perfil → Settings → Password and authentication | [ ] |
| Autenticação em duas etapas na conta Google | myaccount.google.com → Segurança | [ ] |
| Proteção da `main` (pull request obrigatório, sem force push, sem exclusão) | Settings → Rules/Branches | [ ] |
| Varredura de segredos e proteção contra envio de segredos | Settings → Advanced Security (ou Code security) | [ ] |
| Alertas de dependências (Dependabot) | Settings → Advanced Security | [ ] |
| Relato privado de vulnerabilidades | Settings → Advanced Security | [ ] |
| Arquivo `SECURITY.md` na raiz | Já criado | [ ] |
| `.gitignore` para evitar arquivos sensíveis | Raiz do repositório | [ ] |
| Compartilhamento de arquivos Google como "Leitor" | Compartilhar → Qualquer pessoa com o link | [ ] |

Marque cada item só depois de fazer e guardar o print.

## Uso do Gemini na segurança

O Gemini foi usado para revisar esta lista e sugerir melhores práticas. O registro das perguntas e das decisões está em [06_Uso_do_Gemini.md](06_Uso_do_Gemini.md).

## Dados que não entram no repositório

Senhas, tokens, chaves de API, documentos pessoais e dados de terceiros (ver `SECURITY.md`).
