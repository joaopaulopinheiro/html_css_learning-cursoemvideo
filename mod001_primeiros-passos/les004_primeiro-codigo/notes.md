# Tags Iniciais HTML

## Declaração !DOCTYPE

**Informa ao navegador qual é a versão do HTML que está sendo utilizada.** Ele ajuda o navegador a interpretar corretamente o código e garantir que a página seja exibida da maneira esperada.

```html
<!DOCTYPE html> 
Informa que a versão utilizada é a versão HTML5.
```

## Elemento < html >

É a raiz de um documento HTML. **Todos os outros elementos devem ser seus descendentes** e o atributo lang é vital para acessibilidade.

```html
<!DOCTYPE html> 
<html lang="pt-br">
    Todo os outros elementos vêm aqui dentro.
<html>
```

## Elemento < head >

Contém informações de **metadados para máquinas, como título e estilos**. Ele deve ser o primeiro filho de html e existe apenas um em cada documento web.

```html
<!DOCTYPE html> 
<html lang="pt-br">
    <head>
        Conteúdo não visível pelo usuário.
    </head>
<html>
```

### Elemento < meta >

Fornece metadados **não cobertos por outros elementos, como codificação de caracteres**, viewport para dispositivos móveis ou descrições para buscas web.

> charset="UTF-8"

Define a codificação de caracteres. O padrão UTF-8 é essencial para **garantir que acentos e caracteres especiais de diversos idiomas sejam exibidos** corretamente.

> name="viewport" content="width=device-width, initial-scale=1.0"

Fornece instruções ao navegador sobre **como ajustar as dimensões e a escala da página**, sendo crucial para o design responsivo em dispositivos móveis.

```html
<!DOCTYPE html> 
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
<html>
```

### Elemento < title >

Define **o nome do documento exibido na barra ou aba do navegador**. É fundamental para SEO e ajuda usuários a identificar a página em seus favoritos.

## Elemento < body >

Representa **o conteúdo principal que é visível ao usuário**. Pode existir apenas um elemento body por página e ele deve ser o segundo filho de um html.

```html
<!DOCTYPE html>
<html lang="pt-br">
    ...
    <body>
        Conteúdo visível pelo usuário.
    </body>
<html>
```

### Elemento < h1-h6 > (Heading)

Representam **seis níveis hierárquicos de títulos de seções**, onde h1 é o mais importante. Ajudam leitores de tela a construir sumários das páginas web.

### Elemento < hr >

Define uma quebra temática entre parágrafos, **geralmente exibida como uma linha horizontal**. Serve para separar tópicos distintos dentro de uma seção.

### Elemento < p >

Usado para **definir parágrafos de texto**. Organizar o conteúdo em parágrafos torna a leitura mais acessível para todos os usuários.