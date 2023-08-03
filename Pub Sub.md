---
type: GCP Component 
share: true
creation date: 2023-08-02 16:38
modification date: Wednesday 2nd August 2023 16:38:00
tags:
related:
---


- Ensures at-least-once delivery
- No provisioning is required
- Open APIs
- Global by default
- Offers end-to-end encryption
- Pub/Sub is a good solution to buffer changes for lightly coupled architectures
## Structure
- The essential element is a Topic
	- You can think the Topic as an Radio, essentially always on, no matter if has 0 subscribers or 0 messages.
	- One Topic can have many types of messages


<details>
<summary>What means to say that Pub/Sub is a good solution to buffer changes for lightly coupled architectures</summary>
It means that it is an effective approach for handling communication and data synchronization between different components or services in a system that are loosely interconnected.

In a lightly coupled architecture, the components or services are designed to be independent and have minimal direct dependencies on each other. They communicate through well-defined interfaces or messages, allowing them to evolve and scale independently. This design approach promotes flexibility and easier maintenance of the system.
</details>
<!--ID: 1691035009154-->


<details>
<summary>What means to say that Pub/Sub is global by default?</summary>
Pub/Sub being global by default means that it allows for seamless communication and data transfer between different regions and locations within the Google Cloud Platform.
</details>
<!--ID: 1691035009171-->


<details>
<summary>What means to say that Pub/Sub ensures an at-least-once delivery?</summary>
The usual guarantee offered by PubSub is **at least once delivery**. It means that in case of such a failure, PubSub will attempt to deliver the message again, until it's successfully acked (or the subscription retention limit is reached).
</details>
<!--ID: 1691035009198-->


<details>
<summary>What does ack means in Pub/Sub?</summary>
In Pub/Sub, ack stands for acknowledgment and it is used to confirm the successful delivery of a message to a subscriber.
</details>
<!--ID: 1691035009213-->






