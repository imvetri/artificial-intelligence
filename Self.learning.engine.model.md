# Self learning engine model

## Introduction

A simplest form of intellegence is word. With a start sentence, an engine should be able to build knowledge by questioning and generating facts.

This model works by a starter sentence that is given as an order to the machine. Ordering engine, questioning engine and answering engine work together to build the knowledge and parallely actor engine attempts to finish the task with the facts generated.



### Commanding engine 

Receives a command from human. Command is in the form of Action + noun or Verb + noun. Example - Ask question

### Questioning engine

Recives facts, and command. It reads the knowledge graph to question about itself and the knowledge graph. It generates questions about the incoming message and passes it to ansering engine. These can go in an infinite loop. Eveny loop creates a new meaning Example - What is Ask, What is question is one loop. What is ask, What is question, What is ask question is a second loop. What is ask question, who can ask question, who can answer question. 

Designing this along with ansering engine will help to build the questions, facts on its own.

### Answering engine

Reads the knowledge graph and gives answers to the questions. Example, what is ask - Ask is action, ask is verb. What is action, what is verb, what is 'what is ask' - question so on.

### Actor engine 

This uses the knowledge graph and interfaces with other systems.

## System design

![](https://github.com/imvetri/artificial-intelligence/blob/master/Self.learning.engine.model.png)


## Conclusion

The model should fire itself up.


