# pysina_finance
获取新浪财经网站数据的Python包。

## 示例1: 获得历史每股净资产

```python
# example1.py
from sina_finance import sina
code='600519'
r=sina.mgjzc(code)
print(r)
```

```bash
python example1.py 
              每股净资产
日期                 
2022-03-31  164.610
2021-12-31  150.883
2021-09-30  138.791
2021-06-30  128.752
2021-03-31  139.528
...             ...
2001-12-31   10.124
2001-06-30    3.035
2000-12-31    2.391
1999-12-31    1.542
1998-12-31         

[86 rows x 1 columns]
```