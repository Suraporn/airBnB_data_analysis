# Airbnb Data Analysis Project
This project aims to predict popularity of Airbnb listing.

A regression problem of predicting reviews_per_month, as a proxy for the popularity of the listing with [New York City Airbnb listings from 2019 dataset](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data). Airbnb could use this sort of model to predict how popular future listings might be before they are posted, perhaps to help guide hosts create more appealing listings. In reality they might instead use something like vacancy rate or average rating as their target, but we do not have that available here.


## Usage
To replicate the analysis, clone this GitHub repository to your local:
```
git clone https://github.com/Suraporn/airbnb_data_analysis.git
```

Navigate to your local repository and prompt the command line and run:
```
conda env create --file airbnb_env.yaml
```
The new environment energy_project will be created in your conda environment, and we will use this as the main environment to run the analysis.

Activate the new environment by:
```
conda activate airbnb_env
```

## License
`airbnb_data_analysis` is licensed under the terms of the MIT license.

Please refer to the License File [here](https://github.com/Suraporn/airbnb_data_analysis/blob/main/LICENSE)