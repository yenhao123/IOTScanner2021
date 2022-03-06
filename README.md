# IOT scanner

### Server
OS : Ubuntu 20.04.2 LTS

### Web
Python : 3.8.10

Nginx : nginx/1.18.0

Mysql :  MySQL Ver 8.0.26

Php : PHP 7.4.3

## client slide
### construct page
Construct a database which could let your devices safely.

The database contains IOT device info(device type 、device model、open port...)、potential vulnerability.

## server side
### information gathering
searching engines
1. Shodan
2. Censys

devicetypes
1. nas
2. router
3. printer
4. camera

determine devicetype methods
1. keywordMethod (recommended,fast more)
2. featureMethod

### potential vulnerabilities collection
engines
1. Nmap

### vulnerabilities validation
engine
1. Metasploit

## 須知
1. 連接db password換成自己設的密碼，以下為須更動的檔案
www/site_prod.php
www/ip_cve.php
www/get_db/device_ip.php
www/get_db/device_num.php
