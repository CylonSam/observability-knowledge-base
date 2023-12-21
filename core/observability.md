# Observability

Observability is the ability to understand your app's behaviour through collecting useful and diverse data such as **metrics, events, logs and traces**.  Very important!

Observability will always help you, but it will shine brighter when applied to complex and distributed systems

>Observability enables you to understand what is slow or broken and what you need to do to improve performance. With an observability solution in place, teams can receive alerts about issues and proactively resolve them before they impact users. ([Dynatrace](https://www.dynatrace.com/news/blog/what-is-observability-2/))

## Metrics

>_"Metrics are numbers that give information about something."_ (Collins Dictionary)

Metrics are fun little numbers that **provide insights into various aspects of your system**, such as resource utilization, response times, error rates, and throughput.

By collecting and analyzing metrics, you can gain valuable insights into the health and performance of your application.

Metrics are typically collected at regular intervals and can be categorized into different types:

**System Metrics**: These metrics provide information about the underlying infrastructure and resources, such as CPU usage, memory utilization, disk I/O, and network traffic.

**Application Metrics**: These metrics are specific to your application and provide insights into its behavior and performance. Examples of application metrics include request/response times, error rates, database query performance, and business-specific metrics like the number of orders processed or the number of active users.

**User Experience Metrics**: These metrics focus on the end-user experience and provide insights into how users are interacting with your application. Examples of user experience metrics include page load times, click-through rates, conversion rates, and user engagement metrics.

To effectively leverage metrics for observability, it is important to establish a robust monitoring and alerting system. This system should collect, store, and analyze metrics in real-time, allowing you to detect and respond to issues promptly. Additionally, visualizing metrics through dashboards and charts can provide a clear and intuitive representation of your application's performance.

Overall, metrics are a fundamental component of observability, enabling you to gain insights into your application's behavior, identify performance bottlenecks, and make data-driven decisions to improve the overall reliability and user experience.

### Insights
- Metrics will be the main thing you'll be looking at when trying to improve performance and reduce costs. Maybe your app container has more ram and cpu than it actually needs or maybe your app can process more data per request.
- Metrics are kinda cheap to store because they consist of only numbers.
- Not all metrics are important! Analyze the purpose of your system and it's necessities to decide which metrics are truly useful to you and should be collected.

## Events

## Logs

## Traces