# Data Sources

## API 특징
- pyubit 라이브러리
    - 주문 / 조회 / 잔고 확인 등 가능
    - 조회: 600 calls / min
    - 주문: 200 calls / min
    - API KEY 필요
- upbit API
    - 주문 / 조회 / 잔고 확인 등 가능
    - 조회: 900 calls / min
    - 주문: 200 calls / min
    - API KEY 필요



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
EODHD_API_KEY = EODHD_API_KEY
UPBIT_ACCESS = UPBIT_ACCESS
UPBIT_SEKRET = UPBIT_SEKRET
POLYGON_API = POLYGON_API
TWITTER_CONSUMER_KEY = TWITTER_CONSUMER_KEY
TWITTER_CONSUMER_SECRET = TWITTER_CONSUMER_SECRET
TWITTER_ACCESS_TOKEN_KEY = TWITTER_ACCESS_TOKEN_KEY
TWITTER_ACCESS_TOKEN_SECRET = TWITTER_ACCESS_TOKEN_SECRET
```

