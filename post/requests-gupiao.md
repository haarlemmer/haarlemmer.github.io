## Requests爬虫 利用API获取股票信息

最近学了requests，写了一个利用新浪API获取股票信息的程序，程序如下

```python
import requests
code = input("Code: ")
r = requests.get(f"http://hq.sinajs.cn/list={code}")
lis1 = r.text.split("=")
lis2 = lis1[1].split('"')
lis3 = lis2[1].split(',')
print(f"名字: {lis3[0]} \
    \n今日开盘价: {lis3[1]} \
    \n昨日收盘价: {lis3[2]} \
    \n当前价格: {lis3[3]} \
    \n今日最高价: {lis3[4]} \
    \n今日最低价: {lis3[5]} \
    \n成交股票数: {lis3[8]} \
    \n成交金额: {lis3[9]}")
```

### Files

| Path | URL | Password |
|------|-----|----------|
| study/requests/GuPiao.py | [Link](http://106.13.5.48/s/eznQsg6P5DXDagB) | [View](/files.html) |
