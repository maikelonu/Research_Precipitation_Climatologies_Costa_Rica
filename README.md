
# CRCLIMprec-TEC

CRCLIMprec is an program intended for the generation of precipitation climatologies using several interpolation methods

## Installation

Use Git to clone and install the program

## Usage

Unzip file collections and execute individual R scripts accordingly

## Contributing

Maikel Mendez Morales. Escuela de Ingeniería en Construcción, Instituto Tecnológico de Costa Rica. email: mamendez@itcr.ac.cr

Luis Alexander Calvo Valverde. Escuela de Ingeniería en Computación, Instituto Tecnológico de Costa Rica. email: lcalvo@itcr.ac.cr

## Publications

# Generation of Monthly Precipitation Climatologies for Costa Rica Using Irregular Rain-Gauge Observational Networks

MDPI - Water Journal

# https://www.mdpi.com/2073-4441/11/1/70

# https://doi.org/10.3390/w11010070

![alt test](/Network.jpeg)

Graphical Abstract

![alt test](/QGIS_PREC.png)

Abstract: 

Precipitation climatologies for the period 1961-1990 were generated for all climatic regions of Costa Rica using an irregular rain-gauge observational network comprised by 416 rain-gauge stations. Two sub-networks were defined; a high temporal resolution sub-network (HTR), including stations having at least 20 years of continuous records during the study period (157 in total); and a high spatial resolution sub-network (HSR), which includes all HTR-stations plus those stations with less than 20 years of continuous records (416 in total). Results from the kriging variance reduction efficiency (KRE) objective function between the two sub-networks, show that ordinary kriging (OK) is unable to fully explain the spatio-temporal variability of precipitation within most climatic regions if only stations from the HTR sub-network are used. Results also suggests that in most cases, it is beneficial to increase the density of the rain-gauge observational network at the expense of temporal fidelity, by including more stations even though their records may not represent the same time step. Thereafter, precipitation climatologies were generated using seven deterministic (IDW, TS2, TS2PARA, TS2LINEAR, TPS, MQS and NN) and two geostatistical (OK and KED) interpolation methods. Performance of the various interpolation methods was evaluated using cross validation technique, selecting the mean absolute error (MAE) and the root-mean square error (RMSE) as agreement metrics. Results suggest that IDW is marginally superior to OK and KED for most climatic regions. The remaining deterministic methods however, considerably deviate from IDW, which suggests that these methods are incapable of properly capturing the true-nature of spatial precipitation patterns over the considered climatic regions. The final generated IDW climatology was then validated against the GPCC, CRU and WorldClim datasets, which overall spatial and temporal coherence is considered satisfactory, giving assurance about the use this new climatology in the development of local climate impact studies.

Results

![alt test](/prec_clim_1961_1990.jpeg)

## License

[MIT](https://choosealicense.com/licenses/mit/)
