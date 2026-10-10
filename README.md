# Site — Dra. Dunia Verona

Site estático em HTML, CSS e JavaScript. O código da página está em `dist/index.html`; os caminhos de fotos, monograma e fontes apontam para `dist/assets/`.

**Estado desta cópia:** o HTML, CSS e JavaScript foram enviados. Os arquivos de fotos, monograma e fontes ainda não foram incluídos. A reprodução visual completa depende desses arquivos.

## Visualizar localmente

Com Python instalado, execute na pasta do projeto:

```sh
python -m http.server 8000 --directory dist
```

Abra http://localhost:8000.

## Editar

Edite `dist/index.html` para atualizar os textos, estilos e interações. Preserve os caminhos relativos das imagens e fontes.

## Publicação

Site atual: https://duniaverona.loftyamber4.chatgpt.site

Este repositório guarda uma cópia do código. Alterações no GitHub não atualizam automaticamente a hospedagem atual. Em outra hospedagem estática, configure `dist` como pasta pública; não é necessário comando de build.

As fotografias e a identidade visual pertencem à marca. Ao incluir as fontes, preserve suas licenças em `dist/assets/fonts/`.
