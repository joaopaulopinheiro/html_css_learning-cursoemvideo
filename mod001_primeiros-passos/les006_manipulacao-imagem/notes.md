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

<!-- Perguntas (SRS):

01. Qual é a recomendação principal para evitar problemas jurídicos com direitos autorais ao usar imagens da internet?

Resposta: Utilizar apenas imagens de domínio público ou com autorização (ex: Creative Commons)

02. O que acontece se você definir a largura de uma imagem gigante via CSS em vez de redimensionar o arquivo original?

Resposta: O navegador baixa o arquivo original pesado, prejudicando o tempo de carregamento e o SEO.

03. Analise as afirmações:

I. Imagens muito pesadas prejudicam o tempo de carregamento
II. O Google considera performance como fator de ranking
III. Sites lentos podem perder posições nos resultados de busca

04. Em qual situação o formato PNG é preferível ao JPEG em um projeto web?

Resposta: Quando a imagem possui muitas cores e gradientes

05. A recomendação de compressão JPEG para sites profissionais geralmente fica entre _____ e _____.

Resposta: 70% e 90%

06. Por que nomes de arquivos como "foto1.jpg" são evitados em termos de SEO?

Resposta: Porque nomes descritivos ajudam motores de busca a entender o conteúdo da imagem.

07. Se uma imagem "foto.jpg" está dentro da pasta "midia", o valor correto do atributo src é: _____

Resposta: midia/foto.jpg

08. Quais são os formatos mais comuns para armazenar um favicon?

A) ICO
B) PNG
C) GIF

09. <img src="img123.jpg">

Qual melhoria mais adequada para SEO?

X A) Usar PNG
V B) Renomear para algo descritivo
X C) Diminuir a resolução via CSS
X D) Adicionar mais imagens
-->
