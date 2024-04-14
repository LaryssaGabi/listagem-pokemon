# Alternador de Tema Claro/Escuro

Este é um script JavaScript que permite ao usuário alternar entre os temas claro e escuro em uma página web. Quando o usuário clica em um botão, o tema da página é alternado entre claro e escuro, e a imagem do botão de alternância também é atualizada para refletir o tema atual.

## Funcionalidades

- **Alternância de Tema:** Permite ao usuário alternar entre os temas claro e escuro clicando em um botão.
- **Atualização da Imagem do Botão:** A imagem do botão de alternância é atualizada dinamicamente para refletir o tema atual (sol para tema claro e lua para tema escuro).

## Como usar

1. Adicione um botão na sua página HTML e atribua a ele o ID `botao-alterar-tema`.
2. Adicione uma imagem dentro do botão com a classe `.imagem-botao` para representar o ícone de alternância de tema.
3. Configure o caminho das imagens do botão para refletir o ícone de sol e lua para os temas claro e escuro, respectivamente.
4. Configure as classes CSS `modo-escuro` e `modo-claro` para estilizar os elementos da página de acordo com o tema.

## Estrutura do Código

- **Evento de Clique:** Adiciona um ouvinte de eventos de clique ao botão de alternância de tema.
- **Alternância de Classe:** Adiciona ou remove a classe `modo-escuro` do elemento `body` da página para alternar entre os temas claro e escuro.
- **Atualização da Imagem do Botão:** Atualiza dinamicamente a imagem do botão de alternância para refletir o tema atual.

## Dependências

- **JavaScript:** Não são utilizadas bibliotecas externas, apenas JavaScript puro.
- **HTML e CSS:** A estrutura e o estilo dos elementos devem ser definidos em HTML e CSS.


