# Jurebaba

[![balena deploy button](https://www.balena.io/deploy.svg)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://gitlab.com/coletivo-coolab/jurebaba)

A digital territory by and for local communities. Members of Community-Networks should have a say on the content they access and share with each other. Jurubeba provides a media server (Jellyfin), a Youtube downloader (MeTube), a file browser, a proxy manager with GUI and a community portal fully editable thru a web code editor using Markdown.

------------

Um território digital feito por e para redes comnunitárias. Membros da comunidade deveriam controlar o conteúdo que acessam e compartilham uns com os outros. Jurubeba cria um servidor de mídias, uma interface para salvar mídias de plataformas como Youtube, um explorador de arquivos, uma interface para gerenciar os domínios da rede local e um portal comunitário totalmente editável através de um editor de códigos e Markdown.

![JURUBEBA](jurubeba-logo.png)

Enxertando serviços.

# Serviços
## Gerente de domínios

Usamos o [Nginx Proxy Manager](https://nginxproxymanager.com/) para gerenciar os serviços e domínios da rede por uma interface.
## Portal Comunitário

Um portal totalmente editável para incentivar membros das comunidades a explorar as entranhas do código. Expomos o código usando um [editor online](https://github.com/cdr/code-server). O conteúdo pode ser facilmente editado usando [Markdown](https://github.com/zander-br/markdown-course), mas também todo o resto.

Veja uma [versão demo aqui](https://portal.coolab.org/).

## Crie um acervo de vídeos e músicas

Usamos o [MeTube](https://github.com/alexta69/metube) para baixar de plataformas como Youtube, e o servidor de mídias [Jellyfin](https://jellyfin.org/) para exibir o conteúdo gerenciar as bibliotecas. Todo o conteúdo pode ser movido como em uma pasta local do computador usand o 
serviços [Filebrowser](https://github.com/filebrowser/filebrowser).

## TODO:
- Adicionar extensões ao editor de código:
    - ms-ceintl.vscode-language-pack-pt-br
    - liuji-jim.vue
    - austenc.tailwind-docs
    - bradlc.vscode-tailwindcss
    - titiaiev.vue-docs

- Adicionar config padrão Nginx manager
- 