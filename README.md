# Faixas de Pedestres

Este repositório é destinado ao estudo para o desenvolvimento de uma técnica de detecção de faixas de pedestre a partir de levantamentos obtidos por sensoriamento remoto e aprendizado de máquina.

## Motivação

O GeoSampa disponibilizou Aero fotos e um levantamento LiDAR e desde então gostaríamos de fomentar seu uso com processamentos de deteção e classificação. Por um outro lado poderia ser interessante ter espacializado as faixas de pedestres desenhadas na cidade. Pensando nisso pretendemos usar esse repositório para concentrar nosso aprendizado e processamentos realizados. Também para receber contribuições e colaboração.

## Metodologia

A princípio vamos utilizar metodologias de classificação supervisionada com aprendizado de máquina para detectar, a partir das aerofotos e levantamento LiDAR as faixas de pedestre da cidade de São Paulo, mas para isso precisamos de ajuda humana :) 

## Como contribuir?

Como se trata de aprendizado de máquina, precisamos ensinar o algorítimo indicando as *Lições de aprendizado*. Portanto se você tem alguma experiência em Geoprocessamento e quiser contribuir é muito fácil, basta desenhar as faixas que vc localizar a partir das Ortofotos disponibilizadas no GeoSampa.

Criamos aqui um passo-a-passo:

1. Você deve possuir um software de GeoProcessamento instalado. Recomendamos que use o QGis, que é livre, de código aberto e mandido por uma comunidade de programadores.
2. Agora é necessário habilitar o serviço de imagens de aerofotos do GeoSampa. Isso mesmo, o GeoSampa não é só um site é uma estrutura de dados e serviços.
3. Lembre-se de que utilizamos o sistema de coordenadas SIRGAS 2000, assim como costumamos projetar nossas visualizações;
4. Agora é hora de desenhar as feições, tenha atenção para desenhar um polígono somente em cima de faixas de pedestres, livres de pedestre, vegetação ou em pior dos casos veículos. Você pode e deve desenhar o polígono onde tiver sombra, ou com radiação solar. Isso pode fazer bastante diferença na classificação.
5. Procure regiões em locais que vc conheça, mesmo aquelas em que a faixa já está meio apagadinha.
6. Agora é hora de salvar o arquivo, preferimos que utilize GeoJson.
7. E por fim vc deve compartilhar sua colaboação aqui no GitHub.

