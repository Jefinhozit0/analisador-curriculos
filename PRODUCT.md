# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Hipótese a confirmar: pessoas candidatas a vagas de emprego que querem
entender como o currículo se relaciona com uma oportunidade específica.

## Product Purpose

Comparar um currículo com uma vaga e apresentar sugestões para adequá-lo
aos requisitos da oportunidade, sem inventar habilidades ou experiências.
O objetivo é ajudar a pessoa usuária a identificar requisitos e decidir
quais qualificações verdadeiras destacar.

## Positioning

A aplicação permite conferir a comparação e as sugestões antes de gerar
uma prévia do PDF; o processamento usa Ollama local, conforme descrito
no projeto. Não há evidência de que o sistema garanta resultados ou
adequação a uma vaga.

## Capabilities and Constraints

- Recebe um currículo em PDF e a descrição da vaga em texto ou imagens.
- A transcrição de imagens da vaga deve ser confirmada antes da comparação.
- Permite revisar sugestões e conferir uma prévia do PDF antes do download.
- As sugestões não devem inventar habilidades ou experiências.
- Projeto em desenvolvimento; as funcionalidades ainda precisam de testes.

## Evidence on Hand

- [README.md](./README.md) descreve o propósito, o uso de Ollama local e
  a restrição de não inventar qualificações.
- A interface existente e os testes do projeto implementam o fluxo de
  comparação, confirmação da transcrição e revisão de alterações.
- Não há depoimentos, métricas, resultados de contratação ou outros
  materiais de validação disponíveis; não os apresentar como fatos.

## Product Principles

- Não atribuir à pessoa candidata qualificações sem evidência no currículo.
- Tornar os requisitos da vaga e as evidências do currículo verificáveis.
- Manter a pessoa usuária no controle das sugestões e do PDF final.
- Explicar estados, erros e próximos passos com clareza.

## Open Decisions

- Público prioritário e contexto de uso ainda não foram confirmados.
- As prioridades de melhoria da lógica e eventuais requisitos de
  acessibilidade precisam de confirmação.
