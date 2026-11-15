# Gerenciador Inteligente de Mensagens Automáticas com Inteligência Artificial para Whatsapp

## Descrição

Com o aumento considerável de participantes em um grupo no Whatsapp, dedicado a organizar partidas de vôlei em dois horários diferentes a jogadores atendendo ao máximo possível de critérios definidos para a escolha, torna-se necessário um mecanismo de automação inteligente e autônomo, capaz de realizar as operações abaixo:

- Identificar e/ou selecionar parâmetros existentes ou produzir novos para tomada de decisão;
- Enviar mensagem, incluindo a lista de jogadores e informações importantes sobre o horário, a data, o local e o ginásio onde ocorrerá o jogo, a um contanto centralizado para cada gatilho percebido após o evento `receber mensagem de usuário com contexto apresentando intenção em participar do racha`;

## Objetivo

## Fluxo de Funcionamento

- Cadastra-se uma conta no Whatsapp totalmente dedicada a apenas receber mensagens de diferentes contatos;

- Verifica-se o assunto e o contexto de cada uma das mensagens, identificando os seguintes padrões:

    - Contatos que enviaram cada uma das mensagens a essa conta no Whatsapp;
    - Mensagens cujos assunto e contexto estejam totalmente definidos:

        -  Intenção seja participar ou indicar quem jogará;
        -  Intenção não esteja relacionada ao esporte vôlei;

    - Mensagens cujos assuntos e/ou contextos estejam parcialmente ou não definidos:
       
        - Usar métodos indutivos, considerando o comportamento anterior do autor da mensagem. (Ex: Geralmente é o contato x ou referência ao contato y que menciona diretamente/parcialmente ou não sobre vôlei, e/ou definiu o contexto da mensagem para o contexto k anterior).

- Após reconhecer que o autor da mensagem tem intenção em ir ao racha ou mencionar quem vá, buscar e encontrar todas as referências ao contato dessa pessoa que tem interesse em jogar, percebendo como ela costuma ser chamada.

- Escrever na lista centralizada o nome ou apelido (caso encontrado) e a referência à conversa do Whatsapp que enviou a mensagem.