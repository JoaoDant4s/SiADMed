# RF06 - Cadastro de Farmácias

**COMO** administrador do sistema  
**QUERO** cadastrar farmácias no sistema  
**PARA** fornecer informações sobre medicamentos aos pacientes e médicos.

## Dados e Validações

### Campos Obrigatórios no Cadastro de Farmácias:
- Nome da farmácia.
- CNPJ (Validação: formato válido e único).
- Endereço completo.
- Telefone e e-mail.
- **Lista de medicamentos disponíveis**:
  - Nome do medicamento.
  - Fabricante.
  - Preço.

## Critérios de Aceitação

### Cadastro bem-sucedido:
- O sistema deve salvar o cadastro da farmácia e exibir uma mensagem de confirmação:  
  "Farmácia cadastrada com sucesso."

### Validação de CNPJ:
- Caso o CNPJ já esteja cadastrado, o sistema deve exibir uma mensagem de erro:  
  "O CNPJ informado já está em uso."

### Medicamentos listados:
- A farmácia recém-cadastrada deve aparecer na listagem com todos os medicamentos disponíveis.
