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
  * Some more details of the use case can be found in this [paper](https://dl.acm.org/doi/10.1145/3448016.3457556), and this [talk](https://www.youtube.com/watch?v=tEcYffZz-Mc).
* [Expedia](https://www.confluent.io/resources/kafka-summit-2020/launching-the-expedia-conversations-platform-from-zero-to-production-in-four-months/) built their real time conversations platform, which answers questions like "how long is my layover", etc., around Kafka Streams. Some more details of the use case can be found in this [paper](https://dl.acm.org/doi/10.1145/3448016.3457556).
* [Indeed](https://www.slideshare.net/HostedbyConfluent/from-monoliths-to-microservices-a-journey-with-confluent-with-gayathri-veale-current-2022) powers their microservices architecture with Kafka Streams.
* [Wise](https://www.confluent.io/fr-fr/events/kafka-summit-london-2023/streaming-infrastructure-at-wise/) uses Kafka Streams to power the instant money movement features of their financial platform.
* [Lifull Connect](https://www.confluent.io/events/kafka-summit-london-2023/lessons-learned-scaling-stateful-kafka-streams-topologies/) uses Kafka Streams to power their platform for real estate listings.
* [Morgan Stanley](https://www.confluent.io/events/kafka-summit-london-2023/consistent-high-throughput-real-time-calculation-engines-using-kafka-streams/) has Kafka Streams powering their liquidity management platform. 
* [Zopa Bank](https://www.confluent.io/events/kafka-summit-london-2023/highly-available-kafka-consumers-and-kafka-streams-on-kubernetes/) uses Kafka clients and Kafka Streams to power their backend event driven applications.
* [BigCommerce](https://medium.com/bigcommerce-engineering/use-of-kafka-and-kafka-streams-at-bigcommerce-6189345c3c21) uses Kafka streams to power their real time data platform which serves insights to the merchants using their platform for ecommerce.
* [Twitter](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2020/streaming-logging-pipeline-of-home-timeline-prediction-system) uses Kafka Streams extensively, including in their real time ML training pipeline which updates the model that ranks tweets for the 'For You' timeline.
* [New Relic](https://www.datacouncil.ai/talks/kafka-streams-in-production-from-use-case-to-monitoring) uses Kafka Streams to do real time metric aggregations in their core data pipelines.
* [Intel](https://www.intel.com/content/dam/www/central-libraries/us/en/documents/building-a-cyber-intelligence-platform-apache-kafka-paper.pdf) uses Kafka Streams as part of their real time cyber intelligence platform.
* [Stubhub](https://www.meetup.com/kafkabayarea/events/267811182/) uses Kafka Streams for real time fraud detection: unfortunately there seems no presentation materials left, but it was primarily a remote call to other fact stores to check certain fraud indication rules (barely remember the details).
* [Pinterest](https://www.slideshare.net/ConfluentInc/building-pinterest-realtime-ads-platform-using-kafka-streams) used Kafka Streams for their real-time ads platform. Also more details can be found in this [talk](https://www.youtube.com/watch?v=RWPCLfnYFRQ).
* [k2data](https://www.k2data.com/), a data platform solution provider focused on industrial markets, uses Kafka Streams for their client's real-time scenarios, such as anomaly detection and data cleaning.
* [Rabobank](https://axual.com/real-time-financial-alerts-at-rabobank-with-apache-kafkas-streams-api/) builts its realtime Rabo Alerts service upon financial events using Kafka Streams.
* [Altair Panopticon](https://altair.com/resource/panopticon-explainer-introduction-to-stream-processing) incorporates Kafka Streams framework into its stream processing engine provided to customers.
* [ironSource](https://aws.amazon.com/blogs/big-data/how-ironsource-built-a-multi-purpose-data-lake-with-upsolver-amazon-s3-and-amazon-athena/) uses Kafka Streams API to handle multiple real-time use cases, such as budget management, monitoring and alerting that run through their game growth platform.
* [Nuuly](https://www.youtube.com/watch?v=ur1Zeafo_lo) relies on Kafka Streams and Kafka Connect, coupled with data science and machine learning to provide in-the-moment business intelligence and to tailor a personalized rental experience to our customers.
* [Recursion Pharmaceutical](https://videos.confluent.io/watch/NHgXjNs9Yk5MxBn8LY8kxJ) uses Kafka Streams to power its data pipeline for its drug discovery efforts.
* [Trivago](https://www.youtube.com/watch?v=e9jpFHbS4XY) uses Kafka Streams for stream processing of application logs, such as data cleaning and enrichment, sessionization, etc.
