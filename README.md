# Desafio para Desenvolvedor de Hardware

**Ponto importante para todos os desafios:** o resultado não poderá ser enviado por e-mail. Ao invés disso, crie um repositório git e forneça um link de acesso com compartilhamento autorizado.

## Exercício 1 
Uma determinada aplicação requer uso de eletrônica analógica para interfaceamento entre uma fonte de luz pulsante entre 10kHz e 100kHz e um microcontrolador que irá analisar o sinal de saída. A primeira tarefa é selecionar um circuito de condicionamento para detectar a luz pulsante e gerar como saída uma onda quadrada a ser comparada pelo microcontrolador, assim como ilustra a figura a seguir.

![Fig1](https://user-images.githubusercontent.com/77103103/138298596-3d531325-b15b-4df0-a55d-daa209067c62.png)

Elabore o circuito de condicionamento considerando a utilização de um fotodetector e também com a possibilidade de regulagem da tensão limiar de detecção entre presença/ausência de luz.
A ideia é utilizar seus conhecimentos para criar um circuito funcional.


## Exercício 2 
Para fazer a análise do sinal de saída já condicionado pelo circuito analógico você deverá escolher um microcontrolador de sua preferência. O desafio agora é utilizar o software Kicad para implementar o esquemático do circuito de fotodetecção, condicionamento, microcontrolador e reguladores necessários, considerando que o sistema será alimentado através de uma bateria de Lithium.
O resultado esperado nesta etapa é o esquemático contendo todos circuitos projetados.

## Exercício 3
Em um desenvolvimento de projetos, após a criação do esquemático, deve-se realizar o layout da placa de circuito impresso, considerando todas as regras de roteamento, restrições de tensão, corrente e dimensões (se houver). Portanto, continue utilizando o software Kicad e projete uma placa de circuito impresso que comporte toda a eletrônica projetada durante as etapas anteriores.
O resultado esperado nesta etapa é ao menos o placement dos componentes e circuitos projetados anteriormente.

## Exercício 4
A Figura a seguir mostra uma PCI hipotética com sinais mistos de um produto que possui entradas digitais, uma entrada analógica de alta frequência e uma saída analógica também de alta frequência. Os circuitos integrados de sinais mistos possuem um clock de alta frequência, são alimentados por uma fonte chaveada e possuem capacitores de desacoplamento.

![Fig2](https://user-images.githubusercontent.com/77103103/138298753-ab919847-8524-49cd-affe-85be7642f531.png)

O desafio agora é realizar uma análise crítica da distribuição dos circuitos, blocos de desacoplamento, conectores de entrada e saída, planos de terra e linhas de alta frequência.
O resultado esperado é uma análise dizendo os pontos positivos, negativos e sugestões de melhorias. Caso deseje, faça também diagramas mostrando quais melhorias podem ser implementadas.
