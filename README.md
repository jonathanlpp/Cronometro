
Este projeto é um cronômetro simples que permite iniciar, pausar e redefinir o tempo, além de adicionar marcas em momentos específicos.

Funcionalidades

Iniciar/Pausar o Cronômetro: Um botão que alterna entre iniciar e pausar o cronômetro.

Marcar Tempo: Adiciona uma marca com o tempo atual ao clicar no botão de marcação.

Redefinir: Reseta o cronômetro e limpa as marcas.

Estrutura do Código
HTML: Estrutura básica com elementos de controle e exibição.

JavaScript:
Seletores: Utiliza querySelector para manipular elementos do DOM.

Funções:
fomarTime(time): Formata o tempo em horas, minutos, 
segundos e centésimos.
addMarkToList(markIndex, markTime): Adiciona uma marca à lista exibida.

markTime(): Armazena o tempo atual e chama a função de adicionar marca.
toggleTime(): Inicia ou pausa o cronômetro.
resetTime(): Reseta o cronômetro e limpa as marcas.
setTimer(time): Atualiza a exibição do cronômetro.


Como Usar
Iniciar o Cronômetro: Clique no botão "Iniciar" para começar a contagem.
Adicionar Marca: Clique em "Marcar" para registrar o tempo atual.
Redefinir Cronômetro: Clique em "Resetar" para voltar ao estado inicial.
