# CT-002 - Validar imagens dos produtos

## Informações gerais

| Campo | Valor |
|-------|-------|
| **ID** | CT-002 |
| **Título** | Validar correspondência entre imagem e descrição dos produtos |
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

## Passos

1. Acessar página inicial de produtos após o login
2. Para cada produto exibido, comparar a imagem com o nome/descrição do produto

## Resultado esperado

Cada produto deve exibir uma imagem condizente com sua descrição

## Resultado real (após execução)

Todos os produtos exibem a mesma imagem (boneco/silueta)

## Conclusão

❌ **FALHOU** - Bug reportado como BUG-002
