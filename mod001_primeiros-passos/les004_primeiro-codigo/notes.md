# Tags Iniciais HTML

## Declaração !DOCTYPE

**Informa ao navegador qual é a versão do HTML que está sendo utilizada.** Ele ajuda o navegador a interpretar corretamente o código e garantir que a página seja exibida da maneira esperada.

```html
<!DOCTYPE html> <!-- Informa que a versão utilizada é a versão HTML5. -->
```

## Elemento < html >

É a raiz de um documento HTML. **Todos os outros elementos devem ser seus descendentes** e o atributo lang informa a linguagem padrão da página.

```html
<!DOCTYPE html>
<html lang="pt-br">
  <!-- Todo os outros elementos vêm aqui dentro. -->
</html>
```

## Elemento < head >

Contém informações de **metadados para máquinas, como título e estilos**. Ele deve ser o primeiro filho de html e existe apenas um em cada documento web.

```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <!-- Conteúdo não visível pelo usuário. -->
  </head>
</html>
```

### Elemento < meta >

Fornece metadados não cobertos por outros elementos, como **codificação de caracteres, viewport para dispositivos móveis ou descrições para buscas web.**

> `charset="UTF-8"`

Define a codificação de caracteres. O padrão UTF-8 é essencial para **garantir que acentos e caracteres especiais de diversos idiomas sejam exibidos** corretamente.

> `name="viewport" content="width=device-width, initial-scale=1.0"`

Fornece instruções ao navegador sobre **como ajustar as dimensões e a escala da página**.

### Elemento < title >

Define **o nome do documento exibido na barra ou aba do navegador**. É fundamental para SEO e ajuda usuários a identificar a página em seus favoritos.

## Elemento < body >

Representa **o conteúdo principal que é visível ao usuário**. Pode existir apenas um elemento body por página e ele deve ser o segundo filho de um html.

```html
<!DOCTYPE html>
<html lang="pt-br">
  ...
  <body>
    <!-- Conteúdo visível pelo usuário. -->
  </body>
</html>
```

### Elemento < h1-h6 >

Representa **seis níveis hierárquicos de títulos de seções**, onde h1 é o mais importante e de maior hierarquia.

### Elemento < hr >

Define uma quebra temática entre parágrafos, **geralmente exibida como uma linha horizontal**.

### Elemento < p >

Usado para **definir parágrafos de texto**. Organizar o conteúdo em parágrafos torna a leitura mais acessível para todos os usuários.

<!-- Perguntas (SRS)

01. A meta tag com o atributo charset="utf-8" serve para garantir a correta __________ dos caracteres, incluindo acentos e símbolos especiais.

Resposta: codificaçã
-->
