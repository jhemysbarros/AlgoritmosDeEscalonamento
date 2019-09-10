## Trabalho de Sistemas Operacionais

**Algoritmos de Escalonamento de Processos**

O trabalho consistiu em desenvolver três algoritmos de escalonamento: **FIFO**, **SJF** e **SRTF** usando qualquer linguagem de programação, por ter mais familiaridade, optei por utilizar a linguagem Java.

1. **FIFO**
   O FIFO é um escalonamento não¬-preemptivo aonde o processo que chegar primeiro ao estado de pronto é o selecionado para execução. Este algoritmo é bastante simples, sendo necessária apenas uma fila, onde os processos que passam para o estado de pronto entram no seu final e são escalonados quando chegam ao seu início.

2. **SJF**
   No escalonamento SJF, o algoritmo de escalonamento seleciona o processo que tiver o menor tempo de processador ainda por executar. Dessa forma, o processo em estado de pronto que necessitar de menos tempo de UCP para terminar seu processamento é selecionado para execução.

3. **SRTF**
   O SRTF é um escalonamento preempitivo, se um processo chega na fila de prontos com um tempo de **BURST** menor que o tempo restante do processo em execução, então há preempção, pois ele atende a um tempo de chegada para iniciar a execução de um processo, comparando em seguida seu tempo de burst, liberando o processo com o menor tempo de burst restante.
