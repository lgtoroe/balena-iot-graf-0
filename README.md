# balena-iot-graf-0
 
This repository aims to be the first of many as a solution to the implementation of rapid projects in which we can take data from sensors and export it quickly to the web, for this we have chosen Grafana as a platform that has two large data sources such as Prometheus and InfluxDB With this we intend to expose the data sent from python in the case of Raspeeby-PI's GPIO and through node_exporter for system data.

Grafana Works! expose port 80, works in 3000 admin / admin for first time execution.
Prometheus Works! Nothing to do, Add a persistence volume for /data i don't known what is the space alocate for X time, take a note for this.
Node_export Works! Take data from System and Push to Prometheus, nothing to do.
Influx, implemented! waiting push data. Declare ENV vars to work propertly.
Python, push data to Influx, not ready 



That is all for the moment.