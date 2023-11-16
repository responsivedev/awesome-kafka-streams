# Kafka Streams in the wild 

Here is a collection of known uses of Kafka Streams in production. This is based only on public information. If you have a use case you'd like to add, please [contribute](CONTRIBUTING.md)!

* [Salesforce](https://engineering.salesforce.com/real-time-einstein-insights-using-kafka-streams-ca94008c2c6f/) uses Kafka Streams to generate real time insights which are used to score and rank emails for boosting sales efficency.
* [Deutsche Bahn](https://www.infoq.com/news/2020/01/kafka-event-stream-deutsche-bahn/) uses Kafka Streams to make announcements of train arrivals at stations.
* Walmart:
 * [Real time recommendations and Fraud detection](https://www.slideshare.net/ConfluentInc/kafka-streams-at-scale-deepak-goyal-walmart-labs-kafka-summit-london-2019)
 * [Real time data processing and ML inferencing](https://www.slideshare.net/kafkazone/real-time-data-processing-and-model-inferncing-platform-with-kafka-streams-navinder-singh-walmart)
* [Blackrock](https://engineering.blackrock.com/delivering-eventual-consistency-with-kafka-streams-c013a217b9b9) uses Kafka Streams to power their liquidity management solutions.
* [Zalando](https://engineering.zalando.com/posts/2017/11/real-time-ranking-kafka.html) uses Kafka Streams to rank fashion websites in real-time.
* [New York Times](https://www.confluent.io/blog/publishing-apache-kafka-new-york-times/) manages their entire article publishing pipeline using Kafka Streams.
* [Michelin](https://blogit.michelin.io/kstreamplify/) uses Kafka Streams to power their in-house ERP system.
* [Airbnb](https://www.confluent.io/de-de/events/kafka-summit-london-2022/evergreen-building-airbnbs-merge-queue-with-kafka-streams/) uses Kafka Streams to power their actor-based merge queue with serializablle consistenty to manage merges in their large monolithic repositories.
* [Twilio's](https://www.twilio.com/blog/kafka-streams-near-real-time) Enterprise Insights team uses Kafka Streams to power their alerting engine based on real-time metrics.
* [Imperva](https://www.imperva.com/blog/not-just-for-processing-how-kafka-streams-as-a-distributed-database-boosted-our-reliability-and-reduced-maintenance/) uses Kafka Streams to build a highly-available and fault-tolerant distributed data store for their microservices.
* [AVSystem](https://www.avsystem.com/blog/csp/large-scale-data-monitoring-with-kafka-streams/) uses Kafka Streams for real-time analytics on IoT data at scale.
* [LineCorp](https://engineering.linecorp.com/en/blog/applying-kafka-streams-for-internal-message-delivery-pipeline) uses Kafka Streams to implement a task dispatching system and also for performing streaming operations on their Kafka topics.
* Bloomberg:
  * [Real time adaptation of financial market events](https://www.confluent.io/events/kafka-summit-americas-2021/real-time-adaptation-of-financial-market-events-with-kafka/): Bloomberg reacts to changes in financial contracts in over the counter markets in real time using Kafka Streams
  * [Derived data team uses Kafka Streams to do algorithmically derived pricing](https://www.confluent.io/resources/kafka-summit-2020/replaying-kstreams-apps-using-state-snapshots/).
 * [Expedia](https://www.confluent.io/resources/kafka-summit-2020/launching-the-expedia-conversations-platform-from-zero-to-production-in-four-months/) built their real time conversations platform, which answers questions like "how long is my layover", etc., around Kafka Streams.
