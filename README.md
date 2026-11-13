# ERP SaaS Multi-tenant (Java / Spring Boot / PostgreSQL)

> Projeto independente em desenvolvimento, com foco em gestão comercial, estoque e financeiro para múltiplas empresas.

## Visão técnica

- API REST em Java e Spring Boot 3.x.
- Spring Security / JWT para autenticação e autorização.
- PostgreSQL com JPA/Hibernate e migrations Flyway.
- Separação de dados por tenant (`tenantId`), filtros Hibernate e verificações de integridade de negócio.
- Auditoria, soft delete e controle de concorrência otimista com `@Version`.

## Domínios desenvolvidos e estudados

- Autenticação, usuários e multi-tenancy.
- Produtos, clientes e fornecedores.
- Estoque, saldos e movimentações de entrada/saída/ajuste.
- Pedidos de compra e de venda com regras de confirmação e cancelamento.
- Contas a pagar e a receber, com fluxo transacional e rastreabilidade.

## Arquitetura e planejamento

O roadmap de 0 a 36 meses organiza a evolução da prova de conceito, a validação do produto, as prioridades, a capacidade, os riscos técnicos e a preparação para crescimento. A descrição pública não inclui números internos de custo, fornecedores, clientes ou projeções confidenciais.

## Estado do repositório

**Documentação para portfólio. O código-fonte, migrations e testes reais ainda não foram anexados.** Não trate esta pasta como um clone executável nem como uma versão estável de produção.

## Próximos passos

- Adicionar código-fonte revisado e sem credenciais.
- Incluir diagramas de domínio e README de execução.
- Incluir exemplos de testes e dados fictícios.
- Documentar testes de isolamento multi-tenant e hardening.
