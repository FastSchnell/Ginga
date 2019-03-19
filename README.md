# Ginga 巴西足球之魂
==================

Ginga是一个分布式锁。
![image](ginga.jpeg)

下载
----
linux 64位
```
wget googlebridge.com/ginga_linux_amd64
chmod +x ginga_linux_amd64
```

mac
```
wget googlebridge.com/ginga_mac
chmod +x ginga_mac


启动服务
-------
```
./ginga_linux_amd64 -k test_token
```


yaml配置文件
-----------
通过yaml配置文件启动ginga，`vi config.yaml`
```
timeout: 60
endpoint: 0.0.0.0:1903
token: test_token
```
运行Ginga `./ginga_linux_amd64 -c config.yaml`


client
------

Golang [Ginga-Client-Go](https://github.com/FastSchnell/Ginga-Client-Go)

Python [Ginga-Client-Py](https://github.com/FastSchnell/Ginga-Client-Py)

