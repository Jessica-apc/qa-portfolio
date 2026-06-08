# CT-004 - Campo "Nome" vazio

## Informações gerais

| Campo | Valor |
|-------|-------|
| **ID** | CT-004 |
| **Título** | Tentativa de cadastro com campo "Nome" vazio |
| **Status** | Pendente |

## Pré-condição

Página de cadastro está carregada. Todos os campos obrigatórios estão preenchidos corretamente, EXCETO o campo "Nome".

## Dados de teste

| Campo | Valor |
|-------|-------|
| E-mail | teste@email.com |
| Nome | (vazio) |
| Senha | Senha123 |
| Confirmação de senha | Senha123 |
| Conta com saldo | Sim |

## Passos

1. Clicar no botão "Cadastrar"

## Resultado esperado

Página exibe mensagem de erro "Nome não pode ser vazio"
