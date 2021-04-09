# :v: Welcome :v:

Thank you very much for taking the time and partiicpating in the challenge!

# :alarm_clock: Logistics and Expectations

We know that you'd be using your precious free time to work on this challenge and therefore we want to set clear expectations to ensure that your time is spent reasonably and to avoid that you waste or invest too much. Again we appreciate you participating.

__How much time should i spend?__

_A resonable amount of time is a couple of hours, most probably less than half a day._

__How do you evaluate the result?__

_We will not grade or evaluate based on quantity but on quality. We'd invite you to present your results to our team which is a great chance to meet your (potential) new colleagues._

__How shall i present, Powerpoint?__

_Your presentation could be of any form (Word, Miro, Markup Document, Powerpoint, Mural Board, Trello, Textfile, ...) you like and that suits your known workflow._
 
__How can I submit my results?__

_Please commit your code to a repository and share it with. Afterwards we'll schedule a presentation with you where you'd walk us through your approach to the challenge and present what you've did. The presentation will take 60 to 90 minutes and you can schedule it via [this link once you're ready](https://calendly.com/seb-azeti/60min)._

__Deadline__

Please submit your results until __21st of April 2021 and schedule a slot for the presentation beforehand (!), ideally before 25th of April__ as we want to close the position in April.

# Challenge Overview

The challenge consists of two parts including options you can choose from:
1. Technology
   * a) Present an existing software project of yours
   * b) Create a prototype and present it
2. Leadership
   * Create a plan for your first 100 days as a Lead

# Technology

The main purpose of this challenge is to review code that you've written and to evaluate if you can explain your workflow or an architecture to the team. We don't expect full blown software projects in the prototpye. This is intended to be a show case of your software engineering skillset.

__Pick one of the two (a or b) technology tasks.__

## a) Present an existing software project of yours

Showcase a software project that you've actively participated in the development. No matter if it is an awesome pull request that you're proud of or your own project. Ideally it covers some of our known programming languages and shows frontend as well as backend use cases.

__We're capable to evaluate the following languages: Java, Kotlin, Typescript, ReactJS, Javascript, NodeJS.__

### Your tasks
1. Give us access to the code so we can review it.
2. Present the software on a high level, if possible talk about challenges, architecture or technical debt

## b) Create a prototype and present it

Our azeti IoT Platform ingests messages via MQTT through ActiveMQ which is connected via Apache Camel to our backend where data is persisted in InfluxDB and PostgreSQL. Here are some use cases we're facing.

### Use cases

1. It is quite complex for us to connect relational databases from customers and to merge this static relational data with our streaming data. We looked into Kafka and KSQL for that use case. We'd like to enrich streaming data with info from a RDBMs or something as simple as a CSV.
2. We need to act on incoming messages, i.e. sending alerts via E-Mail or Slack Chat message depending on the message content. Most simply put: Send an alert if temperature is above 25 degrees. More complex: Send a slack chat message if the message contains the phrase "Error". More complex: Right now we use Apache Camel routes to do this with custom Java code.

### Your tasks

1. Develop a small prototype (Backend and Frontend) that covers one of the above mentioned use cases. Your tech stack should consist of an event streaming system (i.e. Kafka, Kinesis, pub/sub, MQTT or similar), ReactJS for the Frontend and utilize one of Java, Kotlin, NodeJS, Typescript.
2. Demonstrate the prototype and the architecture of it

:bulb: _This doesn't have to be a full blown software project but just a PoC/prototype, don't worry if you cannot cover TDD and a hollistic documentation, this is not expected in this PoC ;-). Surely we love tests but we are aware of the efforts for such a challenge._

# Leadership

Create a presentation that covers the following questions.

1. What actions will you take in your first 6 months to form the team, build trust and to get to know each member?
2. How would you implement the following statement as a Lead? Statement: _"I provide structure and direction to the team by clearly communicating and collaboratively agreeing on goals and expectations on a regular basis."_
