# Elemento &lt;br&gt;

Força quebras de linha. Use-a apenas se a quebra for parte do conteúdo (como poesias), **nunca para criar vários espaços em sequência**.

# Comentários em HTML

São **notas explicativas ou trechos de código ignorados pelo navegador**. Servem para documentar o código e _não aparecem na página renderizada_.

```html
<!-- essa linha não será renderizado no navegador. -->
```

# HTML Entities (Caracteres Especiais)

Referências para símbolos reservados ou moedas, garantindo a exibição correta e **evitando que o navegador os confunda com tags**.

> _& + o código da sintaxe do caractere (@entity_name)._

- &cent; --> "¢"
- &copy; --> "©"
- &yen; --> "¥"

> _&# + o código numérico do caractere (@entity_number)._

- &#162; --> "¢"
- &#169; --> "©"
- &#165; --> "¥"

# Emojis

São ícones inseridos via **códigos Unicode hexadecimais**. O site `emojipedia.org` é a referência ideal para encontrar esses códigos (codepoints).

> **_&#x + o código hexadecimal do emoji (Unicode)_**

- &#x1F94A; --> 🥊
- &#x1F44A; --> 👊
- &#x1F38A; --> 🎊

> **_&# + o código decimal do emoji (Numérico)_**

- &#129354; --> 🥊
- &#128074; --> 👊
- &#127882; --> 🎊

<!-- Perguntas (SRS):

01. Quais são os padrões de caracteres usados ​​para representar símbolos reservados ou especiais em HTML?

R: Entidades HTML

02. Ao converter um código emoji Unicode (por exemplo, U+1F604) para HTML, qual prefixo deve ser usado?

R: O prefixo &#x. O prefixo &#x é usado para formatos decimais.
-->
