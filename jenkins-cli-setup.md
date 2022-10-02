```
wget http://34.229.120.59:8080//jnlpJars/jenkins-cli.jar
```
* Downloads the `.jar` file
____
* Then create API token. After that use it in your commands
```
java -jar jenkins-cli.jar -s http://asif.techin48.com/ -auth asif:<api_token> -webSocket help

java -jar jenkins-cli.jar -s http://asif.techin48.com/ -auth asif:<api_token> -webSocket list-jobs
```
____

____
[Docs](https://www.jenkins.io/doc/book/managing/cli/)