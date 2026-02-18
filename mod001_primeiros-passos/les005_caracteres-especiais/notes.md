# Elemento &lt;br&gt;

Força quebras de linha. Use-a apenas se a quebra for parte do conteúdo (como poesias), **nunca para criar vários espaços em sequência**.

# Comentários em HTML

São **notas explicativas ou trechos de código ignorados pelo navegador**. Servem para documentar o código e *não aparecem na página renderizada*.

```html 
<!-- essa linha não será renderizado no navegador. -->
```

# HTML Entities (Caracteres Especiais)

Referências (ex: &uarr;) para símbolos reservados ou moedas, garantindo a exibição correta e **evitando que o navegador os confunda com tags**.

> ***& + o código da sintaxe do caractere (@entity_name).***

- &cent; --> "¢"
- &copy; --> "©"
- &yen;  --> "¥"

> ***&# + o código numérico do caractere (@entity_number).***

- &#162; --> "¢"
- &#169; --> "©"
- &#165;  --> "¥"


# Emojis

São ícones inseridos via **códigos Unicode hexadecimais** (ex: &#x1F604;). O site ```emojipedia.org``` é a referência ideal para encontrar esses códigos (codepoints).

> ***&#x + o código hexadecimal do emoji (Unicode)***

- &#x1F94A; --> 🥊
- &#x1F44A; --> 👊
- &#x1F38A; --> 🎊

> ***&# + o código decimal do emoji (Numérico)***

- &#129354; --> 🥊
- &#128074; --> 👊
- &#127882; --> 🎊