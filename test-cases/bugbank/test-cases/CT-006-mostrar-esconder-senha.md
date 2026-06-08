# CT-006 - Mostrar/esconder senha (ícone olho)

## Informações gerais

| Campo | Valor |
|-------|-------|
| **ID** | CT-006 |
| **Título** | Validar funcionalidade de mostrar/esconder senha (ícone olho) |
| **Status** | Pendente |

## Pré-condição

Tela de login do BugBank está carregada

## Dados de teste

| Campo | Valor |
|-------|-------|
| Senha | MinhaSenha123 |

## Passos

1. Localizar o campo "Senha"
2. Preencher o campo "Senha" com `MinhaSenha123`
3. Verificar que os caracteres aparecem como pontos/bullets (•••••••••)
4. Clicar no ícone de olho
5. Observar o campo "Senha"

## Resultado esperado

- Ao clicar no ícone de olho, a senha fica visível (`MinhaSenha123`)
- Ao clicar novamente, a senha volta a ficar oculta (•••••••••)
