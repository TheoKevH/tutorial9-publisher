# Tutorial A: Publisher

**Name**: Theodore Kevin Himawan

**NPM**: 2306210973

**Class**: Adpro A

## Reflection 1

> a. How much data your publisher program will send to the message broker in one
run?

<p align="justify">The publisher will send 5 data to the message broker in one run.</p>

> b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber
program, what does it mean?

<p align="justify">It means that the publisher and subscriber use the same message broker to communicate.</p>

## My screenshot of running the RabbitMQ

![Running RabbitMQ](static/images/rabbitmq.png)

## Running cargo run from the consol

![Console](static/images/console.png)

When running, the publisher sent 5 data to the message broker.

## RabbitMQ Browser

![Activity](static/images/activity.png)

In the RabbitMQ browser, the spikes in the chart shows the message rates. In the dashboard, it shows the number of messages sent in a 1 minute interval, which caused it to spike because I did cargo run twice.