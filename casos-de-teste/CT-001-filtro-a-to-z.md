# CT-001 - Validar ordenação A a Z

## Informações gerais

| Campo | Valor |
|-------|-------|
| **ID** | CT-001 |
| **Título** | Validar ordenação de produtos - Filtro A a Z |
| **Status** | Falhou |
| **Usuário testado** | standard_user |
| **Data da execução** | Maio/2026 |

## Pré-condição

Usuário está logado com credenciais válidas na página de produtos

**Usuário:** standard_user
**Senha:** secret_sauce

## Dados de teste

| Campo | Valor |
|-------|-------|
| Usuário | standard_user |
| Senha | secret_sauce |
| Filtro | Name (A to Z) |

## Passos

1. Acessar página de produtos
2. Clicar no filtro de ordenação
3. Selecionar a opção "Name (A to Z)"
4. Observar a ordem dos produtos exibidos

## Resultado esperado

Os produtos devem aparecer em ordem alfabética crescente (A → Z)

## Resultado real (após execução)

Os produtos apareceram em ordem alfabética decrescente (Z → A)

## Conclusão

❌ **FALHOU** - Bug reportado como BUG-001
