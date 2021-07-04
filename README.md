# terraform-docker weather dashboard

Was able to deploy nodered, infludb, and grafana. Loaded a flow into node and passed in credentials for influxdb. API used was from https://openweathermap.org/ to get weather information from cape canaveral and tempe.

# DEMO

First I accessed my influxdb and nodered container by using {public-ip}:{external-port} and created a user. Then I obtaind my token to use for nodered. 

![](Screenshots/99e188a7cdbc37c2dda5b02515fb7401.png)
![](Screenshots/4657d9e58c1b1cabf68b9e457eb07f4b.png)

Next I created a dashboard in grafana to more easily present my information. To do this, go to configuration and load your data sources and chooose influxdb.

![](Screenshots/a8ba855bcff7b17dc799c0f5cea12ce9.png)
