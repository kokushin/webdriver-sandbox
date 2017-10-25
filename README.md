# webdriver-sandbox

## Put driver

https://chromedriver.storage.googleapis.com/2.29/chromedriver_mac64.zip

```shell
chmod +x /usr/local/bin/chromedriver
```

## Start selenium

```shell
java -jar selenium-server-standalone-3.4.0.jar &
```

## Stop selenium

```shell
ps aux | grep selenium-server-standalone | grep -v grep |awk {'print $2'} |xargs kill -9
```

## Run program

```shell
php test.php
```
