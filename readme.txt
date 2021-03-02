Test call
http://localhost:8000/sample-service/prod
{"name":"sample-service","profiles":["prod"],"label":null,"version":"bacc007c23e0a24558b24db488fcd5fea20071fe","state":null,"propertySources":[{"name":"https://github.com/pasuwat-wang/udemy-config-repository/config/sample-service-prod.properties","source":{"application.name":"sample","sample.name":"Pasuwat","sample.profile":"default"}}]}

http://localhost:8000/sample-service/dev
{"name":"sample-service","profiles":["dev"],"label":null,"version":"bacc007c23e0a24558b24db488fcd5fea20071fe","state":null,"propertySources":[{"name":"https://github.com/pasuwat-wang/udemy-config-repository/config/sample-service-dev.properties","source":{"application.name":"sample","sample.name":"Pasuwat","sample.profile":"dev"}}]}