# Semântica em HTML5

É a prática de usar as tags HTML **priorizando o significado do conteúdo em vez de sua forma visual**. O objetivo é melhorar a *acessibilidade, a SEO (Search Engine Optimization) e a manutenção do código*.

Algumas tags em HTML4 que se tornaram **obsoletas**, eram puramente visuais, como as tag ```<font>, <center> e <u>```. Na HTML5, as tags carregam sentido, deixando a apresentação estética para o CSS.


# Formatações em HTML

## Elemento &lt;strong&gt;

Indica que o conteúdo **tem forte importância, seriedade ou urgência**. Diferente da tag ```<b>```, ela é *semântica e não foca apenas na estética do negrito*.

<!-- INFO: Exemplo -->

```html
<p><strong>Aviso:</strong> tenha cuidado!</p>
```


## Elemento &lt;em&gt; (Itálico / Ênfase)

Representa uma **ênfase no conteúdo, alterando o tom de voz da sentença**. Ela é semântica e geralmente exibe o texto em itálico, diferenciando-se da tag ```<i>```, que *representa texto em um tom ou humor alternativo, como termos técnicos ou nomes científicos*.


<!-- INFO: Exemplo -->

```html
<p>Nós <em>tivemos</em> que fazer isso!</p>

<p>A filosofia <i lang="jp">Kaizen</i> é essencial.</p>
```


## Elemento &lt;mark&gt;

Representa um texto **destacado ou marcado por sua relevância** em um determinado contexto.


<!-- INFO: Exemplo -->

```html
<p>A Guerra Fria foi uma batalha <mark>tecnológica</mark> entre os EUA e a URSS.</p>
```


## Elemento &lt;small&gt;

Utilizada para **comentários secundários, letras miúdas ou avisos legais (como copyright)**.

<!-- INFO: Exemplo -->

```html
<p><small>O conteúdo é licencidado pela licença BY-ND</small></p>
```


## Elemento &lt;del&gt;

Indica que um intervalo de texto **foi deletado do documento e não deve ser considerado**.

```html
<p>Devemos <del>fechar</del> abrir a loja hoje!</p>
```

## Elemento &lt;ins&gt;

Representa um **um texto que foi adicionado ao documento**. Ela é semântica e geralmente exibe o texto sublinhado, diferenciando-se da tag ```<u>```, que *representa anotação não textual, como erros de ortografia*.


<!-- INFO: Exemplo -->

```html
<p>Gosto de <del>Frango</del> <ins>Ovo</ins>!</p>
```

## Elementos &lt;sup&gt; e &lt;sub&gt;

O primeiro, **define um texto sobrescrito, posicionado acima da linha de base**. Já o segundo, **define um texto subscrito, posicionado abaixo da linha de base com fonte menor**.

<!-- INFO: Exemplo -->

```html
<p>Na matemática, temos X<sup>2</sup> e na Química, temos H<sub>2</sub>O!</p>
```


## Elementos &lt;code&gt; e &lt;pre&gt;

O primeiro, **delimita fragmentos curtos de código de computador e possui valor semântico**. Já o segundo, **representa texto pré-formatado, mantendo exatamente os espaços, tabulações e quebras de linha digitados no arquivo HTML**.

<!-- INFO: Exemplo -->

```html
<p>O comando <code>console.log</code> exibe o conteúdo na tela.</p>

<pre>O TEX  T O VAI  FI C A R  EXATA   M   E   N TE ASSIM</pre>
```


## Elementos &lt;q&gt; e &lt;blockquote&gt;

O primeiro, **é usado para citações curtas inseridas no meio de um parágrafo, é semântico e o navegador insere automaticamente as aspas.**. Já o segundo, **indica uma citação longa em bloco, geralmente renderizada com um recuo lateral**.

```cite=""```

> Indica o **link da fonte original** para fornecer contexto e crédito ao autor da informação.

<!-- INFO: Exemplo -->

```html
<p>Fulano: <q>somos aquilo que nos deixamos ser</q></p>

<blockquote cite="https://sitequalquer.com/index.html">
    A vida é bela, pois com ela, podemos aprender, ensinar e se relacionar com outros seres, vivos ou mortos.
</blockquote>
```


## Elemento &lt;abbr&gt;

Representa uma abreviação ou acrônimo, como siglas e mnemônicos.

```title=""```

> Fornece **o significado completa do termo**, que aparece quando o usuário passa o mouse sobre a sigla.

```html
<p>A <abbr title="HyperText Markup Language">HTML</abbr> é usada para criar sites.</p>
```