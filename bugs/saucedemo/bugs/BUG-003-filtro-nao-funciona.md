# BUG-003 - Filtro de ordenação não funciona

## Informações gerais

| Campo | Valor |
|-------|-------|
| **ID** | BUG-003 |
| **Título** | Filtro de ordenação não aplica a opção selecionada |
| **Gravidade** | Máxima |
| **Status** | Novo |
| **Usuário testado** | problem_user |
| **Data** | Maio/2026 |

## Pré-condição

Usuário está logado com credenciais válidas na página de produtos

**Usuário:** problem_user
**Senha:** secret_sauce

## Passos para reproduzir

1. Na página de produtos, clicar no filtro de ordenação
2. Selecionar a opção "Name (Z to A)"
3. Observar a ordem dos produtos após a seleção

## Resultado esperado

Os produtos devem ser reordenados conforme a opção selecionada (Z → A)

## Resultado real

A ordem dos produtos permanece como estava (A → Z), independente da opção escolhida

## Observações

- Diferente do BUG-001 (que aplicava a ordem errada), este bug não aplica NENHUMA ordem
- O problema ocorre com qualquer opção de filtro selecionada
- Usuário não consegue organizar os produtos de nenhuma forma
