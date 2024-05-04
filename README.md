
# Simulador de Loteria (Mega-Sena) <img align="right" src="https://github.com/andrepardinho/Simulador-Mega-Sena/assets/153616098/e39d5ee9-d55a-406d-a513-00d3128d7768" width="115"/> 


Este é um **simulador de loteria desenvolvido em C** como parte de uma atividade da disciplina de programação do curso de Ciência da Computação.

<br>

## Funcionalidades

- O usuário pode escolher seis dezenas entre 1 e 60.
- O programa simula tentativas de sorteio até que todas as dezenas escolhidas sejam sorteadas.
- Exibe o número de tentativas necessárias para acertar todas as dezenas.

## Como usar

1. Execute o programa.
2. Digite as seis dezenas desejadas, uma de cada vez, quando solicitado.
3. Aguarde até que o programa encontre uma combinação que corresponda às dezenas escolhidas. O que pode demorar um tempinho já que em uma aposta de 6 números, existem 50.063.860 (+50 milhões) de combinações possíveis.

## Imagens de Exemplo
**Dezenas escolhidas:** <br>
![Numbers choices](https://github.com/andrepardinho/Simulador-Mega-Sena/assets/153616098/2405b0b8-2859-4be9-8cf1-490d6bd70ac9)

**Sorteios sendo realizados:** <br>
![program running](https://github.com/andrepardinho/Simulador-Mega-Sena/assets/153616098/4c887d33-c0d5-49e6-b148-5a81437c7ec9)

**Resultado:** <br>
![Result](https://github.com/andrepardinho/Simulador-Mega-Sena/assets/153616098/b3ff87f6-0ebf-4b69-9cc0-3343485a002b) <br>
Neste exemplo, como é possivel notar, foram necessárias mais 29 milhões de tentativas de sorteios até que as 6 dezenas fossem acertadas.


## Habilidades Trabalhadas

- ***Manipulação de Arrays:*** O programa utiliza arrays para armazenar as dezenas escolhidas pelo usuário e para controlar os números já sorteados, garantindo que não haja repetição de números durante o sorteio.
- ***Geração de Números Aleatórios:*** A **função rand()** é utilizada para gerar **números aleatórios**, simbolizando os sorteios da loteria.
- ***Uso de semente aleatória*** com base no tempo atual do sistema, garantindo que cada execução do programa produza uma **sequência de números diferente**.
- ***Laços de Repetição:*** O programa utiliza **loops while e for** para simular múltiplas tentativas de sorteio até encontrar uma combinação vencedora.
- ***Controle de Fluxo:*** O programa utiliza **estruturas condicionais** para verificar se os números escolhidos pelo usuário estão dentro do **intervalo** permitido e para determinar quando todas as dezenas foram acertadas.

### Contribuições

Contribuições são bem-vindas! Se você tiver sugestões de melhorias, correções de bugs ou novas funcionalidades, sinta-se à vontade para abrir uma issue ou enviar um pull request.
