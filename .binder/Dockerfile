FROM rocker/shiny-verse:4.2.1
LABEL maintainer='diogo-almeida'

RUN wget https://github.com/diogo-almeida/shiny-text/raw/main/DESCRIPTION && R -e "options(repos = list(CRAN = 'http://mran.revolutionanalytics.com/snapshot/2022-07-31/')); devtools::install_deps()"

RUN rm DESCRIPTION.1; exit 0