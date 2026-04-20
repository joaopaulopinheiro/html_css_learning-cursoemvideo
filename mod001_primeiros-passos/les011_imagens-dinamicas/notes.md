# Trabalhando com Mídias

## Imagens Dinâmicas

Tratam-se de imagens que se _adaptam automaticamente ao tamanho da tela do dispositivo do usuário_ para garantir performance e economia de dados. Isso evita que o site fique pesado e prejudique a experiência de navegação ou o ranqueamento no Google.

### Elemento &lt;picture&gt;

É uma tag contêiner que agrupa **diferentes versões de uma imagem**, permitindo que o navegador escolha a mais adequada para cada cenário.

### Elemento &lt;source&gt;

Define as diferentes opções de arquivos de mídia e suas condições de exibição dentro dos elementos `<picture>`, `<audio>` ou `<video>`.

> `media=`

Atributo que define a **condição de tela** (como largura máxima ou mínima) necessária para que aquele arquivo específico seja carregado.

> `srcset=`

Define o **caminho da fonte** de imagem que deve ser exibida quando a regra de mídia correspondente for atendida.

## Áudios

### Elemento &lt;audio&gt;

Tag do HTML5 que permite a reprodução nativa de sons e músicas sem a necessidade de plugins ou scripts complexos.

> `controls`

Ativa a exibição da interface do player, permitindo que o usuário visualize botões de play, pause e volume.

> `autoplay`

Faz com que a mídia sonora inicie a reprodução **automaticamente** assim que a página termina de carregar.

> `loop`

Determina que o arquivo de áudio deve ser reiniciado imediatamente após o seu término, repetindo-se infinitamente.

> `preload=`
Configura o carregamento prévio do áudio, podendo baixar apenas os **metadados** (como duração), o arquivo completo ou nada.

### Formatos de Áudio

Os formatos recomendados para máxima compatibilidade entre navegadores são **MP3 (mpeg)**, **OGG** e **WAV**.

## Vídeos

### Elemento &lt;video&gt;

É o contêiner utilizado para inserir vídeos hospedados diretamente no próprio servidor do site.

> `poster=`

Atributo que define uma **capa ou imagem estática** para ser exibida enquanto o vídeo ainda não foi iniciado pelo usuário.

### Elemento &lt;iframe&gt;

Utilizado para **incorporar vídeos de serviços externos**, como YouTube ou Vimeo, economizando tráfego de dados e largura de banda do seu próprio servidor.

### Formatos de Vídeo

Para garantir que o vídeo seja reproduzido em qualquer navegador moderno, deve-se disponibilizar os formatos **MP4 ou M4V**, **WebM** e **OGG**.
