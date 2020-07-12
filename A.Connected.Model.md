# A connected model

## Introduction

The self learning engine model is the core that works within every process spawned by the parent process. A process finishes the command it is given by the actor and passes the learned facts back to the knowledge graph.

## Actor engine to process

An actor engine receives commands as actions from the questioning engine. It passes the commands to an executable process.

## Process to facts

The process attempts to apply the facts to finish an action. It learns untill it complets the task succesfully at 100% accuracy. Then it converts the learnings into a curve and then to facts, or a facts itself.

## Note

The process and the actor engine has read only access to knowledge graph. When something new is learnt, a process dies and saves the computing resource.

## Experiements

This model fires when a computer is turned on. 

- [ ] Computer learning itself. Start with instruction set, knowledge about memory, process management, resource management. Let the model learn about the environment.
- [ ] The model will find the common facts to optimise the space used to store the knowledge graph.

## System design

![](https://github.com/imvetri/artificial-intelligence/blob/master/A.connected.model.png)

## Conclusion

This self learning model can be installed at any layer of a computing machine such as bios, kernel, management, IO, interface. Since the effort is the same, its best to stick to lowest level closer to the hardware.

## Idea

Try this model at BIOS / as a firmware code that will build itself upwards. 
