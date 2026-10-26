# Uso do Google Gemini na implantação

O Google Gemini foi usado como guia e revisor em cada etapa. Este registro mostra o que foi perguntado, o que ele respondeu e o que eu decidi.

> Preencha com as suas conversas reais. As respostas do Gemini devem ser conferidas e adaptadas por mim.

| Etapa | O que perguntei ao Gemini | Resumo da resposta | O que eu decidi ou ajustei | Print |
|-------|---------------------------|--------------------|-----------------------------|-------|
| 1. Planejamento | _[configurar o Gemini como guia (instrução inicial) e revisar o plano de implantação, apontando o que faltava, o que estava vago e o que era irrealista.]_ | _[ele confirmou o papel de guia e apontou pontos a detalhar no plano.]_ | _[Criei o plano de implantação em docs/01 e decidi tratar o PortfolioHUB como evolução do Study Hub, no mesmo repositório.]_ | _[---]_ |
| 2. GitHub | _[um padrão de pastas e README para os projetos, um padrão de mensagens de commit e como configurar descrição e tópicos do repositório.]_ | _[sugeriu renomear o repositório, criar pastas projects/, data/ e notebooks/ e incluir um .gitkeep]_ | _[Mantive o nome Meu_Study_Hub_TI, sem renomear, usei a pasta 03_Projetos_e_Certificados em vez de criar projects/, data/ e notebooks/, corrigi o nome errado que apareceu no HTML, atualizei o título para PortfolioHUB e adicionei a seção de tecnologias no README, sem Scikit-Learn e criei o .gitignore.]_ | _[---]_ |
| 3. Usuários e segurança | _[as políticas de segurança mais importantes, onde ativar cada uma, os papéis de colaborador e uma revisão do SECURITY.md]_ | _[indicou 2FA, proteção da main, secret scanning, Dependabot e relato privado. Também sugeriu o “Bypass rules and merge” e desmarcar regras se o merge travasse.]_ | _[Ativei 2FA com app autenticador e GitHub Mobile, e visualizei os códigos de recuperação sem compartilhá-los, ativei a regra de proteção da main e mantive 0 aprovações, ativei secret scanning, push protection, Dependabot e relato privado de vulnerabilidades, recusei o “Bypass rules and merge”, adicionei SECURITY.md e CONTRIBUTING.md ao repositório.]_ | _[---]_ |
| 4. Compartilhamento e acesso | _[um fluxo de colaboração (issues, branches, PRs e revisão), uma revisão do CONTRIBUTING.md e como controlar quem altera a main]_ | _[confirmou o fluxo e sugeriu ajustes no CONTRIBUTING.md. Pelo que aparece na nossa conversa, sugeriu também mexer nas regras da main]_ | _[Fiz o fluxo completo: issue #1, branch, PR #2 com Closes #1, merge, e branch apagada, depois, subi a pasta docs (PR #3) e registrei a seção de prática (PR #4), ainda não tenho colaboradores convidados.]_ | _[---]_ |
| 5. Testes e finalização | _[o que mais testar antes de considerar o projeto pronto (acessibilidade, links, celular e privacidade).]_ | _[sugeriu cobrir essas áreas. Esse resumo eu não tenho em detalhe, então confira no print.]_ | _[Preenchi o checklist de 10 testes em docs/05 (PR #5), o teste no celular passou, e o vídeo ainda está pendente, marquei o teste de documentos do Google como não aplicável, porque não há links do Drive.]_ | _[---]_ |
| 6. Apresentação | _[o que cortar ou melhorar no roteiro de 5 minutos.]_ | _[: esse resumo eu também não tenho, confira no print.]_ | _[Preparei o roteiro final de 5 minutos, o vídeo final ainda não foi gravado nem publicado.]_ | _[---]_ |

## Como o Gemini foi configurado

Usei a instrução inicial da etapa 1 do PROMPTS_GEMINI.md, pedindo um guia passo a passo e confirmação antes de ações irreversíveis

## Limites que observei

Sugeri renomear o repositório, o que poderia quebrar links.
Sugeri pastas novas (projects/, data/, notebooks/) e um .gitkeep, que não combinavam com a estrutura que já existia.
Escrevi o nome errado no HTML.
Sugeri “Bypass rules and merge” e desmarcar regras da main se o merge travasse.
Listei Scikit-Learn como tecnologia, mesmo você ainda não usando.
