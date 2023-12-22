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

Formal definition of event:

>_a thing that happens, especially one of importance._ (Oxford Languages)

Events are things that happen inside your app ecosystem that are relevant enough to be stored.

Let's check what bard has to say about events in the context of observability:

_"Events are discrete occurrences within a system that are significant enough to be recorded. They represent specific moments in time with associated data that helps understand what happened and why. Think of them as checkpoints or milestones in the system's operation."_ (Google Bard)

Interesting!

**Examples of Events**:

- User Interactions: Clicks, form submissions, and other user actions can be captured as events.
- System State Changes: Events can signify changes in the state of a system, such as the start or stop of a service.
- Error Events: Events are often used to capture information about errors or exceptions that occur in the system.
- Security Events: Events can include security-related information, such as login attempts or access control events.

### Insights
- When you have a system that consists of a pipeline of many microservices, maybe you'll want to know if some data left service A (event 1) and was received by a service B (event 2), so that you can track the flow of input data through your system.

## Logs

## Traces