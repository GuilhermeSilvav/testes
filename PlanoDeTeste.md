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