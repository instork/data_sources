# Data Sources

## Prerequisites

 - make conda environment
```bash
$ make env                  # create anaconda environment
$ conda activate <new_env>  # activate anaconda environment
$ make setup                # initial setup for the project
# add jupyter notebook kernel
$ python -m ipykernel install --user --name <new_env> --display-name <display_name> 
```

- .env file
```
UPBIT_ACCESS = <YOUR_API_KEY>
UPBIT_SEKRET = <YOUR_API_KEY>
POLYGON_API = <YOUR_API_KEY>
```

