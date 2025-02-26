# Rygrass25

Raigrass yield prediction in kg MS/ha using 3 locations (NW Spain), 5 cultivars, and metereological data (Tmax(ºC), Tmin(ºC), Precipitation(mm), Radiation())
+ Original data. https://github.com/sgcortes/Raigras25/blob/94a68811733fd7458501676892170c30e4178216/DatosmodeloRaigrasfinalv10-yield.xlsx
+ Base model Gradient Boost Regressor (Kfold=5). https://github.com/sgcortes/Raigras25/blob/fceae48fc1c00e57ac0d8d675239c464827152f7/25_2_GBR_SIN_AGUA_SIN_ALTITUD.ipynb
+ Gradient Boost Regressor training code. Kfold=5, Labelencoder,Hyperparameters tuning (Optuna). https://github.com/sgcortes/Raigras25/blob/68f0e8f941d38a9aef9d3c4fe7a763595d04245d/Optuna_250225_GBR_NO_AGUA_NO_ALTITUD_HIPERPRAMETROS.ipynb
+ Sensitivity analysis of Raigrass yield under predcitor variable change for each location and cultivar. https://github.com/sgcortes/Raigras25/blob/503cbb56407c74691a214112d546d9dd2abd13c9/250225_SENSIBILIDAD_EXCEL_FIGURAS.ipynb
+ Optimal trained GBR model *.pckl file (fine tuned with Optuna). https://github.com/sgcortes/Raigras25/blob/6cc84a8570b93207c1f64cc3f99dcdde250f89c7/gradient_boosting_optuna.pkl

+ Deprecated GBR training. https://github.com/sgcortes/Raigras25/blob/6cc84a8570b93207c1f64cc3f99dcdde250f89c7/25_2_GBR_SIN_AGUA_SIN_ALTITUD.ipynb
   
