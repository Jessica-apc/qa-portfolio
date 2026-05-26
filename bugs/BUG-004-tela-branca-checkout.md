# BUG-004 - Tela branca e trava ao preencher informações de checkout

## Informações gerais

| Campo | Valor |
|-------|-------|
| **ID** | BUG-004 |
| **Título** | Tela branca e trava ao preencher informações de checkout |
| **Gravidade** | Máxima |
| **Status** | Novo |
| **Usuário testado** | standard_user |
| **Data** | Maio/2026 |

## Pré-condição

- Usuário está logado com `standard_user` / `secret_sauce`
- Página de produtos está acessível

## Passos para reproduzir

1. Na página de produtos, adicionar o produto "Sauce Labs Backpack" ao carrinho
2. Clicar no ícone do carrinho (canto superior direito)
3. Clicar no botão "Checkout"
4. Na página de informações, tentar preencher o campo "First Name"
5. Ao digitar qualquer caractere, observar o comportamento

## Resultado esperado

O campo aceita a digitação normalmente e a página permanece estável. O usuário consegue preencher todos os campos e finalizar a compra.

## Resultado real

Ao digitar qualquer caractere no campo "First Name", a tela fica completamente branca e o site trava.

## Gravidade: Máxima

**Justificativa:**
- Impede o usuário de completar a compra
- O site trava, exigindo recarregar a página
- Perda de dados (tudo que foi feito antes se perde)
- Impacta diretamente a conversão de vendas

## Observações adicionais

- Bug encontrado usando `standard_user`
- Acontece consistentemente todas as vezes
- Pendente testar:
  - Outros produtos
  - Outros usuários (problem_user)
  - Outros campos (Last Name, Postal Code)
  - Outros navegadores

## Status atual

**Novo** - Aguardando análise e atribuição para desenvolvedor
