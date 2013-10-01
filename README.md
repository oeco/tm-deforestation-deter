## Deforestation by INPE DETER/PRODES

TileMill project of deforestation map available at infoamazonia.org, using data provided by INPE DETER and PRODES.

### Datasources

INPE DETER:

http://www.obt.inpe.br/deter/dados

INPE PRODES:

http://www.dpi.inpe.br/prodesdigital/dadosn/2012

### Installing the project locally

1. Clone this repository at TileMill projects diretory:

    cd ~/Documents/Mapbox/project
    git clone git@github.com:oeco/tm-deforestation-deter.git

### Map data

To generate map data, you need Python, Spatialite and wget.

Run:

    ./generate

Unfortunatelly, PRODES data can't be stored at GitHub, so loading a PostgreSQL dump is needed.