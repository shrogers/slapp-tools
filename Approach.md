# Introduction #

A SLAPP swarm is a collection of agents, a scheduler, and optionally an observer running in one or more threads/processes.  Agents are implemented as coroutines which may be used for the scheduler and observer as well.  Agents communicate with each other, the scheduler, and the observer via messages.  The scheduler forwards messages to other swarms and the observer sends statistics to an observer swarm which persists the data, generates summary statistics, and displays them in various ways.


# Details #

TBD