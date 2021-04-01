# raynMan (Need a project name, up for discussion!)

Using big data to predict daily Australian rainfall!

## Project Goals

Our goal is to develop and deploy cloud-based ensemble machine learning models to predict daily Australian rainfall. The data we are using consists of modelled and observed daily rainfall data over NSW, Australia between the years 1889 to 2014, [originally accessed from the figshare platform](https://figshare.com/articles/dataset/Daily_rainfall_over_NSW_Australia/14096681). The modelled data has been kindly provided by [CMIP6](https://www.wcrp-climate.org/wgcm-cmip/wgcm-cmip6), an international collaboration of climate model outputs from different groups around the world. We will be gathering, processing, and deploying the consolidated outputs of separate climate models into a big data machine learning application predicting future target rainfall measurements. The final model will be deployed for others to use in their own analyses!

## Usage

- Clone the GitHub repository
- From project root directory, navigate to notebooks folder and open rainfall_analysis.ipynb
- Click on the `Run` menu and then click on `Run All Cells`

## Dependencies

```
* R
* Python
* pandas
* rpy2
* dask
* pyarrow
* dplyr
```
> Please note that this notebook is resource intensive and may not run on some machines

## Contributors

Group 6 Members:
* Kangbo Lu - @KangboLu
* Craig McLaughlin - @cmmclaug
* Debananda Sarkar - @debanandasarkar
* Kevin Shahnazari - @kshahnazari1998

## Attributions

MDS DSCI 525 Instructor Gittu George - @ggeorg02
Data compiled by MDS Instructor Tom Beuzen - @tbeuzen

Modelled data provided by CMIP6: https://www.wcrp-climate.org/wgcm-cmip/wgcm-cmip6
Data is supported by the Pangeo project: https://pangeo-data.github.io/pangeo-cmip6-cloud/
Observed data is supplied by the Australian SILO database: https://www.longpaddock.qld.gov.au/silo/
