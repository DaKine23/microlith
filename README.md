# microlith
Eventbroker like communication inside your application 

## reasoning
Most of the time deploying a monotlithical application is easier or adding a new feature to an existing service. If you just want to try out if things can work porperly. To split that dependency up later on can be tricky. One reason that this is the case is the direct manner of communication. So i will create a library that acts similar to an eventbroker (nats,kafka, rabbitMQ,...) just inside of your application. The interface should be compatible to the mentioned brokers for exchanging it later on without touching too much business code.
