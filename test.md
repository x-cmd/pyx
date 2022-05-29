
在mac arm上，扫描一次要 0.141s。
可以加入一些索引，用首字母，可能就能将时间降一个量级。


```
time awk '{ length($0)==3; }' pypi.txt
```
