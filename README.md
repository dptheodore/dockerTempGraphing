# Weather Dashboard

A simple Node-Red IoT application written in Javascript and HCL utilizing Docker containers and Grafana to beautifully display the temperatures and relative humidities at two locations.

We create a simple flow in Node-Red to make an API call to openweathermap.org and then pass a JSON payload to InfluxDB. Then, we utilize Grafana to beautify the payload.
