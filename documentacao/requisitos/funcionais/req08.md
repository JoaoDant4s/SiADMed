# RF08 - Agendamento de Consultas Médicas

**COMO** paciente ou médico  
**QUERO** agendar consultas no sistema  
**PARA** organizar o atendimento médico.

## Dados e Funcionalidades

### Campos Obrigatórios para Agendamento:
- Nome do paciente.
- Médico responsável.
- Data e horário da consulta.
- Motivo da consulta (opcional).

### Funcionalidades:
- Permitir que o paciente agende consultas com médicos disponíveis.
- Permitir que o médico visualize e gerencie sua agenda de consultas.

## Critérios de Aceitação

### Agendamento bem-sucedido:
- Quando todos os campos obrigatórios forem preenchidos corretamente, o sistema deve salvar o agendamento e exibir uma mensagem de confirmação:  
  "Consulta agendada com sucesso."

### Conflito de horário:
- Caso o médico já tenha uma consulta agendada no mesmo horário, o sistema deve exibir uma mensagem de erro:  
  "Este horário já está ocupado. Por favor, selecione outro."

### Visualização da agenda:
- O médico deve poder visualizar a agenda de consultas de forma clara e organizada por data e horário.
