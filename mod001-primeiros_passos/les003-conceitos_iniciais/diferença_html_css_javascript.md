# Como funciona a HTML e as CSS?

Um servidor retorna uma cópia de documentos HTML, CSS e JavaScript através da solicitação cliente-servidor
O navegador analisa as linhas de código e gera um resultado visual (o site em si).

- **Não são** linguagens de programação
- Uma é uma **linguagem de marcação**, outra são **folhas de estilo**
- Não programa e sim **desenvolve**.

## HTML

HyperText Markup Language

Focada em conteúdo, pode ser: **texto, imagem, título, vídeo, listas, tabelas, etc.**

### Conteúdo em HTML

```html
Abertura de tag - Parâmetro - Valor - Conteúdo - Fechamento de tag

<tag src="VALOR">Exemplo de conteúdo</tag>

Exemplo: <h1>Exemplo de título</h1>
Exemplo: <p>Exemplo de parágrafo</p>
Exemplo: <img src="foto.png" alt="Exemplo de foto">
```

OBS: **Nem toda tag possui fechamento.**

### Estrutura básica de documento HTML

```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
        <h1>Olá, Mundo!</h1>
    </body>
<html>
```

## CSS

Cascading Style Sheets

Focada em design. pode ser: **cores, sombras, tamanhos, posicionamento, etc.**

### Estilos em CSS

```css

Seletor - Declaração (propriedade: valor;)

h1 {
    font-family: Arial;
    font-size: 20pt;
    color: blue;
}

```

OBS: **Toda declaração tem ponto e vírgulo no final.**


## JavaScript

Focado em interações, pode ser: **menus, animações, popups, validações, etc.**