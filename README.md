# Estrutura padr�o de projeto para desenvolvimento do front-end
Esse � um medelo padr�o para desenvolvimento da parte do front-end seguindo boas pr�ticas de estrutura��o do projeto

## T�picos

- [Introdu��o](#introdu��o)
- [Stack e Instala��o](#stack-e-instala��o)
  - [Sass](#sass)
  - [Compass](#compass)
  - [Susy](#susy)
  - [Outros Componentes](#outros-componentes)


## Introdu��o

Para desenvolvimento do front-end de qualquer site � sempre bom manter um padr�o de estrutura independente do tipo e do tamanho do proejto em si. Por isso nesse reposit�rio � feito uma pr�-estrutura padr�o de projeto para ser seguida utilizando a tecnologia do Sass e fazendo a modulariza��o de partes do site tornando assim o projeto mais organizado e facilitando futuras melhorias e manuten��es

## Stack e Instala��o

Para a utiliza��o correta do padr�o de projeto deve ser instalado alguns componentes. � suma import�ncia que o usu�rio tenha um conhecimento pr�vio das tecnologias a seguir.

### Sass

Segundo a pr�pria documenta��o:
> Sass � uma extens�o de CSS que adiciona novas possibilidades e eleg�ncia � linguagem base.

O seu prop�sito � corrigir as falhas do CSS. Que � uma linguagem simples de aprender mas pode se tornar complexa de ser mantida. Por este motivo foi idealizado o Sass como uma meta-linguagem para melhorar a sintaxe original do CSS, oferencedo mais funcionalidades.

Sass � uma biblioteca (*gem*) Ruby e para instal�-la � necess�rio possuir o Ruby instalado.

Para Windows � necess�rio a instala��o do [Ruby Installer](http://rubyinstaller.org/).

Ap�s instalado basta abrir o terminal (linha de comando) e digitar `gem install sass`.

> Para mais informa��es clique [aqui](http://sass-lang.com/install).

### Compass

O Compass � uma framework CSS que utiliza a linguagem Sass para agregar poder e facilitar a escrita de estilos.

Ele possui uma grande quantidade de mixins previamente implementados que facilitam e diminuem a complexidade com atributos e sua compatibilidade cross-browser, como por exemplo `border-radius` and `text-shadow`. O Compass ainda facilita a utiliza��o de sprites de imagens.

Para instal�-lo voc� deve possuir o Ruby previamente instalado e executar o seguinte comando no terminal (linha de comando): `gem install compass`.

> Para mais informa��es clique [aqui](http://compass-style.org/install/).

### Susy

Susy � um grid framework que auxilia na delimita��o das colunas de conte�dos, auxiliando a criar layouts responsivos.

Para instal�-lo voc� deve possuir o Ruby previamente instalado e executar o seguinte comando no terminal (linha de comando): `gem install susy`.

> Para mais informa��es clique [aqui](http://susydocs.oddbird.net/en/latest/install/).

### Outros Componentes

- **Compass-normalize:** � um plugin do Compass que facilita o uso do `normalize.css`, que � um pequeno CSS cujo objetivo � aumentar a consist�ncia do CSS em diferentes browser, essa consist�ncia � atingida removendo as regras aplicadas por cada browser. Para instalar: `gem install compass-normalize`, mais [aqui](https://github.com/ksmandersen/compass-normalize).
- **Breakpoint:** � uma biblioteca que auxilia a escrita de media queries. Para instalar: `gem install breakpoint`, mais [aqui](https://github.com/at-import/breakpoint/wiki/Installation#installation).
- **optipng:** Otimizador de imagens. Para instalar siga as instru��es no [site oficial](http://optipng.sourceforge.net/). Lembrando que no Windows o caminho para o execut�vel deve estar no Path.


## Refer�ncias

Este guia de estilos foi baseado nos seguintes conte�dos:
- [Magamobi Sass Styleguide](https://github.com/Magamobi/sass-styleguide)