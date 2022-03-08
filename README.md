
# Seja bem vindo!

Este é o repositório contendo os códigos fontes das apresentações
preparadas para a oficina de “Análise de dados NIR em ambiente R: Manejo
de dados + pré-processamento + PCA + LDA + PLS”, ministrado de forma
privada a um grupo de estudantes nos dias 30 de junho e 2 de julho de
2021. A oficina é destinada à *comunidade acadêmica* e interessadas(os)
em geral, que **possuam conhecimento básico da linguagem R** e que
**lidem com dados NIR**.

# Carga horária

5 horas e 20 minutos, distribuídos da seguinte maneira:

| Parte    | Duração   | Tema                                        |
|:---------|:----------|:--------------------------------------------|
| Primeira | 1 hora    | Manejo de dados                             |
| Segunda  | Meia hora | Preparo de dados pré-análises               |
| Terceira | Meia hora | Análise de componentes principais (PCA)     |
| Quarta   | 1 hora    | Análise linear discriminante (LDA)          |
| Quinta   | 1 hora    | Análise de mínimos quadrados parciais (PLS) |

Destino uma hora às perguntas durante a oficina, mais 20 minutos de
introdução.

# Programação

| Dia | Temas                                                 |
|----:|:------------------------------------------------------|
|   1 | Manejo de dados + Preparo de dados pré-análises + PCA |
|   2 | LDA + PLS                                             |

# Pré-requisitos

É essencial que os participantes tenham o [R](http://www.r-project.org)
instalado em seus computadores. Vejam o tutorial para instalação do
ambiente R em seus computadores neste arquivo:
<https://github.com/ricoperdiz/minicurso-elaboracao-mapa-R/blob/main/extra-ref/Instrucoes_ROPerdiz_instalando_Baixando_R.pdf>.

Participantes devem saber o mínimo para lidar com dados em ambiente R, o
que inclui saber importar os dados para área de trabalho e ter noções
sobre pasta de trabalho.  
Recomendamos a leitura do livro [Curso básico de introdução à linguagem
R](https://intror.netlify.app) para sanar possíveis dúvidas no
conhecimento básico da linguagem.

É necessário que os participantes possuam os pacotes listados abaixo
instalados em seus computadores para a versão mais recente do R:

``` r
install.packages(c("tidyverse", "caret", "tidymodels", "data.table", "pls"), dependencies = TRUE)
```

# Antes de começar o minicurso - Opcional

Sugiro que instalem o
[RStudio](https://www.rstudio.com/products/rstudio/download/).

# Dados a serem utilizados durante a oficina

Duas opções:

1)  Próprios dados, já formatados para análise OU;

2)  utilizem um conjunto de dados NIR de minha tese disponibilizado no
    pacote `NIRtools` (ver em <https://github.com/ricoperdiz/NIRtools>;
    instruções sobre como utilizar este conjunto serão dadas amanhã). O
    conjunto é muito pequeno e servirá apenas para demonstração dos
    tópicos abordados durante o evento.

# Apresentações

-   Apresentação do dia 01:
    [Slides](https://oficina-dados-nir-dia01.netlify.app) \| [Código
    fonte](https://github.com/ricoperdiz/oficina-dados-nir/blob/main/01_dia1/index.Rmd)  
-   Apresentação do dia 02:
    [Slides](https://oficina-dados-nir-dia02.netlify.app) \| [Código
    fonte](https://github.com/ricoperdiz/oficina-dados-nir/blob/main/02_dia2/index.Rmd)

# Dúvidas, informações adicionais

GitHub: <https://github.com/ricoperdiz>  
Twitter: <https://twitter.com/ricoperdiz>  
Sítio pessoal: <https://www.ricardoperdiz.com>  
Correio eletrônico: <ricardoperdiz@yahoo.com>
