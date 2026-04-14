# Semântica em HTML5

É a prática de usar as tags HTML **priorizando o significado do conteúdo em vez de sua forma visual**.

Algumas tags em HTML4 que se tornaram **obsoletas**, eram puramente visuais, como as tag `<font>, <center> e <u>`. Em HTML5, as tags _carregam sentido_, deixando essa apresentação estética para o CSS.

# Formatações em HTML

## Elemento &lt;strong&gt; [Texto importante]

Indica que o conteúdo **tem forte importância, seriedade ou urgência**. Diferente da tag `<b>`, ele é _semântico e não foca apenas na estética do negrito_.

<!-- INFO: Exemplo -->

```html
<p><strong>Aviso:</strong> tenha cuidado!</p>
```

## Elemento &lt;em&gt; [Itálico / Ênfase]

Representa uma **ênfase no conteúdo, alterando o tom de voz da sentença**. Ela é semântica e exibe o texto em itálico, diferenciando-se da tag `<i>`, que _representa texto em um tom ou humor alternativo, como termos técnicos ou nomes científicos_.

<!-- INFO: Exemplo -->

```html
<p>Nós <em>tivemos</em> que fazer isso!</p>

<p>A filosofia <i lang="jp">Kaizen</i> é essencial.</p>
```

## Elemento &lt;mark&gt;

Representa um texto **destacado ou marcado por sua relevância** em um determinado contexto.

<!-- INFO: Exemplo -->

```html
<p>
  A Guerra Fria foi uma batalha <mark>tecnológica</mark> entre os EUA e a URSS.
</p>
```

## Elemento &lt;small&gt;

Utilizada para **comentários secundários, letras miúdas ou avisos legais (como direitos autorais)**.

<!-- INFO: Exemplo -->

```html
<p><small>O conteúdo é licencidado pela licença BY-ND.</small></p>
```

## Elemento &lt;del&gt;

Indica que um intervalo de texto **foi deletado do documento e não deve ser considerado**.

```html
<p>Devemos <del>fechar</del> abrir a loja hoje!</p>
```

## Elemento &lt;ins&gt;

Representa **um texto que foi adicionado ao documento**. Ela é semântica e exibe o texto sublinhado, diferenciando-se da tag `<u>`, que _representa anotação não textual, como erros de ortografia_.

<!-- INFO: Exemplo -->
```html
<p>Gosto de <del>Frango</del> <ins>Ovo</ins> com <u>pharofa</u>!</p>
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
<p>O comando <code>console.log()</code> exibe o conteúdo na tela.</p>

<pre>O TEX   T  O VAI F  I C AR  A SS I M  N  O NAV  E   G AD  OR</pre>
```

## Elementos &lt;q&gt; e &lt;blockquote&gt;

O primeiro, **é usado para citações curtas inseridas no meio de um parágrafo, é semântico** e o navegador insere automaticamente as aspas. Já o segundo, **indica uma citação longa em bloco**, geralmente renderizada com um recuo lateral.

> `cite=""`

Indica o **link da fonte original** para fornecer contexto e crédito ao autor da informação.

<!-- INFO: Exemplo -->
```html
<p>Fulano: <q>somos aquilo que nos deixamos ser</q></p>

<blockquote cite="https://sitequalquer.com/index.html">
  A vida é bela, pois com ela, podemos aprender, ensinar e se relacionar com outros seres, vivos ou mortos.
</blockquote>
```

## Elemento &lt;abbr&gt;

Representa uma **abreviação ou acrônimo**, como siglas e mnemônicos.

> `title=""`

Fornece **o significado completo do termo**, que aparece quando o usuário passa o mouse sobre a sigla.

```html
<p>A <abbr title="HyperText Markup Language">HTML</abbr> é usada para criar sites.</p>
```

## Elemento &lt;address&gt;

Representa **informações de contato, como endereço físico, e-mail, telefone entre outros** detalhes de contato relacionados ao autor do conteúdo da página.

```html
<address>
  <p>João Paulo Pinheiro</p>
  <p>Rua dos Desenvolvedores, 456</p>
  <p>São Paulo, SP - CEP: 01234-567</p>
  <p>Telefone: (00) 94002-8922</p>
</address>
```

<!-- Perguntas (SRS):

01.  No contexto do desenvolvimento web com HTML5, o que define o conceito central de semântica?

Resposta: O foco no significado e na função dos elementos para estruturar o conteúdo.

02. Verdadeiro ou Falso: O uso de HTML semântico melhora o ranqueamento de um site em mecanismos de busca como o Google.

Resposta: Verdadeiro

03.Qual é a diferença de uso entre os elementos <em> e <i> no HTML5?

Resposta: <em> indica ênfase no texto, enquanto <i> representa termos técnicos ou contextuais.

04. De acordo com o MDN, qual é um caso de uso válido para o elemento <u> no HTML5?

Resposta: Marcar erros ortográficos em um texto.

05. Para escrever fórmulas como H₂O e x² em HTML, quais tags devem ser usadas respectivamente?

Resposta: <sub> e <sup>

06. Verdadeiro ou Falso: A tag `<del>` deve ser usada para indicar um texto que foi removido e não deve ser mais considerado pelo leitor.

Resposta: Verdadeiro

07. Qual é a principal diferença de aplicação entre <blockquote> e <q>?

Resposta: <blockquote> é usado para citações longas (em bloco), enquanto <q> é para citações curtas inseridas na linha do texto.

08. Complete a lacuna: No uso da tag <blockquote>, o atributo utilizado para indicar a URL da fonte original é ______.

Resposta: cite

09. Complete a lacuna: Para fornecer o significado completo de uma sigla na tag <abbr>, deve-se usar o atributo ______.

Resposta: title

10. A tag ______ é utilizada para fornecer informações de contato (físico ou digital) relacionadas ao autor ou proprietário de um documento.

Resposta: <address>
-->
