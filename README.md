# apprd-bom
### From workspace folder
    mvn install:install-file -Dfile=apprd-bom/pom.xml -DpomFile=apprd-bom/pom.xml

### Publish to exchange
### Go to bom folder
    mvn deploy -f pom.xml -Pdeploy-to-exchange-v3