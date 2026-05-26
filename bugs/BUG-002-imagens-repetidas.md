# BUG-002 - Imagens dos produtos repetidas

## Informações gerais

| Campo | Valor |
|-------|-------|
| **ID** | BUG-002 |
| **Título** | Todos os produtos exibem a mesma imagem |
| **Gravidade** | Máxima |
| **Status** | Novo |
| **Usuário testado** | problem_user |
| **Data** | Maio/2026 |

## Pré-condição

Usuário está logado com credenciais válidas na página de produtos

**Usuário:** problem_user
**Senha:** secret_sauce

## Passos para reproduzir

1. Fazer login com usuário problem_user
2. Acessar página inicial de produtos
3. Visualizar a lista de produtos

## Resultado esperado

Cada produto deve exibir sua respectiva imagem (mochila, lanterna, camiseta, etc.)

## Resultado real

Todos os produtos exibem a mesma imagem (um boneco/silueta sem sentido)

## Observações

- O problema afeta a experiência do usuário
- Cliente não consegue identificar o produto pela foto
- Gravidade máxima pois impacta diretamente a usabilidade
