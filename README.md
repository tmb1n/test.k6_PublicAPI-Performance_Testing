# Performance_Testing-Project
<br>

## Performance Testing on test.k6.io with JMeter


This project is on Performance testing with JMeter for the test.k6.io on contacts, news, flip_Game, Calculating π module. It's a evaluating way to simulate and analyze the performance of a public API `test.k6.io` under various user load scenarios and monitoring working functionality and usability as expected.

<br>

## How to run this project!
1. Download & Install [JDK](https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html)
2. Download & Extract [JMeter Binaries Zip](https://jmeter.apache.org/download_jmeter.cgi)
3. Set environment variable(path) -  **Set JAVA_HOME**
4. Go to bin folder and open `jmeter.bat`
5. Download & Extract **[Project_files](https://drive.google.com/drive/folders/13SuvIsQtVSnPtEatu--I1_O4ma-ujcb4?usp=drive_link)** and Move it to `\apache-jmeter-5.5\bin` folder
6. Open the `test.k6-Performance_Testing.jmx` file on jemeter
7. **Run the project**

But in GUI mode it consumes more memory and **makes system slower**. \
So we run JMeter from the command line. There also generate an HTML report file.

8. Go to `\apache-jmeter-5.5\bin` and make a folder called "report". 
9. Now run following commands:
```ruby
jmeter -n -t project_files\test.k6-Performance_Testing.jmx -l report\test.k6-Performance_Testing.jtl  -e -o report\TestResult.html
```
**_command structure:_**
>	`jmeter -n -t [jmx file] -l [results file .jtl/.csv] -e -o [Path for html report folder]`

\
11. Then a HTML report will be generated in this folder.


<br>

<!-- 
## Test Cases for this Testing:
`incomplete` 
-->

## Test Report:
* Thread Properties
``` java
> Number of user:     = 3000
> Time:               = 10 minutes
                      = 10*60
                      = 600 SECOND 
> Users per 1 SECOND  = (3000/600)
                      = 5
> Users per 10 SECOND  = 50 
> Loop count           = 1
```
* Report
1. HTML [Report Link](https://drive.google.com/drive/folders/1WM7cePqVMVgdr2F4CITW3jM7ccn2yJb1?usp=drive_link)
2. Snapshots:
> * *JMeter Summary Report*
![jreport](https://drive.google.com/uc?export=view&id=1_QUwc694iF_s1C8Arab8v92BJHwzpRCl)

> * *Generated HTML Summary Report*
![rimage](https://drive.google.com/uc?export=view&id=1mhdDdC432lmD5SxqHS_xRxCg9jTFFOIk)



---

|:warning: **if you face any type of image broken/missing issue, please `refresh` this web page again.**|
| --- |

### **#Happy_Testing**
---

