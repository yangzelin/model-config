This folder contains the specification and light-codegen config.json for the MQ demo producer application. The source code is not available to the public but our enterprise customers who still have to integrate with existing application with MQ. If you are interested in access the MQ component and the example applications, please contact sales@lightapi.net

To scaffold the project. 

```
cd ~/networknt
rm -rf light-mq/examples/producer
java -jar light-codegen/codegen-cli/target/codegen-cli.jar -f openapi -o light-mq/examples/producer -m model-config/rest/openapi/mq-producer/openapi.yaml -c model-config/rest/openapi/mq-producer/config.json
```

