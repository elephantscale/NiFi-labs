# Lab 01
## NiFi Install

### Step 1. Download NiFi.

* Google for "install nifi" or
* Go directly to [Download](https://nifi.apache.org/download.html)
* Choose the zip file
* Download the zip file


![](images/17.png)


![](images/18.png)

### Step 2. Unzip the file.

```shell
unzip nifi-1.16.3-bin.zip 
```

* You will see the NiFi directory
![](images/19.png)

### Step 3. Start NiFi.

* **IMPORTANT** - Set the password first
```shell
nifi-1.16.3/bin/nifi.sh set-single-user-credentials mark mark123456789
```

```shell

cd nifi-1.16.3
./bin/nifi.sh run
```

### Step 4. Open NiFi in your browser.

* In a browser, open https://localhost:8443/nifi









