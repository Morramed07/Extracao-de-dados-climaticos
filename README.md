# Extracao-de-dados-climaticos

Este projeto extrai dados de precipitação para municípios brasileiros usando a API da NASA POWER e calcula o Índice de Precipitação Padronizado (SPI) em escala trimestral.

🔄 Etapas principais

- 📍 Uso de shapefile do IBGE e cálculo de centróides
- 🌎 Coleta de dados mensais de precipitação (2000–2025)
- 🔗 Integração espacial dos dados
- 📈 Cálculo do SPI com o pacote SPEI
- 🗺️ Geração de mapas temáticos com ggplot2


🎯 Objetivo

- Monitorar padrões de seca e umidade no Brasil ao longo do tempo, permitindo análises climáticas comparáveis entre regiões e períodos.

🌐 Sobre a API NASA POWER

A API da NASA POWER fornece acesso a mais de 350 variáveis climáticas, incluindo:
- temperatura
- umidade relativa
- radiação solar

🔗 Documentação oficial:
https://power.larc.nasa.gov/parameters/
