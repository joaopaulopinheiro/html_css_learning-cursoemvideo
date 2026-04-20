# Introdução aos Estilos CSS

## Estilos Inline

Consistem em aplicar regras de estilo diretamente dentro das tags HTML para configurações extremamente pontuais e específicas.

> `style=""`

Atributo HTML usado para abrir a declaração de estilos CSS dentro de uma tag.

> `background-color`

Propriedade que define a cor de fundo de um elemento.

> `color`

Propriedade CSS responsável por alterar a cor do texto.

> `font-family`

Define a família tipográfica (fonte) que será aplicada ao texto.

> `text-align`

 Controla o alinhamento horizontal do texto, podendo ser à esquerda, direita, centralizado ou justificado.

> `font-size`

Atributo que define o tamanho da fonte, podendo usar unidades como pixels (px) ou medidas relativas (em).

## Estilos Internos

Permitem organizar o código separando o conteúdo do design dentro de um único arquivo HTML, facilitando a manutenção de páginas isoladas.

### Elemento &lt;style&gt;

Tag colocada dentro do `&lt;head&gt;` que delimita a área onde todas as regras CSS daquela página serão escritas.

## Estilos Externos

É a técnica mais versátil e profissional, onde os estilos são armazenados em um arquivo `.css` separado para serem compartilhados por todo o site.

## Regras CSS

São as diretrizes que definem como o navegador deve interpretar e aplicar as estilizações.

> `@charset "UTF-8";`

Regra inserida no topo do arquivo CSS para garantir a compatibilidade e exibição correta de caracteres acentuado.

> `text-decoration`

Propriedade usada para adicionar ou remover decorações de texto, como o sublinhado padrão de links (none).

### Link para Estilo

A tag `&lt;link&gt;`, inserida no `&lt;head&gt;`, é a responsável por conectar o arquivo HTML ao arquivo CSS externo.

### Nível de Especificidade

Define a hierarquia de poder das regras: Inline (maior poder) sobrepõe o Local/Interno, que por sua vez sobrepõe o Externo.

<!-- Perguntas (SRS)

01. Quando diferentes formas de aplicar CSS são usadas simultaneamente no mesmo elemento, qual é a ordem correta de precedência (do mais forte para o mais fraco)?

Resposta: Inline > Interno > Externo

02. Qual regra deve ser declarada no início de um arquivo CSS externo para garantir suporte a caracteres acentuados?

Resposta: @charset "UTF-8"

03. Verdadeiro ou Falso: Sobre o uso combinado de técnicas CSS:

I. É permitido usar CSS inline, interno e externo no mesmo documento
II. O uso combinado pode gerar conflitos de estilo devido à precedência
-->
