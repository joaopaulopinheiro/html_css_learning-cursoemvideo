# Listas em HTML

## Elemento &lt;ol&gt;

Representam listas **onde a sequência dos itens é fundamental para o significado**, como em receitas ou direções.

> `type=""`
****
Configura o **estilo do marcador** apenas nas listas ordenadas. (1 A a I i)

> `start=""`

Define o **número inicial da contagem** em listas ordenadas, aceitando *sempre um valor inteiro*.

<!-- INFO: EXEMPLO -->
```html
<ol type="A" start="1">
    <li>Acordar</li>
    <li>Trabalhar</li>
    <li>Dormir</li>
<ol>
```

## Elemento &lt;ul&gt;

Representam listas de itens cuja ordem **não possui valor numérico** e não é importante.

> `list-style-type:`

Configura o **estilo do marcador** apenas nas listas não ordenadas, através do CSS. (disc square circle)

<!-- INFO: EXEMPLO -->
```html
<ul style="list-style-type: disc">
    <li>Café</li>
    <li>Chá</li>
    <li>Leite</li>
<ul>
```

## Elemento &lt;li&gt;

Identifica **cada item** dentro das listas.

<!-- INFO: Exemplo -->
```html
<h1>Meus livros favoritos</h1>
<ol type="2" start="10">
    <li>Desenvolvimento Pessoal</li>
    <ul style="list-style-type: square">
        <li>Essencialismo</li>
        <li>Poder do Subconsciente</li>
        <li>Milagra do Amanhã</li>
    </ul>
</ol>
```

## Elemento &lt;dl&gt;

Lista que funciona como um dicionário, **relacionando grupos de termos e descrições**.

### Elemento &lt;dt&gt;: [Termo de Definição]

Especifica **o nome ou o termo a ser definido** dentro de uma lista de definição.

### Elemento &lt;dd&gt;: [Descrição de Definição]

Provê a **definição, valor ou detalhe associado ao termo** anterior em uma lista de descrição.

<!-- INFO: Exemplo -->

```html
 <dl>
    <dt>Café</dt>
    <dd>- Bebida quente e de cor preta</dd>

    <dt>Leite</dt>
    <dd>- Bebida gelada e de cor branca</dd>

    <dt>Chá</dt>
    <dd>- Bebida quente/gelada e colorida.</dd>
</dl>
```

<!-- Perguntas (SRS)

01. Qual é a principal diferença conceitual entre o uso de uma lista ordenada (<ol>) e uma lista não ordenada (<ul>)?

Resposta: A lista ordenada é utilizada quando a sequência ou hierarquia dos itens é relevante para o sentido do conteúdo.

02. Para criar uma lista com algarismos romanos em maiúsculas (I, II, III...), o valor do atributo type deve ser ______.

Resposta: I

03. Na estrutura de uma Lista de Definição (<dl>), qual é a função da tag <dd>?

Resposta: Apresentar a descrição ou detalhamento do termo previamente declarado.

04. Como criar uma lista ordenada com numeração romana maiúscula iniciando no item 5?

Resposta: <ol type="I" start="5">

05. Qual é a forma recomendada de definir o estilo do marcador de uma lista <ul>?

Resposta: Através da propriedade CSS list-style-type

06. Complete a lacuna: 'Na estrutura de uma lista de definição, cada termo a ser definido é marcado pela tag ____'.

Resposta: <dt>
-->
