# Barbearia Style

## Sobre o projeto
O Barbearia Style é um projeto acadêmico desenvolvido para a disciplina de Ergonomias de Sistemas Computacionais e IHC. O objetivo é criar um site para uma barbearia fictícia, apresentando seus serviços, preços e uma página demonstrativa de agendamento.

## Cenário
Barbearia.

## Integrantes e papéis

| Integrante | Papel técnico | Papel de gestão TSP |
|---|---|---|
| Elielson | Líder de Projeto | Team Leader |
| Elidiel | Desenvolvedor | Planning Manager |
| Alan | Web Designer / Frontend | Support Manager |
| Joaquim | Analista de Qualidade e Teste | Quality Manager |

## Caminho escolhido
Caminho A – Protótipo de páginas em HTML e CSS.

## Funcionalidades
- Página inicial da barbearia.
- Apresentação dos serviços e preços.
- Página demonstrativa de agendamento.
- Menu de navegação entre as páginas.

## Tecnologias utilizadas
- HTML
- CSS
- GitHub
- GitHub Projects (Kanban)

## Organização do projeto
As tarefas são organizadas por meio de um quadro Kanban no GitHub Projects, utilizando as etapas A fazer, Fazendo, Em revisão e Feito.

## Planejamento e PSP
- Planilha de planejamento: -
- PSP do Integrante 1: - 
- PSP do Integrante 2: -https://github.com/bruhqxx/barbearia-style/blob/dd0021e6fe071b298710ab09aa4fd4143a036721/style.css
- PSP do Integrante 3: -
- PSP do Integrante 4: -

## Registros e qualidade
- Registro das reuniões: -
- Revisões e testes: -
- Retrospectiva: -




---

## Quality Manager — Controle de Qualidade

**Responsável:** Joaquim  
**Data:** 17/11/2026

### 1. Revisão de Código

- **Arquivo revisado:** `servicos.html`
- **Responsável pela revisão:** Joaquim
- **Resultado:** Aprovado nos testes de navegação.
- **Observação:** Os links de Início, Serviços e Agendamento funcionaram corretamente. Foi sugerida a padronização dos nomes dos serviços.

### 2. Testes Realizados

| Teste | Resultado esperado | Resultado obtido | Status |
|---|---|---|---|
| Telefone inválido | Bloquear letras | Aceitou abcdef | Reprovado |
| Telefone após correção | Bloquear letras | Bloqueou abcdef | Aprovado |
| Navegação | Abrir páginas corretas | Links funcionaram | Aprovado |

### 3. Bug Encontrado e Corrigido

- **Problema:** Campo de telefone aceitava letras.
- **Arquivo:** `agendamento.html`
- **Causa:** Falta de validação do formato do telefone.
- **Correção:** Adicionado o atributo `pattern` ao campo de telefone.
- **Resultado:** O formulário passou a bloquear telefones inválidos.
- **Status:** Corrigido e testado.

### 4. Evidências

- [Código corrigido](https://github.com/bruhqxx/barbearia-style/blob/main/agendamento.html)
- [Código revisado](https://github.com/bruhqxx/barbearia-style/blob/main/servicos.html)
- [Registro dos testes](https://github.com/bruhqxx/barbearia-style/issues/8)

Os resultados também foram registrados na planilha Quality Manager da equipe.
