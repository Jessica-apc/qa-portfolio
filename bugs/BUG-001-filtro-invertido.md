# BUG-001 - Filtro A a Z invertido

## Informações gerais

| Campo | Valor |
|-------|-------|
| **ID** | BUG-001 |
| **Título** | Filtro A a Z mostra ordem invertida |
| **Gravidade** | Média |
| **Status** | Novo |
| **Usuário testado** | standard_user |
| **Data** | Maio/2026 |

## Pré-condição

Usuário está logado com credenciais válidas na página de produtos

**Usuário:** standard_user
**Senha:** secret_sauce

## Passos para reproduzir

1. Acessar página de produtos
2. Clicar no filtro de ordenação
3. Selecionar a opção "Name (A to Z)"
4. Observar a ordem dos produtos exibidos

## Resultado esperado

Os produtos devem aparecer em ordem alfabética crescente (A → Z)

## Resultado real

Os produtos aparecem em ordem alfabética decrescente (Z → A)

## Observações

O bug ocorre consistentemente todas as vezes que o filtro é aplicado.
