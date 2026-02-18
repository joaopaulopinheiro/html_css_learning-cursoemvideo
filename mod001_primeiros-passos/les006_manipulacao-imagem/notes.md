# Direito de Imagem (Creative Commons)

Nem toda imagem que existe na internet **pode ser usada livremente por pessoas alheias**. Alguns exemplos de licenças são:

1. **CC-BY** -> Atribuindo os créditos à criação original, **você têm permissão para distribuir, remixar e criar por cima da mesma**, inclusive comercialmente.
2. **BY-SA** -> Atribuindo os créditos à criação original, **você têm permissão para distribuir, remixar e criar por cima da mesma**, inclusive comercialmente, *mas mantenho o mesmo tipo de licença da original*.
3. **BY-ND** -> Atribuindo os créditos à criação original, **você têm permissão, apenas para reutilizar a obra**, inclusive comercialmente, *mas sem distribuí-la*.
4. **BY-NC** -> Atribuindo os créditos à criação original, **você têm permissão para distribuir, remixar e criar por cima da mesma**, mas sem usá-la comercialmente.
5. **BY-NC-SA** -> Atribuindo os créditos à criação original, **você têm permissão para distribuir, remixar e criar por cima da mesma**, mas sem usá-la comercialmente e *mantenho o mesmo tipo de licença da original*.
6. **BY-NC-ND** -> Atribuindo os créditos à criação original, **você têm permissão, apenas para distribuir a obra**, mas sem usá-la comercialmente.

Alguns sites gratuitos que disponibilizam imagens com direito ao uso comercial: `unsplash.com e pexels.com`


# Formato de Imagens

Os formatos mais utilizados na web são o **JPEG e o PNG**, onde o primeiro **suporta a compactação da imagem** e o segundo **suporta a transparência da imagem**

Outros formatos menos utilizados são: *SVG, GIF e raramente TIF*.


# Tamanho de Imagens

Via de regra temos que **quanto menor o tamanho de armazenamento uma imagem possui, melhor para o site**.

Ou seja, quanto menor a imagem, menor o espaço que ela ocupa no site.

Algumas características especiais:

- Tamanho máximo recomendado para imagens em um site: **1500px de largura**.
- Resolução máxima recomendada (ao manipular a original): **entre 50% a 80%**.
- Qualidade máxima recomendada (ao manipular a original): **entre 70% a 90%**.


# Elemento &lt;img&gt;

Serve para **embutir imagens em documentos**. Requer obrigatoriamente o *atributo ```src=""``` (origem do arquivo) e o ```alt=""``` (texto alternativo para acessibilidade)*.


> Imagem na MESMA pasta do arquivo HTML [src="arquivo.ext"]

Nessa situação, basta especificar, no atributo src da tag, o **caminho do arquivo**.

<!-- INFO: Exemplo -->
```html
<img src="imagem.jpg" alt="imagem qualquer">
```

> Imagem eu uma SUBPASTA da pasta do arquivo HTML [src="subpasta/arquivo.ext"]

Nessa situação, basta especificar, no atributo src da tag, o caminho com **o nome da subpasta e do arquivo**.

<!-- INFO: Exemplo -->
```html
<img src="subpasta/imagem.jpg" alt="imagem qualquer">
```

> Imagem eu uma pasta ACIMA da pasta do arquivo HTML [src="../arquivo.ext"]

Nessa situação, basta inserir, no atributo src da tag, "../" e o **caminho do arquivo**.

<!-- INFO: Exemplo -->
```html
<img src="../imagem.jpg" alt="imagem qualquer">
```

> Imagem eu um SERVIDOR ou SITE EXTERNO ao arquivo HTML [src="arquivo.ext"]

Nessa situação, basta inserir, no atributo src da tag, o a **url pública do arquivo**.

<!-- INFO: Exemplo -->
```html
<img src="https://site.com/imagens/logo.png" alt="imagem qualquer">
```


# Links para Favicon

Ícone minúsculo exibido em **abas, favoritos e barras de endereços**. São inseridos em um documento HTML através da tag ```<link>```.

<!-- INFO: Exemplo -->
```html
<head>
    ...
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
    <!-- Em href, informe o caminho completo do arquivo -->
    <!-- Os tipos aceitos são: ICO, PNG, GIF, JPEG e SVG. -->
</head>
```

Sites próprios para favicons são: `iconarchive.com, favicon.cc e favicon.io`