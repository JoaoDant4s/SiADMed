# RF01 - Inserir Dados Médicos
**COMO** médico no sistema

**QUERO** inserir dados médicos completos de um paciente a fim de cadastrar uma consulta

**PARA** possibilitar o processamento e análise de informações clínicas.


## Dados Necessários:
  - Nome completo do paciente
    - Tipo: String
    - Validação: Não vazio.
  - Data de nascimento do paciente
    - Tipo: Data
    - Validação: Formato válido de data.
  - Sintomas descritos
    - Tipo: Texto
    - Validação: Não vazio.
  - Exames laboratoriais
    - Tipo: Arquivo ou Link
    - Validação: Arquivo em formato PDF, JPG, PNG ou link válido.
  - Descrição do caso
    - Tipo: Texto longo
    - Validação: Não vazio.
## Critérios de Aceitação
  - Todos os campos obrigatórios devem ser preenchidos antes de salvar.
  - Exibir mensagem de erro caso algum campo obrigatório esteja vazio: **"Preencha todos os campos obrigatórios antes de salvar os dados médicos."**
