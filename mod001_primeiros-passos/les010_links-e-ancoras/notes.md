# Links e Âncoras

Permite _ligar documentos entre si_ e navegar pela web. Pode apontar para **páginas, arquivos, e-mails ou locais no mesmo documento**.

## Elemento &lt;a&gt;

É usado para _criar hiperlinks_ e refere-se ao **ponto clicável que estabelece a ligação** entre diferentes conteúdos na rede.

> `href=""`

Define a **referência de hipertexto ou a URL de destino** para onde o usuário será enviado ao clicar.

> `hreflang=""`

Serve para **indicar o idioma principal** do documento vinculado.

> `target=""`

Controla **onde o link será aberto**. O valor `_self` abre na mesma aba (padrão), enquanto `_blank` abre o destino em _uma nova janela ou aba_ do navegador.

> `rel=""`

Define a **relação entre o documento atual e o destino do link**. Exemplos incluem `external` para sites de terceiros, `next/prev` para navegação sequencial e `nofollow` para links não endossados.

### Links para Downloads

> `download=""`

Atributo que sinaliza ao navegador para **baixar o arquivo vinculado em vez de apenas exibi-lo**.

> `type=""`

Informa ao navegador **a natureza do arquivo que está sendo acessado ou baixado**. Como exemplos de valores temos _application/pdf_ ou _audio/mpeg_.

No site `iana.org`, tem todos os mediatypes compatíveis.

<!-- INFO: Exemplo -->
```html
<a href="caminho/arquivo.pdf" download="nome-do-arquivo.pdf" type="application/pdf">Link baixável</a>
```

<!-- Perguntas (SRS)

01. Em uma estrutura de pastas em um servidor Linux, o que os símbolos ../ representam quando usados no atributo href?

Resposta: Indicam subir um nível na hierarquia de pastas.

02. Qual é a utilidade do atributo hreflang em uma âncora

Resposta: Indicar o idioma do documento de destino.

03. Verdadeiro ou Falso: O atributo target="_self" é o comportamento padrão das âncoras no HTML.

Resposta: Verdadeiro

04. Complete a lacuna: Ao organizar um site, o link para a próxima página de um artigo deve conter o atributo rel="________" por questões de semântica.

Resposta: next

05. Ao configurar um link externo para abrir em nova aba e indicar sua natureza, qual combinação é recomendada?

B) target="_blank" e rel="external"
C) target="_blank" e rel="noopener noreferrer"

06. Complete a lacuna: Os Media Types como application/pdf devem ser aplicados no atributo ______ da tag <a>.

Resposta: type

07. Para que um link de download funcione corretamente e informe o tipo de arquivo, quais atributos devem ser usados?

Resposta: download e type="application/pdf"
-->
