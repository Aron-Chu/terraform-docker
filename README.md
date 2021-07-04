# terraform-docker weather dashboard

Was able to deploy nodered, infludb, and grafana. Loaded a flow into node and passed in credentials for influxdb. API used was from https://openweathermap.org/ to get weather information from cape canaveral and tempe.

# DEMO

First I accessed my influxdb and nodered container by using {public-ip}:{external-port} and created a user. Then I obtaind my token to use for nodered. 

(https://user-images.githubusercontent.com/86208890/124390616-46c39400-dca1-11eb-947d-612d98ab0615.png)
(https://user-images.githubusercontent.com/86208890/124390641-678be980-dca1-11eb-8aaf-b4858592fdc5.png)

Next I created a dashboard in grafana to more easily present my information. To do this, go to configuration and load your data sources and chooose influxdb.

(https://user-images.githubusercontent.com/86208890/124390649-707cbb00-dca1-11eb-85f1-312c10e8b01a.png)
