### To regenerate the project in /tmp and compare with the existing, run from parent folder ~/networknt
java -jar light-codegen/codegen-cli/target/codegen-cli.jar -f swagger -o /tmp/user -m model-config/rest/oauth2_user/1.0.0/swagger.json -c model-config/rest/oauth2_user/1.0.0/config.json


### for new sepc version: openapi-3.0
java -jar light-codegen/codegen-cli/target/codegen-cli.jar -f openapi -o /tmp/user -m model-config/rest/oauth2_user/1.0.0/openapi.json -c model-config/rest/oauth2_user/1.0.0/config.json
