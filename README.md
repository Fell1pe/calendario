## Calendário de Veículos - Agendamento e Codificação por Cores

Este projeto cria um aplicativo de calendário simples onde você pode escolher uma cor e atribuí-la a um dia específico para seus veículos.

**Recursos:**

* Exibe um calendário com dias da semana e datas.
* Permite a seleção de uma cor e um dia.
* Altera a cor de fundo do dia escolhido no calendário com base na cor selecionada.

**Tecnologias Usadas:**

* HTML: Define a estrutura e o conteúdo da página web.
* CSS: Define a aparência visual do calendário, legenda de cores e outros elementos.
* JavaScript: Implementa a funcionalidade para alterar a cor de fundo de um dia com base na seleção do usuário.

**Descrição do Código:**

**HTML (index.html):**

Este arquivo estrutura o layout da página web, incluindo a tabela do calendário, a legenda de cores, controles de seleção (menu suspenso de cores e entrada de dia) e um botão de envio.

**CSS (style.css):**

Este arquivo define estilos para vários elementos, como a borda do calendário, cabeçalhos e células da tabela, fundo da legenda de cores, formatação de texto e espaçamento.

**JavaScript (calendario.js):**

Este arquivo contém a função `colorirDia()`. Quando o botão de envio é clicado:

1. Ele recupera o valor do dia selecionado no campo de entrada "dia".
2. Ele recupera o valor da cor selecionada no menu suspenso "cor".
3. Ele acessa o elemento da tabela do calendário usando seu ID ("calendário").
4. Ele usa `getElementsByTagName('td')` para obter todos os elementos de dados da tabela (td).
5. Ele calcula o índice da célula do dia alvo adicionando 2 ao valor do dia selecionado (considerando o deslocamento dos cabeçalhos dos dias da semana).
6. Ele acessa o elemento `td` específico usando o índice calculado e define sua propriedade de estilo `backgroundColor` para a cor escolhida.

**Instruções:**

1. Salve o arquivo HTML como `index.html`.
2. Salve o arquivo CSS como `style.css`.
3. Salve o arquivo JavaScript como `calendario.js`.
4. Abra `index.html` em um navegador web para visualizar o aplicativo de calendário.
5. Selecione uma cor e insira um número de dia (entre 1 e 31).
6. Clique no botão de envio para ver a cor do dia escolhido no calendário mudar.

**Notas Adicionais:**

* Você pode personalizar ainda mais o CSS para aprimorar o estilo visual do calendário e da legenda de cores.
* A funcionalidade do JavaScript pode ser estendida para implementar recursos como:
    * Armazenamento de atribuições de cores para uso futuro (usando armazenamento local ou banco de dados).
    * Exibir cores diferentes para veículos diferentes.
    * Destacar eventos futuros em datas específicas.

Este README fornece um ponto de partida para a compreensão da funcionalidade do projeto e do potencial para desenvolvimento futuro.