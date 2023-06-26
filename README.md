# FOSS4G-2023-Airflow-Grass-Automation
## Workshop Airflow Grass Automation
<br>

### Repositories
[Airflow Repository](https://github.com/Kan-T-IT/FOSS4G-2023-Airflow)


## GRASS SETUP

### Prerequisites
- Docker installed - lasted version
- Permissions to execute Docker

### Setup
- Image building.
  - For this step, we will pull the image from DockerHub

 ```bash 
docker pull mundialis/grass-py3-pdal:8.2.1-alpine 
```
Note: for MAC jump to Exercise steps

### Download vector data
https://overpass-turbo.eu/s/1wn5

### Exercise steps

[steps to follow](https://github.com/Kan-T-IT/FOSS4G-2023-Airflow-Grass-Automation/blob/main/CHEATSHEET.md)

- Initial Setup
  - Mapset creation
- Importing the data
- Buffering vector
- NDVI
- MASKING
- Exporting



[final dag](https://github.com/Kan-T-IT/FOSS4G-2023-FINAL-DAGS)
