# RF07 - Consulta e Atualização de Medicamentos por Farmácias

**COMO** farmácia cadastrada no sistema  
**QUERO** consultar e atualizar a lista de medicamentos disponíveis  
**PARA** manter as informações atualizadas para médicos e pacientes.

## Dados e Funcionalidades

### Funcionalidades Disponíveis:
- Consultar a lista de medicamentos cadastrados.
- Adicionar novos medicamentos à lista.
- Atualizar preço, fabricante ou disponibilidade de medicamentos já cadastrados.
- Remover medicamentos que não estejam mais disponíveis.

## Critérios de Aceitação

### Consulta bem-sucedida:
- O sistema deve exibir uma lista com todos os medicamentos cadastrados pela farmácia.

### Atualização de medicamento:
- Ao atualizar as informações de um medicamento, o sistema deve salvar as alterações e exibir uma mensagem de confirmação:  
  "Medicamento atualizado com sucesso."

### Remoção de medicamento:
- O sistema deve permitir a remoção de medicamentos e exibir uma mensagem de confirmação:  
  "Medicamento removido com sucesso."

### Validação de campos obrigatórios:
- Caso algum campo obrigatório (nome, fabricante ou preço) esteja vazio ao tentar adicionar ou atualizar um medicamento, o sistema deve exibir uma mensagem de erro:  
  "Preencha todos os campos obrigatórios para continuar."
