# GereciamentoDeClinica
 GereciamentoDeClinica
# 🏥 Sistema de Gerenciamento de Clínica Médica

Este é um projeto para praticar os conceitos de **Engenharia de Software** com **Java + Spring Boot**, focado na construção de um sistema completo de agendamento de consultas médicas.

---

## 🚀 Stack Utilizada

- **Backend:** Java 17, Spring Boot
- **Banco de Dados:** PostgreSQL
- **Segurança:** Spring Security + JWT
- **ORM:** Spring Data JPA
- **Build Tool:** Maven
- **Versionamento de banco:** Flyway (em etapas futuras)
- **Gerenciamento de dependências:** Maven
- **IDE recomendada:** IntelliJ IDEA

---

## 🗂️ Etapas do Projeto

### ✅ Semana 1 – Planejamento e Setup

- [x] Definir escopo e funcionalidades
- [x] Escolher tecnologias
- [x] Criar repositório GitHub
- [ ] Criar projeto base com Spring Initializr
- [ ] Configurar banco de dados PostgreSQL
- [ ] Criar estrutura base de pacotes
- [ ] Criar entidades iniciais (`Usuario`, `Medico`, `Consulta`)
- [ ] Documentar modelos com UML (opcional)
- [ ] Testar conexão com o banco de dados

---

### ✅ Semana 2 – Autenticação e Cadastro

- [ ] Implementar cadastro e login de usuários (JWT)
- [ ] Separar perfis de acesso (Paciente, Médico, Admin)
- [ ] Proteger rotas com Spring Security
- [ ] Criar estrutura de DTOs para entrada e saída
- [ ] Criar testes básicos de autenticação

---

### ✅ Semana 3 – Funcionalidade de Agendamento

- [ ] CRUD de médicos e horários disponíveis
- [ ] Paciente pode ver médicos e horários
- [ ] Criar agendamento de consulta
- [ ] Validar conflitos de horário
- [ ] Listar consultas do paciente e do médico

---

### ✅ Semana 4 – Painéis e Lógicas de Negócio

- [ ] Painel do paciente (histórico, próximas consultas)
- [ ] Painel do médico (consultas agendadas)
- [ ] Atualização de status da consulta (realizada, cancelada)

---

### ✅ Semana 5 – Administração do Sistema

- [ ] Tela/Admin API para gerenciar médicos, pacientes e usuários
- [ ] CRUD completo de médicos
- [ ] Gerenciamento dos horários disponíveis

---

### ✅ Semana 6 – Testes e Deploy

- [ ] Testes automatizados (unitários e de integração)
- [ ] Deploy no Railway, Render ou outro serviço
- [ ] Documentação final da API (Swagger ou Postman)
- [ ] README com instruções de uso

---

## 🧠 Conceitos de Engenharia Aplicados

- Separação de responsabilidades (MVC)
- Camadas: Controller, Service, Repository
- Versionamento de banco (Flyway)
- Segurança (JWT e roles)
- Boas práticas com DTOs e validações
- Testes com JUnit

---

## 📌 Requisitos Funcionais

### 👤 Usuário (Paciente)
- Cadastro e login
- Agendamento de consultas
- Cancelamento de consulta
- Visualização de consultas futuras e passadas

### 🩺 Médico
- Login
- Ver suas consultas
- Marcar consultas como realizadas
- Definir disponibilidade

### ⚙️ Admin
- Cadastro de médicos
- Gestão de usuários e consultas
- Acesso a estatísticas

---

## 💡 Extras (futuros)

- Notificações por e-mail
- Dashboard com gráficos (consultas por especialidade, mês, etc.)
- Deploy com Docker
- Integração com calendário (Google Calendar)

---

## 📌 Como rodar o projeto (futuramente)

```bash
# Clonar o projeto
git clone https://github.com/seu-usuario/nome-do-repositorio.git

# Abrir no IntelliJ ou VSCode

# Rodar com Maven
./mvnw spring-boot:run
