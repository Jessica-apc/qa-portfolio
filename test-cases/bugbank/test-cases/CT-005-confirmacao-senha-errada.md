# CT-005 - Confirmação de senha incorreta

## Informações gerais

| Campo | Valor |
|-------|-------|
| **ID** | CT-005 |
| **Título** | Preencher campo "Confirmação de senha" de forma incorreta |
| **Status** | Pendente |

## Pré-condição

Página de cadastro está carregada. Todos os campos estão preenchidos corretamente, EXCETO a confirmação de senha.

## Dados de teste

| Campo | Valor |
|-------|-------|
| E-mail | teste@email.com |
| Nome | Jessica |
| Senha | Senha123 |
| Confirmação de senha | SenhaErrada456 |
| Conta com saldo | Sim |

## Passos

1. Clicar no botão "Cadastrar"

## Resultado esperado

Página exibe mensagem de erro informando que os campos "Senha" e "Confirmação de senha" devem ser iguais
