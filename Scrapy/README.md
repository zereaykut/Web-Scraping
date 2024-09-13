# Scrapy
Some scrapy applications.

## Python Virtual environment

Create python environment
```shell
python -m venv venv
```

Activate environment in Mac/Linux 
```shell
source venv/bin/activate
```

Activate environment in Windows 
```shell
.\venv\Scripts\activate
```

Install required packages
```shell
pip install -r requirements.txt
```

## Run Scrapy Spider

```shell
scrapy runspider audible_changing_user_agent.py -o output_audible_changing_user_agent.csv
scrapy runspider worldometers_scraping_data_from_multiple_links.py -o output_worldometers_scraping_data_from_multiple_links.json
```