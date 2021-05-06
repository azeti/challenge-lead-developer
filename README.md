# :v: Welcome :v:

Thank you very much for taking the time and partiicpating in the challenge!

# :alarm_clock: Logistics and Expectations

We know that you'd be using your precious free time to work on this challenge and therefore we want to set clear expectations to ensure that your time is spent reasonably and to avoid that you waste or invest too much. Again we appreciate you participating.

__How much time should I spend?__

_A resonable amount of time is a couple of hours, most probably less than half a day._

__How do you evaluate the result?__

_We will not grade or evaluate based on quantity but on quality. We'd invite you to present your results to our team which is a great chance to meet your (potential) new colleagues._

__How shall I present, Powerpoint?__

_Your presentation could be of any form (Word, Miro, Markup Document, Powerpoint, Mural Board, Trello, Textfile, ...) you like and that suits your known workflow._
 
__How can I submit my results and present?__

_First, [book a slot for your presentation in advance](https://calendly.com/seb-azeti/lead-iot-challenge). The presentation slot is set to maximum 90 minutes. Secondly, commit your code to a repository and share (linkl or ZIP including your gitlog) it with us through the designated slack channel that you'll be givent to._

__Deadline__

Please submit your results until __24th of May 2021 and schedule a slot for the presentation. We designated the last week of May 2021 for the presentation slots. [Use this link to schedule it](https://calendly.com/seb-azeti/lead-iot-challenge).__

# Challenge Overview

The challenge consists of a technical and a leadership section. The technology section offers four options that you can choose one of to proceed with. We give options to ensure that every candidate can select the most time effective option for herself. If you don't see any option matching, let us know and suggest a different approach, we're happy to consider as we're aware of time and efforts to participate in a recruitiing challenge.

1. Technology
__The technology challenge must include backend code, ideally in Java or Kotlin.__

   * a) Present an existing software project of yours
   * b) Create a prototype and present it
   * c) Code review of bad Java code
   * d) Propose a custom topic if options a), b) or c) don't work for you, we're happy about proposals.
2. Leadership
   * Create a plan for your first 6 months as a Lead Software Engineer

# Technology

The technology section is intended to be a show case of your software engineering skillset. 

__Select only one of the following options!__

## a) Present an existing software project of yours

Showcase a software project that you've actively participated in the development. No matter if it is an awesome pull request that you're proud of or your own project. Ideally it covers some of our known programming languages and shows frontend as well as backend use cases.

__Your project must include a part of java or Kotlin, furthermore we're capable to evaluate the following languages: Java, Kotlin, Typescript, ReactJS, Javascript, NodeJS.__

### Your tasks
1. Give us access to the code so we can review it.
2. Present the software on a high level, if possible talk about challenges, architecture or technical debt

## b) Create a prototype and present it

Our azeti IoT Platform ingests messages via MQTT through ActiveMQ which is connected via Apache Camel to our backend where data is persisted in InfluxDB and PostgreSQL. Here are some use cases we're facing.

### Use cases

1. Merge existing relational data (simplke table) with incoming time series data, i.e. to enrich an incoming message with existing meta data from a RDBMS.
2. React on the payload of an incoming message, i.e. throw an alert depending on the payload.

### Your tasks

1. Develop a small prototype (Backend and Frontend) that covers one of the above mentioned use cases. Your tech stack should consist of an event streaming system (i.e. Kafka, Kinesis, pub/sub, MQTT or similar), ReactJS for the Frontend and utilize one of Java, Kotlin, NodeJS, Typescript.
2. Demonstrate the prototype and the architecture of it

:bulb: _This doesn't have to be a full blown software project but just a PoC/prototype, don't worry if you cannot cover TDD and a hollistic documentation, this is not expected in this PoC ;-). Surely we love tests but we are aware of the efforts for such a challenge._

## c) Code review of bad Java code
We'll hand over a couple of Java files. This is legacy code we already replaced and is a blueprint for bad code style and poor structure. Let us know if you pick this challenge and we will send the code to you on demand.

### Your task
Review the code and present your findings, including proposal to fix it or restructure the code, following modern best practices in Java development. You can assume that we use Lombok nowadays.

# Leadership

Create a presentation that covers the following questions.

1. What actions will you take in your first 6 months to establish yourself in the existing team, build trust and to get to know each member?
2. How would you implement the following statement as a Lead? Statement: _"I provide structure and direction to the team by clearly communicating and collaboratively agreeing on goals and expectations on a regular basis."_
