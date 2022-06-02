## LoanScan USDT Interest Rates
This repo contains the code of the crawler that process and store top 5 platforms for USDT interest rates

### Instructions

- Clone this repo: `https://github.com/kadnan/LoanscanUSDTInterestRates.git`
- Assuming you have Python installed, install Scrapy: `pip install scrapy`
- Go in the folder `cd InterestRates`
- Run the command `scrapy runspider rates.py -o rates.json` which should create a file `rates.json` in the same folder

If all works you should show records like below in the JSON file:
```
    [
        {"Rate": 0.1307, "Platform": "Youhodler"},
        {"Rate": 0.1268, "Platform": "Vauld"},
        {"Rate": 0.12, "Platform": "YieldApp"},
        {"Rate": 0.1163, "Platform": "IconFi"},
        {"Rate": 0.105155, "Platform": "Zipmex"}
]
```