# Serverless Java with Spring Boot

Code samples from my [presentation](https://www.devtalks.ro/speakers/28-Thomas+Vitale) at DevTalks Romania 2022.

Applications in a microservices architecture can communicate with each other in different ways.
Adopting an event-driven paradigm based on asynchronous messaging provides services with a way of
communicating while reducing runtime coupling.

Applications in a microservices architecture can communicate with each other in different ways.
Adopting an event-driven paradigm based on asynchronous messaging provides services with a way
of communicating while reducing runtime coupling. Functions are a natural way of implementing
event-driven business logic regarding suppliers, processors, and consumers. Furthermore,
when going serverless, we aim at executables with instant startup and efficiency. Enter Spring.

Spring Cloud Function favours using the functional programming paradigm to implement your business logic
and provides useful features to build data pipelines, including type conversion and function composition.
Functions can be exposed through different options (like web endpoints or message channels), and adapters
can run them on platforms like Knative, AWS Lambda, Azure Functions, and GCP Functions. 

Spring Cloud Stream integrates your functions with messaging systems like RabbitMQ and Kafka without requiring
any change to your code. 

Finally, Spring Native lets you compile your applications as native executables using
GraalVM and provides instant startup, instant peak performance, and reduced memory consumption.
