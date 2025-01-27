# RF02 - Processamento e Análise de Dados Médicos com IA

**COMO** usuário do sistema
**QUERO** que os dados médicos sejam processados e analisados utilizando IA
**PARA** gerar uma lista de diagnósticos prováveis com probabilidade associada.

## Fontes de Dados:
  - Sintomas descritos (campo texto).
  - Resultados de exames laboratoriais (formatos suportados: PDF, JPG, PNG, texto).
## Condições:
  - A IA só será acionada após o preenchimento de todos os campos médicos exigidos no RF01.
## Critérios de Aceitação
  - Diagnósticos gerados pela IA:
    - Quando acionada, a IA deve retornar uma lista de diagnósticos prováveis com uma probabilidade associada (ex.: diagnóstico A - 80%).
  - Mensagens de erro:
    - Caso algum campo obrigatório esteja ausente, o sistema deve exibir uma mensagem de erro: "Preencha todos os campos obrigatórios antes de processar os dados."
## Formatos de exame inválidos:
  - Se algum arquivo de exame tiver um formato não suportado, o sistema deve exibir uma mensagem de erro: "Formato de exame inválido. Por favor, envie arquivos nos formatos PDF, JPG, PNG ou texto."
