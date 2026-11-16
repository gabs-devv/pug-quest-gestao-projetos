# Pug Quest - Gestão do Projeto com Scrum

Repositório acadêmico destinado à segunda entrega da disciplina de Gestão de Projetos. O conteúdo demonstra a aplicação do Scrum e do GitHub Projects no planejamento do Pug Quest, projeto de TCC voltado ao gerenciamento de campanhas de RPG de mesa online.

## Identificação

- **Aluno:** Gabriel Henrique de Oliveira Campos
- **Curso:** Sistemas de Informação - Centro Universitário de Itajubá - FEPI
- **Orientador e stakeholder:** Alyson Benoni Matias Pereira
- **Entrega:** 18 de novembro de 2026
- **GitHub Project:** [Pug Quest - Gestão com Scrum](https://github.com/users/gabs-devv/projects/1)

## Objetivo da entrega

A entrega registra as etapas, as versões e as tarefas do Pug Quest em uma ferramenta real de gestão. O quadro Kanban permite acompanhar o Product Backlog, o trabalho pronto para iniciar, as atividades em andamento, a revisão e a conclusão.

O repositório concentra as Issues e a documentação da implementação local planejada. O foco desta entrega está na gestão do projeto e na rastreabilidade do trabalho.

## Tecnologias previstas

| Camada | Tecnologia | Responsabilidade |
| --- | --- | --- |
| Frontend | React com Next.js | Interface, páginas, componentes e navegação |
| Backend | Node.js | Regras de negócio, validações e autorização |
| Dados | Supabase com PostgreSQL | Persistência, autenticação e políticas de acesso |
| Gestão | GitHub Projects | Backlog, estados, Sprints, prioridades e acompanhamento |
| Versionamento | Git e GitHub | Issues, branches, commits, Pull Requests, tags e releases |

## Papéis do projeto

Como o projeto é individual, Gabriel Henrique de Oliveira Campos acumula os papéis de Product Owner, Scrum Master e Developer. O orientador Alyson Benoni Matias Pereira atua como stakeholder acadêmico.

## Fluxo Kanban

O GitHub Project utiliza os estados abaixo:

1. **Backlog:** item cadastrado e ainda não iniciado.
2. **Ready:** item detalhado e preparado para execução.
3. **In progress:** atividade em execução.
4. **In review:** incremento aguardando validação.
5. **Done:** atividade concluída conforme os critérios de aceite.

## Sprints

| Sprint | Objetivo | Issues principais |
| --- | --- | --- |
| Sprint 0 | Planejamento e ambiente de gestão | PUG-01 |
| Sprint 1 | Fundação local | PUG-02 e PUG-03 |
| Sprint 2 | Campanhas e acesso | PUG-04 a PUG-06 |
| Sprint 3 | Conteúdo narrativo | PUG-07 a PUG-09 |
| Sprint 4 | Campo de batalha | PUG-10 e PUG-11 |
| Sprint 5 | Qualidade e entrega | PUG-12 a PUG-16 |

## Versões planejadas

| Versão | Marco | Conteúdo mínimo |
| --- | --- | --- |
| v0.1.0 | Fundação local | Ambiente, arquitetura inicial, banco e execução integrada |
| v0.2.0 | Gestão de campanhas | Autenticação, perfis, campanhas, convites e participantes |
| v0.3.0 | Conteúdo narrativo | Personagens, locais, histórias, informações e bestiário |
| v0.4.0 | Campo de batalha | Mapas, grid e miniaturas |
| v1.0.0 | Versão para avaliação | Testes, documentação, implantação e avaliação com usuários |

## Product Backlog

O Product Backlog possui 16 Issues numeradas de PUG-01 a PUG-16. Cada Issue contém descrição, critérios de aceite, checklist técnico, prioridade, estimativa em Story Points, Sprint, versão, dependências e evidências esperadas.

A lista completa está disponível na [área de Issues](https://github.com/gabs-devv/pug-quest-gestao-projetos/issues).

## Rastreabilidade

O fluxo planejado relaciona cada requisito ao trabalho executado:

1. Uma Issue registra a necessidade e os critérios de aceite.
2. A atividade recebe Sprint, versão, prioridade e estimativa.
3. A implementação futura utiliza uma branch associada à Issue.
4. Os testes e as evidências acompanham a Pull Request.
5. O incremento validado integra uma tag e uma release.

## Implementação local planejada

A estrutura técnica considera diretórios separados para frontend, backend, Supabase e documentação. As instruções detalhadas estão em [Implementação local](docs/implementacao-local.md).

A gestão da entrega não declara funcionalidades como concluídas sem evidências. Os itens técnicos permanecem no Backlog ou em Ready até que a implementação funcional seja realizada.

## Documentação

- [Relatório da Entrega 2](docs/entrega-2.md)
- [Sprints e versões](docs/sprints-e-versoes.md)
- [Implementação local](docs/implementacao-local.md)
- [Roteiro da apresentação](docs/roteiro-apresentacao.md)

## Definição de pronto

Uma atividade somente será considerada concluída quando atender aos critérios de aceite, possuir evidências verificáveis, registrar as validações realizadas, atualizar a documentação aplicável e permanecer vinculada ao histórico correspondente no GitHub.
