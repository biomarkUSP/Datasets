# Datasets

## Descrição

Reune datasets a serem usados para mapeamento genético e outros estudos de estatística genômica.
Os arquivos *mouse.csv* e *maize.csv* foram disponibilizados pelo Prof. Antônio Augusto F. Garcia (ESALQ/USP) na disciplina de pós-graduação "Biometria de Marcadores Genéticos"

Os arquivos *pheno.csv*, *geno.csv*,*map.csv* foram disponibilizados pelo Prof. Roberto Fritsche Neto (ESALQ/USP) na disciplina de pós-graduação "Melhoramento de Plantas Alógamas"

Os datasets foram construídos pelos autores e aqui disponibilizados por nós para fins didáticos.

## Usage

```R
#' Importando arquivo mouse.csv
#'------------------------------------------------------------------------------------------------------------------------
mouse = read.csv(https://raw.githubusercontent.com/biomarkUSP/Datasets/master/mouse.csv,header=T)

#' importandoo um arquivo generico desta base:
#'------------------------------------------------------------------------------------------------------------------------
nomeoarquivo = "mouse" # para mouse
file = read.csv(paste("https://raw.githubusercontent.com/biomarkUSP/Datasets/master/",nomeoarquivo,".csv",sep=""),header=T)

nomeoarquivo = "map" # para map
file = read.csv(paste("https://raw.githubusercontent.com/biomarkUSP/Datasets/master/",nomeoarquivo,".csv",sep=""),header=T)

```

## Contato

Autor do Banco de dados:

**Germano Martins F. Costa Neto** <germano.cneto@usp.br>

Eng. Agr., Me. Genética em Melhoramento de Plantas

Doutorando em Genética e Melhoramento de Plantas - ESALQ/USP

Laboratório de Melhoramento de Plantas Alógamas <http://www.genetica.esalq.usp.br/alogamas>

## Contato dos professores

Para maiores informações sobre os datasets, assim como as políticas de uso dos mesmos, por favor contacte os professores:

Prof. Antônio Augusto F. Garcia (ESALQ/USP) <augusto.garcia@usp.br>

Prof. Roberto Fritsche Neto (ESALQ/USP) <roberto.neto@usp.br>
