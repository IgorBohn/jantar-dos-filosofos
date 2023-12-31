# Jantar dos Filósofos

Desenvolvido para a matéria de Linguagem de Programação 4.

Este é um projeto que simula o clássico problema dos filósofos famintos, também conhecido como "Jantar dos Filósofos". O problema foi formulado por E.W. Dijkstra em 1965 para ilustrar os desafios de sincronização em sistemas distribuídos e a necessidade de evitar deadlocks.

O problema consiste em um cenário onde cinco filósofos estão sentados em torno de uma mesa redonda. Cada filósofo alterna entre os estados de pensar e comer. Eles compartilham cinco garfos, um entre cada par de filósofos. Para comer, um filósofo precisa pegar os garfos à sua esquerda e à sua direita. No entanto, se um garfo estiver sendo usado por um filósofo vizinho, o filósofo atual deve esperar até que ambos os garfos estejam disponíveis.

O projeto demonstra as situações em que os filósofos podem entrar em deadlock (quando todos pegam um garfo e ficam esperando pelo outro) e como diferentes soluções de sincronização podem ser aplicadas para evitar esse problema.
