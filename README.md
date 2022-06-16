# get-crypto-prices
A simple python script to get my favorite crypto prices every 5 or 10 minutes and display it as a windows notification.

## The notification
![DEMO IMAGE](https://github.com/DreamSky1996/get-crypto-prices/blob/master/img/1.png)

### TODO:
* [x] Add/Fix the toast icon
* [x] Accept coins as parameter (maybe .json) 
* [x] Linux support
* [x] Dynamic price formatting
* [ ] Overlay mode (avoids notifications)
* [ ] Add validations and error treatment
* [ ] Create "Make" file to simplify installing/executing
* [ ] GUI to select which cryptos to get (replacing the .json)

## Required:
* ```pip install python-binance```

### Windows:
* ```pip install win10toast```

### Linux (Tested on Ubuntu and Manjaro)
* ```pip install notify2```


