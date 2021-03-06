# CSS (Flexbox)

Display:flex --> Torna a tag um elemento do tipo flex container, e assim automaticamente todos os seus filhos diretos desta tag tornam se em flex itens.

Flex direction -->  É a propriedade que estabelece o eixo principal do container definindo assim a direção que os flex itens são colocados no flex container.

* row(padrão): à direção do texto,esquerda para direita.
* row reverse: sentido opsto à direção do texto.
* column: orddenação de cima par baixo, em coluna unica.
* column reverse: ordenação ineversa ,de baixo para cima 

Flex wrap --> É a propriedade que define se os itens devem ou não quebrar a linha. Por padrão eles nao quebram linhas, isso faz com que os flex itens sejam compactados além do limite do conteúdo.

* nowrap: é o padrão, não permite a quebra de linha.
* wrap: permite a quebra de linha asssim que um dos flex itens não puder mais ser compactado.
* wrap reverse: Permite q a quebra de linha assim que um dos flex itens não puder mais ser compactado, porém na direção contraria da linha, acima.

Flex flow --> É um atalho para as propriedades flex direction e flex wrap.Porém seu uso não é tão comum, visto que, quando mudamos o flex direction para column, mantemos o padrão do flex wrap que é nowrap.

Justify Content --> Essa propriedade vai se encarregar de alinhar os itens dentro do container de acordo com a direção pretendida e tratar da distribuição de espaçamentoo entre eles.OBS: Caso seus itens esteja ocupando 100% de todo o container, ele não se aplica.

* flex-start: inicio do container.
* flex-end: final do container.
* center: ao centro do container.
* space-between: cria um espaçamento igual entre os elementos.
* space-around: os espçamentos do meio são duas vezes maiores que o inicial e final.

Align-items --> Trata do alinhamneto dos flex itens de acordo com o eixo do container. O alinhamento é diferente para quando os itens estão em colunas ou linhas. Permite o alinhamento central no eixo vertical.

* Tipos de Alinhamento:
* center: alinhamento dos itens ao centro.
* stretch: padrão, e os flex itens crescem igualmente. 
* flex-start: alinhamento dos itens no inicio.
* flex-end: alinhamento dos itens no final.
* baseline: alinhamento de acordo com a linha base da tipografia dos itens.

# Propriedades Flex items

Flex grow --> Define a proporcionalidade de crescimento dos itens, respitando o tamanho de seus conteúdos internos. OBS: Não irá funcionar caso tenhamos adicionado justify-content ao nosso flex container.

Flex basis --> É a propriedade que estabelece o tamanho inicial do item antes da distribuição de espaço restante dentro dele, usando como base o conteúdo interno disposto.

* Valores possíveis:
* auto: caso o item não tenha tamanho, este será proporcional ao conteúdo do item.
* px, %, em....: são valores exatos previamente definidos.
* 0 (zero): terá relação com a definição do flex-grow.

flex-shrink --> É a propriedade que estabelece a capacidade de redução ou compressão do tamanho de um item.

Flex --> Esta propriedade é um atalho ou abreviação de escrita para as propriedades: grow, shrink e basis.

Order --> Propriedade que aplica uma ordem aos elementos no css.

Align-self --> É a propriedade que estabelece o alinhamento de modo individual sobre um determinado item.

* Valores:
* auto: valor padrão, irá respeita a definição de align-items do container.
* flex-start: ao inicio do container.
* flex-end: ao final do container.
* center: relativo ao centro de acordo com o eixo.
* stretch: ocupa todo os espaços relativo.
* baseline: utiliza a linha base da tipografia.




