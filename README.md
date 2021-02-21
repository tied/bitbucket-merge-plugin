## Bitbucket Plugin for latest version of Attlasian SDK 2021

```bash
    ❯ atlas-version
    
    ATLAS Version:    8.2.6
    ATLAS Home:       /usr/local/Cellar/atlassian-plugin-sdk/8.2.6/libexec
    ATLAS Scripts:    /usr/local/Cellar/atlassian-plugin-sdk/8.2.6/libexec/bin
    ATLAS Maven Home: /usr/local/Cellar/atlassian-plugin-sdk/8.2.6/libexec/apache-maven-3.5.4
    AMPS Version:     8.1.0
    --------
    [INFO] Project POM found
    Executing: /usr/local/Cellar/atlassian-plugin-sdk/8.2.6/libexec/apache-maven-3.5.4/bin/mvn --version -gs /usr/local/Cellar/atlassian-plugin-sdk/8.2.6/libexec/apache-maven-3.5.4/conf/settings.xml
    Apache Maven 3.5.4 (1edded0938998edf8bf061f1ceb3cfdeccf443fe; 2018-06-17T13:33:14-05:00)
    Maven home: /usr/local/Cellar/atlassian-plugin-sdk/8.2.6/libexec/apache-maven-3.5.4
    Java version: 1.8.0_282, vendor: AdoptOpenJDK, runtime: /Library/Java/JavaVirtualMachines/adoptopenjdk-8.jdk/Contents/Home/jre
    Default locale: en_US, platform encoding: UTF-8
    OS name: "mac os x", version: "10.15.6", arch: "x86_64", family: "mac"
```


Here are the SDK commands you'll use immediately:

* atlas-run   -- installs this plugin into the product and starts it on localhost
* atlas-debug -- same as atlas-run, but allows a debugger to attach at port 5005
* atlas-help  -- prints description for all commands in the SDK

Full documentation is always available at:

https://developer.atlassian.com/display/DOCS/Introduction+to+the+Atlassian+Plugin+SDK
