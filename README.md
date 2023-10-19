# Projeto Final Estrutura de Dados 2

# Rede Social - Relatório

Este repositório contém o código para uma simples página da web que simula uma rede social, permitindo aos usuários buscar as conexões de outros usuários. Aqui está um resumo do que o código faz:

## Estrutura da Página

A página da web é projetada com duas áreas principais:

1. **Barra Lateral (Sidebar)**
   - Largura: 35% da tela
   - Exibe uma lista de 30 nomes de usuários brasileiros aleatórios.

2. **Conteúdo Principal (Content)**
   - Largura: 400px
   - Inclui um campo de busca, onde os usuários podem inserir um nome de usuário.
   - Exibe os resultados da busca na área de resultados.

## Estilos CSS

A página tem um estilo atraente com a seguinte customização:

- Fundo: Uma imagem de plano de fundo que cobre toda a tela e se mantém fixa enquanto você rola.
- Cores e tamanhos definidos para uma aparência esteticamente agradável.
- Barras de rolagem personalizadas.

## Dados de Conexão

Os dados de conexão entre os usuários são representados por um objeto JavaScript chamado `graph`. Ele mapeia os nomes de usuários para suas conexões.

## Função de Busca

A função `searchConnections()` é ativada quando o botão "Buscar" é clicado. Ela faz o seguinte:

- Recupera o nome de usuário inserido pelo usuário.
- Verifica se o usuário existe no objeto `graph`.
- Se o usuário existir, exibe uma lista de amigos do usuário pesquisado.
- Se o usuário não existir, mostra uma mensagem informando que o usuário não existe.

## Link para a Rede Social
Você pode acessar a rede social simulada [clicando aqui](https://wallacyfernandez.github.io/Projeto-Final-Estrutura-de-Dados-2/).

## Exemplo de Uso

Para experimentar o código, basta inserir o nome de um usuário na barra de busca e clicar no botão "Buscar".

```html
<script>
    const graph = {
        // ... (dados de conexão)
    };

    function searchConnections() {
        // ... (lógica de busca)
    }
</script>



