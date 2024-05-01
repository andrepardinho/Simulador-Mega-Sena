
# Simulador de Loteria (Mega-Sena) <img align="right" src="https://github.com/andrepardinho/Simulador-Mega-Sena/assets/153616098/e39d5ee9-d55a-406d-a513-00d3128d7768" width="115"/> 


Este é um simulador de loteria desenvolvido em C como parte de uma atividade da disciplina de programação do curso de Ciência da Computação.

## Funcionalidades

- O usuário pode escolher seis dezenas entre 1 e 60.
- O programa simula tentativas de sorteio até que todas as dezenas escolhidas sejam sorteadas.
- Exibe o número de tentativas necessárias para acertar todas as dezenas.

## Como usar

1. Execute o programa.
2. Digite as seis dezenas desejadas, uma de cada vez, quando solicitado.
3. Aguarde até que o programa encontre uma combinação que corresponda às dezenas escolhidas. O que pode demorar um tempinho já que em uma aposta de 6 números, existem 50.063.860 (+50 milhões) de combinações possíveis.

## Imagens de Exemplo


## Habilidades Trabalhadas

- Manipulação de Arrays: O programa utiliza arrays para armazenar as dezenas escolhidas pelo usuário e para controlar os números já sorteados, garantindo que não haja repetição de números durante o sorteio.
- Geração de Números Aleatórios: A função rand() é utilizada para gerar números aleatórios, simbolizando os sorteios da loteria.
- Uso de semente aleatória com base no tempo atual do sistema, garantindo que cada execução do programa produza uma sequência de números diferente.
- Laços de Repetição: O programa utiliza loops while e for para simular múltiplas tentativas de sorteio até encontrar uma combinação vencedora.
- Controle de Fluxo: O programa utiliza estruturas condicionais para verificar se os números escolhidos pelo usuário estão dentro do intervalo permitido e para determinar quando todas as dezenas foram acertadas.

### Contribuições

Contribuições são bem-vindas! Se você tiver sugestões de melhorias, correções de bugs ou novas funcionalidades, sinta-se à vontade para abrir uma issue ou enviar um pull request.
