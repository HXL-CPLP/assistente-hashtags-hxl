# Assistente para escolha de hashtags HXL (em português)

> Sistema especialista em português para seleção de hashtags HXL. Usa script python para gerar página HTML estática usando uma base de conhecimentos sobre o Padrão HXL que está [encodada em formato JSON](hxl-knowledge-base.json).

[![Standard HXL](https://img.shields.io/badge/Standard-HXL-%23F26459)](https://hxlstandard.org/)
![GitHub](https://img.shields.io/github/license/HXL-CPLP/assistente-hashtags-hxl)
[![Site](https://img.shields.io/badge/Site-hxl.etica.ai%2Fassistente--hashtags--hxl-blue)](https://hxl.etica.ai/assistente-hashtags-hxl)
[![GitHub stars](https://img.shields.io/github/stars/HXL-CPLP/assistente-hashtags-hxl?style=social)](https://github.com/HXL-CPLP/assistente-hashtags-hxl/)

[![Grupo de Usuários do Padrão HXL da Comunidade dos Países de Língua Portuguesa](https://hxl.etica.ai/img/banner-hxl-cplp.png)](https://padrao-hxl.etica.ai/)


**Para acessar o assistente: <https://hxl.etica.ai/assistente-hashtags-hxl/>.**

Para acessar a discussão inicial: <https://github.com/HXL-CPLP/forum/issues/4>.

## Sobre o HXL

A **Linguagem de Intercâmbio Humanitária** (em inglês: [_Humanitarian Exchange
Language_](https://hxlstandard.org/), **HXL**) é um padrão simples baseado em
hashtag que os respondedores de crises humanitárias podem usar para adicionar
informações interoperáveis a planilhas e dados similares.

O HTML gerado por esse repositório é atua como um
[sistema especialista](https://pt.wikipedia.org/wiki/Sistema_especialista) que
ajuda pessoas que trabalham como Gestores de Informação a escolher
hashtags mais precisas e interoperáveis.

A versão mais atualizada pode ser acessada em <https://hxl.etica.ai/assistente-hashtags-hxl/>.

### Versão original em inglês

O repositório do qual este projeto é um hard fork está em
<https://github.com/HXLStandard/hxl-hashtag-chooser>.

O acesso do resultado da versão em inglês pode ser acessada em
<https://hxlstandard.github.io/hxl-hashtag-chooser/index.html>.


## Uso
Para gerar o HTML que está na pasta [docs/](docs/index.html) pode usar o
Makefile fornecido:

    $ make

Para gerar o HTML diretamente:

    $ python gen-chooser.py > docs/index.html
    $ cp style.css docs/style.css
    
# Knowledge base
The knowledge base for the chooser is in the file hxl-knowledge-base.json. Instructions on updating it will come soon.

# Aviso Legal
Tanto o site <https://padrao-hxl.etica.ai> como a organização no GitHub
<https://github.com/HXL-CPLP> e seus projetos são realizações voluntárias do
**Grupo de Usuários do Padrão HXL da Comunidade dos Países de Língua
Portuguesa** e, ainda que possa haver colaboração ou uso de conteúdo,
**não somos afiliados ou endossados por HXLStandard.org, OCHA, IFRC e afins**.

# License
This script and the HXL knowledge base are released into the Public Domain. Use with good cheer.
