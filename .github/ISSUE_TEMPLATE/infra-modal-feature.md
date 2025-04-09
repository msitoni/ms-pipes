---
name: "[FEATURE] Tela Modal - Terraform AWS"
about: Criar uma tela modal com uma escolha entre ECS ou SQS via Terraform
title: "[FEATURE] Tela modal para criação de estrutura Terraform"
labels: enhancement, terraform, frontend
assignees: ''

---

### 🎯 Objetivo da funcionalidade

Apresentar uma **tela modal** que permita ao usuário **escolher apenas uma** das opções abaixo:

- ( ) AWS ECS  
- ( ) AWS SQS

---

### 📋 Descrição técnica

A escolha do usuário deve disparar a criação de uma estrutura base em Terraform:

- **ECS**: criar cluster, task, service, etc.
- **SQS**: criar fila padrão, DLQ, política.

A modal deve usar elementos como `radio button` ou `dropdown`, garantindo escolha única.

---

### ✅ Critérios de aceitação

- [ ] Modal exibida corretamente
- [ ] Apenas uma opção pode ser escolhida
- [ ] Código Terraform gerado e validado
- [ ] Documentação atualizada

---

### 📎 Links úteis

- [Terraform AWS ECS](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ecs_service)
- [Terraform AWS SQS](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/sqs_queue)
