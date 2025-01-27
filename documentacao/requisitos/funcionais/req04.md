# RF04 - Integração com Sistemas de EHR

**COMO** administrador do sistema  
**QUERO** integrar o sistema com prontuários eletrônicos (EHR)  
**PARA** acessar o histórico médico e informações relevantes do paciente.

## Dados e Funcionalidades

### Dados Disponíveis via Integração:
- Histórico médico do paciente (últimos 10 registros, no mínimo).
- Exames laboratoriais anteriores.
- Medicamentos prescritos nos últimos 12 meses.

### Condições:
- A integração deve respeitar normas de segurança, como LGPD e HIPAA.

## Critérios de Aceitação

### Segurança:
- A integração deve criptografar todos os dados sensíveis durante a transmissão.

### Disponibilidade de Dados:
- O sistema deve exibir os dados médicos integrados de forma clara e estruturada para o médico responsável.

### Mensagens de Erro:
- Caso a integração falhe, o sistema deve exibir uma mensagem de erro:  
  "Falha ao acessar os dados do EHR. Por favor, tente novamente mais tarde."
