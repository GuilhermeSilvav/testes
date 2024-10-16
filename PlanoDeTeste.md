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

## 2. Teste de Cadastro de Colaboradores
   Objetivo: Verificar se o sistema permite o cadastro correto de colaboradores.

Casos de Teste:

CT01: Cadastrar um colaborador válido.

Passos: Acessar a tela de cadastro de colaboradores, preencher os campos obrigatórios e clicar em "Salvar".
Resultado Esperado: Colaborador cadastrado com sucesso e listado na tela de visualização de colaboradores.
CT02: Tentar cadastrar um colaborador sem CPF.

Passos: Acessar a tela de cadastro, deixar o campo CPF em branco e clicar em "Salvar".
Resultado Esperado: Mensagem de erro informando que o CPF é obrigatório.
CT03: Cadastrar um colaborador com CPF inválido.

Passos: Preencher o CPF com dados inválidos e clicar em "Salvar".
Resultado Esperado: Mensagem de erro informando que o CPF é inválido.


## 4. Teste de Devolução de EPIs
   Objetivo: Verificar se o sistema permite a devolução correta de EPIs.

Casos de Teste:

CT01: Devolver um EPI que foi emprestado.

Passos: Acessar a tela de devolução, selecionar um EPI emprestado e clicar em "Devolver".
Resultado Esperado: Devolução registrada com sucesso e EPI disponível novamente para empréstimo.
CT02: Tentar devolver um EPI que não foi emprestado.

Passos: Tentar devolver um EPI que não está no histórico de empréstimos.
Resultado Esperado: Mensagem de erro informando que o EPI não está emprestado.
CT03: Devolver um EPI sem preencher campos obrigatórios.

Passos: Tentar devolver sem selecionar o EPI.
Resultado Esperado: Mensagem de erro informando que um EPI deve ser selecionado.


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

