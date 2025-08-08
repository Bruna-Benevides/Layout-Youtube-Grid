# Layout Youtube com Grid

## Descrição do Projeto

Neste projeto o objetivo era criar um layout com grid, simulando a plataforma do youtube.

### Arquivos usados

Para isso usamos um arquivo de reset, para reconfigurar a tela e zerar os padrões.

E um arquivo de estilos em CSS para estilizar os elementos de forma a alinhá-los em grade.

E um HTML com tag **Main** para o contéudo, com algumas tags **Divs** para fazer as separações de elementos e dentro delas alguns links, com a tag **A**

### Formatação do projeto

Na primeira **Div** utilizamos um link onde colocamos uma tag video com classe _video-destaque_ , uma h1 com classe _titulo-destaque_,  e dois Ps com classe _vistos_ e _texto_ com informações sobre o video.

Na lateral, separamos com uma **section** com classe _lateral_ e quatro **Divs** para fazer a separação de propaganda e três videos com classe _videos-sugeridos_ . E assim estilizamos os três vídeos com as mesmas medidas e padrão, alinhando eles com o Flexbox.

E utilizamos o **display: grid** para alinhar todo o conteúdo em grade, com ajuda do _grid-template-area_ .
