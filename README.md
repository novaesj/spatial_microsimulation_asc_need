# spatial_microsimulation_asc_need

Spatial microsimulation using data from the English Longitudinal Study of Ageing (ELSA) to estimate adult social care (ASC) need among people aged 65 and over in local authorities in England.


## Repository structure

    data/
      raw/                      # Census and ELSA data 
      imputed_elsa/             # imputed ELSA files
      synthetic_populations/    # IPF outputs, one folder per constraint specification 
    analysis/                  # analysis notebooks
    spatial_microsimulation/   # spatial microsimulation setup
    data prearation/           # data transformation for ELSA and Census data
    README.md

## Data access

ELSA microdata cannot be redistributed. It can be obtained from the UK Data Service (https://ukdataservice.ac.uk/) under the relevant licence conditions. Census constraint tables are available from the Office for National Statistics / Nomis (https://www.nomisweb.co.uk/).
