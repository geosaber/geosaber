---
title: QGIS 3.0 e Whitebox GAT
category: General
feature_image: "https://github.com/geosaber/r4geo/raw/gh-pages/img/osm_bkground.png"
---
# *WhiteBox for Processing*
## Integra ferramentas do Whitebox Tools no framework de Processamento do QGIS.
O Whitebox Tools é um avançado mecanismo de análise de dados geoespaciais desenvolvido no Grupo de Pesquisa de Geomorfometria e Hidrogeomática da Universidade de Guelph. As Ferramentas do Whitebox podem ser usadas para executar operações de análise de sistemas de informações geográficas (GIS) comuns, como análise de custo-distância, buffer de distância, reclassificação de rasterização e muito mais.
[![WhiteBoxTools](https://github.com/geosaber/r4geo/raw/gh-pages/img/whitebox-settings.png)](https://plugins.bruy.me/processing-whitebox.html)

## *WhiteboxTools library*
![WhiteboxTools](https://github.com/geosaber/r4geo/raw/gh-pages/img/whiteboxtoolslogoblue.png)
---
>***WhiteboxTools*** é um mecanismo avançado de análise de dados geoespaciais.
A biblioteca foi desenvolvida usando a linguagem de programação *Rust*, uma linguagem de sistemas de alto desempenho e segura, muitas vezes visto como um substituto moderno para C/C++.
Embora *WhiteboxTools* é destinado a servir como uma fonte de ferramentas plugin para o projeto ***Whitebox GAT Open-Source GIS***, as ferramentas contidas na biblioteca são autônomas e podem ser executadas fora do projeto maior **Whitebox GAT**.
Houve um grande número de solicitações para chamar as ferramentas do *Whitebox GAT* e funcionalidades de fora da interface do **Whitebox** (por exemplo, a partir de *scripts* de automação ***Python***).
Eventualmente, a maioria das aproximadamente 400 ferramentas contidas dentro do *Whitebox GAT* será portado para *WhiteboxTools*.
Além de separar as capacidades de processamento e a interface do usuário (e assim reduzir a dependência de Java), essa migração deve melhorar significativamente a eficiência de processamento.
Isso porque a ***Rust*** é geralmente mais rápida do que o código Java equivalente e porque muitas das funções do *WhiteboxTools* são projetados para processar dados em paralelo sempre que possível.

## Referências:

- [WhiteboxTools library](https://whiteboxgeospatial.wordpress.com/2017/07/10/announcing-the-whiteboxtools-library)

- [**WhiteBox for QGIS Processing**](https://plugins.bruy.me/processing-whitebox.html)

- [***Whitebox Geospatial Analysis Tools - GAT***](http://www.uoguelph.ca/~hydrogeo/Whitebox)

- [**Whitebox Tools**](https://github.com/jblindsay/whitebox-tools)

- [*WhiteboxTools User Manual*](https://jblindsay.github.io/wbt_book)

- [*WhiteboxTools R Frontend*](https://github.com/giswqs/whiteboxR)

- [*Prof. John Lindsay's Resources*](https://jblindsay.github.io)
