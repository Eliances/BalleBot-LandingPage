#Dicas uteis para programar HTML no VSCode


-Iniciar o VSCode apenas anotando um "!" e enter para autocompletar com alguns atalhos úteis;

-A Segunda linha "meta" aparentemente não é algo relevante no primeiro momento a ser editado;

-Insterir uma linha "meta" com o nome "description" para ser a descrição apresentada pelo Google na home do site;

-Foi adicionado o "header" para ser apresentado como cabeçalho, "main" para ser o corpo do site (parte principal) e "footer" para ser o rodapé do site;

-A instrução "<nav>" é um tipo de menu para navegação;

-Dentro da instrução "nav" pode se usar a tag "<a>" que serve como redirecionamento quando clicado (âncora);

-Quando colocada a instrução "<img>" deve ser utilizada junto a instrução "src" para definir a origem da imagem a ser escolhida, caso não esteja na mesma raíz que o projeto, também deve ser dito o diretorio (Deve também ser usado junto o "alt" para ser a mensagem alternativa caso a imagem não carregue);

-No HTML é usado tags h1 até h6 para definir tamanho das palavras na página;

-A instrução "p" é referente a um parágrafo de texto;

-Pode ser usada a instrução "<strong>" para deixar trechos em negrito, para isso é só definir os parâmentros dentro do próprio texto;




#Dicas uteis para programar CSS no VSCode


-É recomendado começar o código em CSS usando "*" antes de qualquer linha, isso desfaz qualquer alteração já feita automaticamente pelo editor de codigos;

-Quando for utilizar o CSS para ajustar o HTML é sempre bom deixar o HTML já com classes formadas, pra isso basta colocar "class" após a primeira instrução do HTML e para chamar essa classe em CSS basta usar ".CLASSE {";

-Utilizar o Google Fonts para importar fontes para o CSS, basta pesquisar a fonte e copiar o @import gerado por ele na aba selected families;

-"margin" = distância da tag para a parte mais externa // "padding" = distância da tag para o conteúdo interno;

-Um fundo estilizado pode ser feito com gradiente, para isso pode ser retirado do figma, selecionando o fundo e indo na aba "inspect" na sessão CSS > Background";

-A maneira para linkar o CSS ao HTML é seguindo a seguinte linha: "<link rel="stylesheet" type="text/css" href="NOME-DO-CSS">", feito isso no head o HTML irá começar a seguir a diagramação do CSS;

-Pode ser utilizado o guia do Flexbox para auxiliar na indentação de itens na página, podendo automaticamente ajustar distâncias;

-Com o Flexbox podemos editar as propriedades dos parent e dos children, ou seja, das sessões pais e dos itens dessas sessões, os filhos;

-Para editar a fonte de algum dos itens pode-se só copiar do Google Fonts na região "CSS rules";

-"display-flex" é útil para alinhar horizontalmente todos itens de uma classe, alé disso é interessante deixar o "flex-direction: row" garantindo que irá ficar na horizontal;

-"display: flex" alinha toda uma célula;

-Padding quando não justificado qual o lado que vai ser afastado faz com que TODOS os lados sejam afastados;

-Outra maneira de centralizar algo sem prevcisar do flexbox é definindo na variável um "display: block" e "margin: auto";

-Para estilizar um botão, para mudar de cor quando o mouse passar por cima deve ser feito após todas as propriedades, repetir a "variável:hover", assim pode-se editar e tudo só mudará quando o mouse estiver em cima do objeto;

-Para gerar um link em um botão ou texto, basta usar o 'href="link-desejado"' que assim irá ser encaminhado para o local linkado quando clicar;

-