# Plano de testes da situação de aprendizagem 4º Semestre
Rodrigo Ferreira
Guilherme Velho
Jonatas Gabreil Santos Campos
Fillipe Lima

## 1. Teste de Cadastro de Equipamentos
Objetivo: Garantir que o sistema permita o cadastro correto de diferentes tipos de EPIs.

Casos de Teste:

CT01: Cadastrar um EPI válido.

Passos: Acessar a tela de cadastro de EPIs, preencher os campos obrigatórios e clicar em "Salvar".
Resultado Esperado: EPI cadastrado com sucesso e listado na tela de visualização de EPIs.
CT02: Tentar cadastrar um EPI sem preencher campos obrigatórios.

Passos: Acessar a tela de cadastro, deixar campos obrigatórios em branco e clicar em "Salvar".
Resultado Esperado: Mensagem de erro informando que campos obrigatórios devem ser preenchidos.
CT03: Cadastrar um EPI com dados inválidos (ex: nome com caracteres especiais).

Passos: Preencher os campos com dados inválidos e clicar em "Salvar".
Resultado Esperado: Mensagem de erro informando que os dados são inválidos.


## 5. Teste de Relatórios de Empréstimos
Objetivo: Garantir que o sistema gere relatórios precisos sobre os empréstimos de EPIs.

Casos de Teste:

CT01: Gerar relatório de todos os empréstimos.

Passos: Acessar a tela de relatórios e solicitar um relatório completo.
Resultado Esperado: Relatório gerado com todos os empréstimos registrados.
CT02: Gerar relatório de empréstimos por colaborador.

Passos: Selecionar um colaborador específico e gerar o relatório.
Resultado Esperado: Relatório gerado com os empréstimos desse colaborador.
CT03: Tentar gerar relatório sem critérios de filtro.

Passos: Solicitar relatório sem escolher filtros.
Resultado Esperado: Mensagem de erro informando que filtros devem ser selecionados.
