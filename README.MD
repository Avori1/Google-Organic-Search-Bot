# Google Search Traffic BOT

- This is a bot that generates prganic traffic from Google Search.

## System

> if you are not using windows OS, replace the firefox driver (_geckodriver.exe_) with a driver that is compatible with your OS.

## How to install

1. Clone this repository

```shell
git clone --single-branch --branch main https://github.com/yukebrillianth/Google-Organic-Search-Bot.git GOSB

cd GOSB
```

atau download via [Release Page](https://github.com/yukebrillianth/Google-Organic-Search-Bot/releases/tag/Beta)

2. Install required packages

```shell
pip install -r ./requirements.txt
```

3. Edit proxy.json, fill with rotating proxy if you use rotating proxy
4. Edit config.json
5. Run main.py

```shell
py ./main.py
```

## Definitions

1. **_keyword_** = Keywords to be searched
2. **_website_uri_** = The Url of the article you are looking for
3. **_use_proxy_** = Using rotating proxy or not
4. **_amount_** = Amount of traffic (if not using a proxy)
5. **_headless_** = Show browser or not
6. **_interval_** = Time lapse
