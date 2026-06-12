# Atividade 9 - Integração Contínua, Branches e Pull Requests

---

## 1. O que é Integração Contínua?

A **Integração Contínua (Continuous Integration - CI)** é uma prática de desenvolvimento de software em que os programadores enviam frequentemente suas alterações de código para um repositório compartilhado. A cada envio, testes automáticos e verificações são executados para garantir que as novas modificações não causem erros no sistema.

O principal objetivo da Integração Contínua é identificar e corrigir problemas rapidamente, mantendo o software sempre funcional e atualizado.

---

## 2. Qual é o papel das branches nesse processo?

As **branches** (ramificações) permitem que os desenvolvedores trabalhem em novas funcionalidades, correções ou melhorias de forma isolada, sem alterar diretamente a versão principal do projeto.

No processo de Integração Contínua:

* Cada desenvolvedor cria uma branch para sua tarefa.
* As alterações são desenvolvidas e testadas nessa branch.
* Quando o trabalho é concluído, a branch pode ser integrada à principal (geralmente chamada de `main` ou `master`).

Dessa forma, as branches ajudam a reduzir conflitos e facilitam a organização do desenvolvimento.

---

## 3. Por que o Pull Request é importante?

O **Pull Request (PR)** é uma solicitação para que as alterações realizadas em uma branch sejam analisadas e incorporadas a outra branch, normalmente a principal.

Ele é importante porque:

* Permite a revisão do código por outros membros da equipe.
* Ajuda a identificar erros, problemas de lógica e oportunidades de melhoria antes da integração.
* Garante maior qualidade e padronização do código.
* Possibilita a execução de testes automáticos antes da aprovação.

Assim, o Pull Request funciona como uma etapa de controle de qualidade, garantindo que apenas alterações validadas sejam adicionadas ao projeto principal.