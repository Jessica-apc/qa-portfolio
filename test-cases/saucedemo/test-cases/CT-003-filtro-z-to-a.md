# CT-003 - Validar ordenação Z to A

## Informações gerais

| Campo | Valor |
|-------|-------|
| **ID** | CT-003 |
| **Título** | Validar ordenação de produtos - Filtro Z to A |
| **Status** | Falhou |
| **Usuário testado** | problem_user |
| **Data da execução** | Maio/2026 |

## Pré-condição

Usuário está logado com credenciais válidas na página de produtos

**Usuário:** problem_user
**Senha:** secret_sauce

## Dados de teste

| Campo | Valor |
|-------|-------|
| Usuário | problem_user |
| Senha | secret_sauce |
| Filtro | Name (Z to A) |

## Passos

1. Acessar página de produtos
2. Clicar no filtro de ordenação
3. Selecionar a opção "Name (Z to A)"
4. Observar a ordem dos produtos exibidos

## Resultado esperado

Os produtos devem aparecer em ordem alfabética decrescente (Z → A)

## Resultado real (após execução)

A ordem dos produtos permanece como estava (A → Z)

## Conclusão

❌ **FALHOU** - Bug reportado como BUG-003
