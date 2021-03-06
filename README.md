
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Ibamam

<!-- badges: start -->

<!-- badges: end -->

O objetivo deste pacote é disponibilizar a base de dados sobre multas e
autuações ambientais do Instituto Brasileiro do Meio Ambiente e dos
Recursos Naturais Renováveis (IBAMA).

Os dados foram obtidos no [Portal Brasileiro de Dados
Abertos](https://dados.gov.br/) no repositóio do
[IBAMA](https://dados.gov.br/organization/instituto-brasileiro-do-meio-ambiente-e-dos-recursos-naturais-renovaveis-ibama).

<!-- > __Caso você não utilize R__, é possível __fazer download da base de dados__ através [deste link](https://github.com/beatrizmilz/mananciais/raw/master/inst/extdata/mananciais.csv).  -->

Caso você queira utilizar a base mais atual, sem que seja necessário
instalar o pacote, recomendo que utilize o seguinte código:

## Como instalar?

Este pacote pode ser instalado através do [GitHub](https://github.com/)
utilizando o seguinte código em `R`:

``` r
# install.packages("devtools")
devtools::install_github("cccneto/Ibamam")
library(Ibamam)
```

## Como usar?

Existem dois arquivos disponíveis, em que a diferença é o período dos
dados. Caso você não utilize `R` e queira ter acesso aos dados em
formato `.csv`, os mesmos podem ser acessados através dos links a
seguir. Lembrete: o arquivo foi salvo em formato “separado por ponto e
vírgula”, e com encoding “UTF-8”.

Abaixo segue um exemplo das bases disponíveis:

``` r
# dplyr::glimpse(multas)
```

Caso queira saber o significado de cada variável, leia a [documentação
da base de dados]():

### Exemplo de tabela

``` r
# library(magrittr)
# multas %>% 
#   dplyr::arrange(desc(ValorAuto)) %>% 
#   head(7) %>%
#   knitr::kable()
```

## Como citar o pacote
