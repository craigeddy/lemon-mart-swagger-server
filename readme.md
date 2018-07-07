After setting up a shared folder (Folder path = c:\source, Folder Name=source) in VirtualBox
```
C:\source\lemon-mart-swagger-server>docker run --rm -v /source/lemon-mart-swagger-server/server:/local/server swaggerapi/swagger-codegen-cli generate -i https://raw.githubusercontent.com/craigeddy/lemon-mart-swagger-server/master/swagger.2.yaml -l nodejs-server -o /local/server
```
