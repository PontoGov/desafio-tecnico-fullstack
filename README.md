# 💼 Desafio Técnico - Ticket Manager App

Bem-vindo ao desafio técnico! Seu objetivo é desenvolver uma aplicação **full-stack** para gerenciar **chamados de suporte técnico**, com tarefas vinculadas a cada chamado. O sistema deve respeitar regras de negócio baseadas em **fluxo de status** para garantir o controle correto do processo.

---

## 🎯 Objetivo

Criar uma aplicação web funcional (frontend + backend) onde:

- Um **chamado** pode conter várias **tarefas**
- Ambos possuem status que devem seguir um fluxo definido
- O sistema impede ações que violem regras de negócio

---

## 🧱 Funcionalidades

### 📁 Chamado (Ticket)
- Criar chamado
- Listar chamados
- Visualizar detalhes de um chamado (com tarefas)
- Atualizar status do chamado
- Remover chamado (apenas se **não tiver tarefas vinculadas**)

---

### 🗂️ Tarefa
- Adicionar tarefa a um chamado
- Editar tarefa
- Atualizar status da tarefa
- Remover tarefa

---

### 🧠 Regras de Negócio

- As informações do chamado são: Título, Descrição, Status(Aberto, Em Andamento ou Finalizado).
- As informações da tarefa são: Descrição, Nome do Responsável, Status(Pendente, Fazendo ou Concluída).
- Um chamado pode ter várias tarefas.
- Um chamado **só pode ser finalizado** se **todas as tarefas estiverem concluídas**.
- Um chamado **não pode ser excluído** se possuir tarefas vinculadas.

---

## 🧰 Tecnologias Esperadas

### Backend
- PHP (Podendo utilizar auxiliares como frameworks).
- Banco de dados PostgreSQL.

### Frontend
- HTML.
- CSS.
- JQuery.
- JavaScript.

---

## Diferencial (Opcional)

- Utilização de Docker para ambientação da aplicação.
- Utilização de Kendo UI com JQuery.

---
## 📝 Entrega

- Crie um repositório público ou privado (dê acesso aos avaliadores)
- Inclua um `README.md` com:
  - Instruções para rodar o projeto
  - Comentários ou considerações pessoais

---

## 📬 Dúvidas?

Fique à vontade para entrar em contato com o time caso tenha qualquer dúvida sobre o desafio. Boa sorte!

