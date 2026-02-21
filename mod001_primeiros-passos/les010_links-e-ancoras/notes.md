# Links e Âncoras

Permite *ligar documentos entre si* e navegar pela web. Pode apontar para **páginas, arquivos, e-mails ou locais no mesmo documento**.

## Elemento &lt;a&gt;

É usado para *criar hiperlinks* e refere-se ao **ponto clicável que estabelece a ligação** entre diferentes conteúdos na rede.

```href=""```

> Define a referência de hipertexto ou a URL de destino para onde o usuário será enviado ao clicar.

```hreflang=""```

> Serve para indicar o idioma principal do documento vinculado.

```target=""```

> Controla onde o link será aberto. O valor _self abre na mesma aba (padrão), enquanto _blank abre o destino em uma nova janela ou aba do navegador.


```rel=""```

> Define a relação entre o documento atual e o destino do link. Exemplos incluem external para sites de terceiros, next/prev para navegação sequencial e nofollow para links não endossados.


### Links para Downloads

```download=""```

> Atributo que sinaliza ao navegador para baixar o arquivo vinculado em vez de apenas exibi-lo. 

```type=""```

> Informa ao navegador a natureza do arquivo que está sendo acessado ou baixado. Como exemplos de valores temos application/pdf ou audio/mpeg.

No site `iana.org`, tem todos os mediatypes compatíveis.

<!-- INFO: Exemplo -->

```html
<a href="caminho/arquivo.pdf" download="nome-do-arquivo.pdf" type="application/pdf">
```