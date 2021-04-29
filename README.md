# BME280

Raspberry PiでBME280で気圧、温度、湿度を取得するアプリです。
## 使い方
### 1. `smbus2`をインストールする
```shell
pip3 install smbus2
```

### 2. `Python3/bme280.py`をRaspberry Piの任意のディレクトリに配置する。

### 3. 実行する
```
python3 bme280.py 
```

## 変更内容
フォーク元の[本家リポジトリ](https://github.com/SWITCHSCIENCE/BME280)に対して、以下のような変更点があります。
### Python3対応
Python3に対応した、`bme280.py`を`Python3`ディレクトリに追加しました。

### 標準出力の形式変更
`Python3/bme280.py`を実行したときの標準出力を、スペース区切りの
> 気圧(hPa) 温度(°C) 湿度(%)

という形式に変更しました。

例
> ``` 1003.74 27.13 37.85 ```