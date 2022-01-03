# AFS and deforestation: analysis via propensity score matching for Amazon and Cerrado

## About

<div align="justify">From 2006 to 2017, the Agroforestry Systems (AFS) increased around 2.2 million hectares on municipalities of States that comprehend the Amazon and Cerrado biomes,
based in the Rural Census from *Instituto Brasileiro de Geografia e Estatística* (IBGE). As the AFS integrate the forest to crop and animal production 
and sometimes are strategic tools in public policies to recover deforested areas, in this project I evaluate the effects of the AFS expansion
on Brazilian municipalities located in the Amazon and Cerrado biomes.</div>

<div align="justify">For this purpose, I use the Propensity Score Matching (PSM) to compare municipalities that present AFS expansion and municipalities that do not 
present AFS expansion between the years 2006 and 2017. The objective is to estimate the average treatment effect on treated (ATT) by deforestation values from 2017 to 2019, 
which are standardized by deforestation in kilometer square per municipality in years from 2008 to 2019. The hypothesis is that AFS expansion reduced the deforestation by increase of
agricultural productivity, recovery of degraded land or fixation of the rural producer on land.</div>

Lastly, this project is based on my Master's thesis (available only in Portuguese) and you can check it [here](https://www.prppg.ufpr.br/siga/visitante/trabalhoConclusaoWS?idpessoal=117872&idprograma=40001016024P0&anobase=2021&idtc=104) for more details.

## Methodology

- Propensity Score Matching(PSM)

## Technology

- RStudio (R Programming Language)

## Libraries

- cobalt
- ggplot2
- MatchIt
- readxl

## Source

The dataset was extracted in the sources below:

- [IBGE](https://sidra.ibge.gov.br/pesquisa/censo-agropecuario/censo-agropecuario-2017)
- [INPE](http://terrabrasilis.dpi.inpe.br/app/dashboard/deforestation/biomes/legal_amazon/rates)

##

Developed by [Thiago Balbo](https://github.com/ThiagoBalbo16)



