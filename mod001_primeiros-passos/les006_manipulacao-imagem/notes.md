# Direito de Imagem (Creative Commons)

Nem toda imagem que existe na internet **pode ser usada livremente por pessoas alheias**. Alguns exemplos de licenças são:

1. *Licença CC-BY*
   > Atribuindo os créditos à criação original, **você têm permissão para distribuir, remixar e criar por cima da mesma**, inclusive comercialmente.
2. *Licença BY-SA*
    > Atribuindo os créditos à criação original, **você têm permissão para distribuir, remixar e criar por cima da mesma**, inclusive comercialmente, *mas mantenho o mesmo tipo de licença da original*.
3. *Licença BY-ND*
    > Atribuindo os créditos à criação original, **você têm permissão, apenas para reutilizar a obra**, inclusive comercialmente, *mas sem distribuí-la*.
4. *Licença BY-NC*
    > Atribuindo os créditos à criação original, **você têm permissão para distribuir, remixar e criar por cima da mesma**, mas sem usá-la comercialmente.
5. *Licença BY-NC-SA*
   > Atribuindo os créditos à criação original, **você têm permissão para distribuir, remixar e criar por cima da mesma**, mas sem usá-la comercialmente e *mantenho o mesmo tipo de licença da original*.
6. *Licença BY-NC-ND*
   > Atribuindo os créditos à criação original, **você têm permissão, apenas para distribuir a obra**, mas sem usá-la comercialmente.

Alguns sites gratuitos que disponibilizam imagens com direito ao uso comercial: `unsplash.com e pexels.com`

## Formato de Imagens

Os formatos mais utilizados na web são o **JPEG e o PNG**, onde o primeiro **suporta a compactação da imagem** e o segundo **suporta a transparência da imagem**

Outros formatos menos utilizados são: *SVG, GIF e raramente TIF*.

## Tamanho de Imagens

Via de regra temos que **quanto menor o tamanho de armazenamento uma imagem possui, melhor para o site**.

Ou seja, quanto menor a imagem, menor o espaço que ela ocupa no site.

Algumas características especiais:

- Tamanho máximo recomendado para imagens em um site: **1500px de largura**.
- Resolução máxima recomendada (ao manipular a original): **entre 50% a 80%**.
- Qualidade máxima recomendada (ao manipular a original): **entre 70% a 90%**.

## Elemento &lt;img&gt;

Serve para **embutir imagens em documentos**. Requer obrigatoriamente o *atributo `src=""` (origem do arquivo) e o `alt=""` (texto alternativo para acessibilidade)*.

### Arquivo na mesma pasta do arquivo HTML

Nessa situação, basta especificar, no atributo src da tag, o **caminho do arquivo**.

<!-- INFO: Exemplo -->
```html
<img src="imagem.jpg" alt="imagem qualquer">
```

### Arquivo eu uma subpasta da pasta do arquivo HTML

Nessa situação, basta especificar, no atributo src da tag, **o caminho com o nome da subpasta e do arquivo**.

<!-- INFO: Exemplo -->
```html
<img src="subpasta/imagem.jpg" alt="imagem qualquer">
```

### Arquivo eu uma pasta acima da pasta do arquivo HTML

Nessa situação, basta inserir, no atributo src da tag, **"../" e o caminho do arquivo**.

<!-- INFO: Exemplo -->
```html
<img src="../imagem.jpg" alt="imagem qualquer">
```

### Arquivo em uma fonte externa ao arquivo HTML

Nessa situação, basta inserir, no atributo src da tag, o a **url pública do arquivo**.

<!-- INFO: Exemplo -->
```html
<img src="https://site.com/imagens/logo.png" alt="imagem qualquer">
```

## Links para Favicon

Ícone minúsculo exibido em **abas, favoritos e barras de endereços**. São inseridos em um documento HTML através da tag `<link>`.

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

<!-- Perguntas (SRS):01.

01. Por que não é profissional simplesmente copiar e usar qualquer imagem encontrada no Google em um site comercial?

R: Devido a leis de direitos autorais que podem resultar em sanções legais para o desenvolvedor ou cliente.

02. Por que é importante redimensionar imagens para o tamanho exato que aparecerão no site em vez de usar a versão original gigante?

R: Para reduzir o peso do arquivo em bytes, economizar largura de banda e acelerar o carregamento da página.

03. Em relação ao SEO, por que nomes de arquivos como 'foto1.jpg' são evitados?

R: Nomes descritivos ajudam motores de busca a entender o conteúdo da imagem (ex: 'cachorro-correndo.jpg').

04. Qual a principal diferença técnica entre os formatos PNG e JPEG em relação ao fundo da imagem?

R: O formato PNG suporta transparência, enquanto o JPEG não.

05. Qual é a recomendação para o nível de compressão JPEG em sites profissionais para equilibrar qualidade e peso?

R: Entre 70% e 90%.

06. Qual a desvantagem de usar imagens externas (de outros servidores) em seu site?

R: Se o servidor externo cair, a imagem deixará de carregar em seu site.

07. Quais são os formatos de arquivo mais comuns para armazenar um favicon?

R: ICO, PNG e GIF.

08. Qual o tamanho padrão (em pixels) de um favicon comum?

R: 16 x 16 pixels.
-->
