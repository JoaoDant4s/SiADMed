# RF05 - Cadastro de Usuários com Níveis de Acesso

**COMO** administrador do sistema  
**QUERO** cadastrar usuários com diferentes níveis de acesso  
**PARA** garantir o controle de permissões e a segurança do sistema.

## Dados e Validações

### Tipos de Usuários e Dados Necessários

#### **Paciente**:
- Nome completo (Obrigatório).
- Data de nascimento (Obrigatório).
- CPF (Validação: formato válido e único).
- E-mail e telefone (Obrigatórios).
- Endereço completo (Obrigatório).

#### **Médico**:
- Nome completo (Obrigatório).
- CRM (Validação: formato válido com base no estado de registro).
- Especialidade médica (Obrigatório).
- CPF, e-mail e telefone (Obrigatórios).

#### **Administrador**:
- Nome completo (Obrigatório).
- CPF, e-mail e telefone (Obrigatórios).

### Níveis de Acesso:
- **Paciente**: Acesso apenas a seus próprios dados.
- **Médico**: Acesso aos pacientes sob sua responsabilidade.
- **Administrador**: Acesso total ao sistema.

## Critérios de Aceitação

### Cadastro bem-sucedido:
- Quando todos os campos obrigatórios forem preenchidos corretamente, o usuário deve ser cadastrado.

### Validação de CPF:
- Se o CPF já estiver em uso, o sistema deve exibir uma mensagem de erro:  
  "O CPF informado já está cadastrado no sistema."

### Permissões de Acesso:
- Cada usuário deve ter acesso limitado de acordo com seu nível de permissão.

  ![image](https://github.com/user-attachments/assets/e62bc2fe-5e10-4ef4-bd28-25d4126d18e6)

