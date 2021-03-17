

### Development state: Beta (Code is stable, documentation is often lagging)

### Join our community [Telegram](https://t.me/rokcapGC) channel!



## Technical Analysis Automated:
* Momentum
* Relative Strength Index (RSI)
* Ichimoku Cloud (Leading Span A, Leading Span B, Conversion Line, Base Line)
* Simple Moving Average
* Exponential Moving Average
* MACD
* MFI
* OBV
* VWAP

## Alerts:
* Telegram
* Discord

## Features:
* Modular code for easy trading strategy implementation
* Easy install with Docker

You can build on top of this tool and implement algorithm trading and some machine learning models to experiment with predictive analysis.

## Installing And Running
The commands listed below are intended to be run in a terminal.

1. Install [docker CE](https://docs.docker.com/install/)

1. Create a config.yml file in your current directory. See the Configuring config.yml section below for customizing settings.

1. In a terminal run the application. `docker run --rm -v $PWD/config.yml:/app/config.yml rokcap/alogxbeta:master`.

1. When you want to update the application run `docker pull rokcap/alogxbeta:master`

### Configuring config.yml

For a list of all possible options for config.yml and some example configurations look [here](docs/config.md)
