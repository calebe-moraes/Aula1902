# Documento de Requisitos do Sistema

## 1. Introdução
Este documento apresenta os requisitos do sistema desenvolvido na disciplina, com o objetivo de organizar as funcionalidades, regras e características do software.

---

# 2. Requisitos Funcionais (RF)

## RF01 – Cadastro de Usuários
O sistema deve permitir o cadastro de novos usuários com nome, email e senha.

Critério de Aceitação:
- O usuário deve conseguir se cadastrar com dados válidos.
- O sistema deve salvar as informações no banco de dados.

Verificação:
- Teste de cadastro com dados corretos e incorretos.

---

## RF02 – Login no Sistema
O sistema deve permitir que usuários cadastrados realizem login.

Critério de Aceitação:
- O usuário deve acessar o sistema com email e senha válidos.

Verificação:
- Testar login com credenciais válidas e inválidas.

---

## RF03 – Visualização de Dados no Dashboard
O sistema deve exibir informações principais em um dashboard.

Critério de Aceitação:
- O dashboard deve carregar os dados corretamente após o login.

Verificação:
- Conferir se os dados aparecem corretamente na interface.

---

## RF04 – Registro de Informações
O sistema deve permitir o registro de informações (ex: atendimentos, vendas ou atividades).

Critério de Aceitação:
- Os dados devem ser armazenados e exibidos posteriormente.

Verificação:
- Inserir dados e verificar se aparecem na listagem.

---

# 3. Requisitos Não Funcionais (RNF)

## RNF01 – Desempenho
O sistema deve responder às ações do usuário em até 3 segundos.

Métrica:
- Tempo de resposta menor ou igual a 3 segundos.

---

## RNF02 – Usabilidade
A interface deve ser simples e intuitiva para usuários iniciantes.

Métrica:
- Usuário deve conseguir utilizar as funções principais sem treinamento técnico.

---

# 4. Regras de Negócio (RN)

## RN01 – Acesso Restrito
Apenas usuários cadastrados podem acessar o sistema.

---

## RN02 – Validação de Dados
O sistema não deve permitir cadastro com campos obrigatórios vazios.
