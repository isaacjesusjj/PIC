# PIC

# Divisão dos Módulos de Desenvolvimento

## 1. Desenvolvedor — Pacientes e Cadastros

**Responsável: Adonis**

- Cadastro de pacientes
- Dados pessoais
- Dados de contato
- Endereço
- Responsáveis, quando aplicável
- Cadastro dos psicólogos/profissionais
- Dados profissionais
- Busca e filtros de pacientes
- Histórico cadastral
- Ativação/inativação de pacientes
- Relacionamento paciente ↔ profissional

## 2. Desenvolvedor — Prontuário e Atendimento Clínico

**Responsável:**

- Prontuário eletrônico
- Registro de sessões
- Evolução clínica
- Anotações do psicólogo
- Histórico de atendimentos
- Queixas/demandas
- Plano terapêutico
- Documentos clínicos
- Anexos
- Modelos de documentos
- Relatórios clínicos
- Encerramento de atendimento
- Histórico/versões das informações clínicas

## 3. Desenvolvedor — Agenda e Gestão

Esse desenvolvedor trabalha em um sistema de agenda.

**Responsável:**

- Agenda do psicólogo
- Marcação de consultas
- Reagendamento
- Cancelamento
- Confirmação
- Faltas
- Encaixes
- Horários disponíveis
- Duração da sessão
- Recorrência
- Calendário diário/semanal/mensal
- Lembretes
- Eventuais integrações com calendário

## 4. Desenvolvedor — Autenticação, Segurança e Infraestrutura

Desenvolvedor mais voltado para backend/infraestrutura, porque essa frente será transversal ao sistema.

**Responsável: Isaac**

- Login
- Logout
- Recuperação de senha
- Controle de sessão
- JWT/OAuth, se adotado
- Perfis de usuário
- Permissões
- Psicólogo
- Administrador
- Recepção, se houver
- Controle de acesso
- Auditoria
- Logs
- Criptografia
- Banco de dados/infraestrutura
- Backup
- Notificações
- E-mail
- Arquivos
- Configurações gerais
- CI/CD
- Ambiente de desenvolvimento/homologação/produção
