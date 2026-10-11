# Site — Dra. Dunia Verona

Site estático em HTML, CSS e JavaScript. O código da página está em `dist/index.html`; monograma e fontes estão em `dist/assets/`. As fotografias são carregadas de uma hospedagem externa, por URLs no HTML.

## Visualizar localmente

Com Python instalado, execute na pasta do projeto:

```sh
python -m http.server 8000 --directory dist
```

Abra http://localhost:8000.

## Editar

Edite `dist/index.html` para atualizar os textos, estilos e interações. Preserve os caminhos relativos das imagens e fontes.

## Publicação

Site atual: https://duniaverona.github.io/site-dunia-verona/

Este repositório guarda uma cópia do código. Alterações no GitHub não atualizam automaticamente a hospedagem atual. Em outra hospedagem estática, configure `dist` como pasta pública; não é necessário comando de build.

As fotografias e a identidade visual pertencem à marca. As licenças das fontes estão em `dist/assets/fonts/`.


## Imagens

Os arquivos de fotos foram removidos da versão atual do repositório a pedido da proprietária. O site usa imagens hospedadas fora do GitHub; mantenha as URLs externas ao editar. As versões antigas do histórico Git ainda podem conter fotografias.
