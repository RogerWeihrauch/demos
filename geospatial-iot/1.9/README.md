# Geospatial IoT Demo

*NOTE:* This demo has been contributed by [amollenkopf](https://github.com/amollenkopf/) from [ESRI](https://www.esri.com).

<img src="docs/0-overview/architecture.jpg"/>
This project demonstrates how to configure a full stack geo-enabled Internet of Things (IoT) solution using <a href="https://mesosphere.com/">Mesosphere's</a> open sourced <a href="https://dcos.io/">Data Center Operating System (DC/OS)</a> using <a href="https://www.docker.com/">Docker</a> containerization and <a href="http://mesos.apache.org/">Mesos</a> frameworks including <a href="https://mesosphere.github.io/marathon/">Marathon</a>, <a href="http://kafka.apache.org/">Kafka</a>, <a href="http://spark.apache.org/">Spark</a>, and <a href="http://elasticsearch.mesosframeworks.com/">Elasticsearch</a>.<br>  <!-- To see the DC/OS IoT demo in action click on the video link below.<br> -->
<center><table><tr><td width="50%"><img src="docs/9-visual/02.gif"><br>Geohash aggregation replay of taxi movement in New York City.</td><td width="50%"><img src="docs/9-visual/03.gif"><br>Heatmap replay & of taxi movement in New York City.<br><br></td></tr></table></center>
<!-- <center><a href="https://youtu.be/tOPmPIHuV-o"><img src="docs/0-overview//dcos-iot-demo-screenshot.jpg" height="75%" width="75%" ></a></center> -->

## To create your own DC/OS IoT demo environment:
0. <a href="docs/0-overview/README.md">Review the application & architecture overview</a>.<br>
1. Provision compute resources on <a href="docs/1-azure/README.md">Microsoft Azure</a>, <a href="docs/1-amazon/README.md">Amazon Web Services</a>, <a href="docs/1-amazon-c2s/README.md">Amazon C2S</a> or <a href="docs/1-on-premise/README.md">on-premise.</a><br>
2. <a href="docs/2-install/README.md">Install DC/OS</a> and then <a href="docs/3-explore/README.md">Explore the DC/OS & Mesos dashboards</a>.<br>
3. <a href="docs/4-kafka/README.md">Install Kafka & schedule brokers</a>.<br>
4. <a href="docs/5-elasticsearch/README.md">Install Elastic & schedule an Elasticsearch Cluster</a>.<br>
5. <a href="docs/6-webapp/README.md">Install Map web application</a>.<br>

## Running the demo:
6. <a href="docs/7-stream/README.md">Schedule a Spark Streaming job</a>.<br>
7. <a href="docs/8-source/README.md">Schedule a Kafka producer application</a>.<br>
8. <a href="docs/9-visual/README.md">Visualize IoT movement behavior</a>.<br>
9. <a href="docs/10-cleanup/README.md">Applying cleanup procedures</a> between demo runs.
