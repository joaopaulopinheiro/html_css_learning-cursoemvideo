# Listas em HTML

## Elemento &lt;ol&gt;

Representam listas **onde a sequência dos itens é fundamental para o significado**, como em receitas ou direções. 

```type=""```

> Configura o **estilo do marcador** apenas nas listas ordenadas. (1 A a I i)

```start=""```

> Define o **número inicial da contagem em listas ordenadas**, aceitando *sempre um valor inteiro*.


## Elemento &lt;ul&gt;

Representam listas de itens cuja ordem **não possui valor numérico** e não é importante. 

```list-style-type:```

> Configura o **estilo do marcador** apenas nas listas não ordenadas, através do CSS. (disc square circle)


## Elemento &lt;li&gt;

**Identifica cada item** dentro das listas.

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

Estrutura que funciona como um dicionário, **relacionando grupos de termos e descrições**.

### Termo de Definição (&lt;dt&gt;)

Especifica **o nome ou o termo a ser definido** dentro de uma lista de definição.

### Descrição de Definição (&lt;dd&gt;)

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