# Quick Car Sharing 

This repository contains the code for our [real-time monitoring and analytics
solution](https://d9p.io/2021/05/08/solution-real-time-monitoring-and-analytics/).

## Structure


* **frontend**: Our dashboard based on [deck.gl](https://deck.gl/). You can see
  a live version here: [http://carsharing.d9p.io/](http://carsharing.d9p.io/).
* **quick**: Quick's GraphQL schema that is used in the backend.
* **trip-aggregator-app**: The Kafka Streams application that aggregates status
  events into trips
