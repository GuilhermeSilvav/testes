# Plano de Testes da Situação de Aprendizagem - 4º Semestre
Fillipe Lima

2. Teste de Cadastro de Colaboradores (FILLIPE)
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
