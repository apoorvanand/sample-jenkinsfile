# sample-jenkinsfile

-javaagent:C:\\Users\\anand\\.m2\\repository\\org\\jacoco\\org.jacoco.agent\\0.8.6\\org.jacoco.agent-0.8.6-runtime.jar=destfile=G:\\Amazon-interview\\jacoco-maven-unittestv2\\target\\jacoco.exec


https://apoorwanand.s3.us-east-1.amazonaws.com/spring-petclinic.zip


https://dzone.com/articles/code-coverage-report-generator-for-java-projects-a
https://dzone.com/articles/reporting-code-coverage-using-maven-and-jacoco-plu

https://apoorwanand.s3.amazonaws.com/jacoco-codecoverge-Demo.zip

server.tomcat.threads.max=800

server.tomcat.accept-count=300
server.tomcat.max-connections=10000
#server.tomcat.max-threads=200
server.tomcat.min-spare-threads=300

https://howtodoinjava.com/spring-boot2/embedded-tomcat-configuration/



https://learn.akamai.com/en-us/webhelp/netstorage/netstorage-http-api-developer-guide/GUID-BC01774E-121C-4F64-AC54-D0050FA4983C.html
```
import numpy as np
import matplotlib.pyplot as plt
import matplotlib.dates as md
import numpy as np
import datetime as dt
import time
li=[[1616870067,0.12],[1616890061,0.16],[1617870061,2.16],[1618870061,5.16]]
xs = [md.date2num(dt.datetime.fromtimestamp(x[0])) for x in li]
ys = [x[1] for x in li]
plt.subplots_adjust(bottom=0.2)
plt.xticks( rotation=25 )
ax=plt.gca()
xfmt = md.DateFormatter('%Y-%m-%d %H:%M:%S')
ax.xaxis.set_major_formatter(xfmt)
plt.plot(xs, ys)

```


