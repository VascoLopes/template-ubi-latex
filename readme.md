# Template em LaTeX, não oficial, para a escrita de teses e dissertações na Universidade da Beira Interior (UBI)

O conjunto de ficheiros aqui encontrados representam uma versão não oficial do template para escrita de teses e dissertações da UBI, que pode ser encontrado [e-projects.ubi.pt](http://www.e-projects.ubi.pt/latex/template.html), sendo possível efetuar o download em [área reservada UBI](https://minha.ubi.pt/sub/areareservada/).

Esta versão não oficial é baseada na versão 2.2 do template oficial: "Versão 2.2 - 01/06/2016". Encontra-se de acordo com o despacho Reitoral nº 49/R/2010.

## Alterações em relação ao template oficial:
- **Resolução do problema da não existência do ficheiro "algorithmic.sty"**
- **Alteração à maneira como são feitos os acrónimos**. Os acrónimos deixam de ser feitos como uma tabela, o que impossibilitava a sua referência, passando a ser feitos com auxílio do pacote "Acronym". Agora podem ser criados com o comando \acro{}{} e referênciados normalmente, utilizando \ac{} ou um comando similar.
- **Alteração do tipo de letra para "Trebutchet MS"**. Acrescentou-se os ficheiros necessários e configurou-se o tipo de letra para ser o Trebutchet MS para estar de acordo com o regulamento.

## Utilização deste template
### Como utilizar num ambiente de desenvolvimento online (testado no ShareLatex e no Overleaf)
- Fazer download do conjunto de ficheiros no formato .zip
- Fazer upload do .zip num ambiente de desenvolvimento online
- Alterar o compilador para XeLatex
