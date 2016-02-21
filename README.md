# cmis-script-client

This is a simple client to run the groovy scripts from apache chemistry.


## Configuration

You can configure the client in the [scriptclient.properties](src/main/resources/scriptclient.properties) file:

```properties
cmisurl=http://localhost:8080/browser   #your repo url
cmisuser=test                           #username
cmispassword=test                       #password
cmisrepo=testing                        #repository to run with
threads=1                               #number of threads to start
script=template                         #the name of the groovy script in the scripts folder
```

