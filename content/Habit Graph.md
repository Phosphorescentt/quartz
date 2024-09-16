Some days I'm hit with a spike of motivation and I think "Damn there are so many things that I want to do to be more me" and these initial thoughts are destroyed with the following thought: "Which one is the *most important* one to start with?".

Ah, a dependency problem - time to pull out some graph theory. Long story short, the idea is to construct a matrix of each habit and which other habits it enables and use that to decide on some [topological sorting](https://en.wikipedia.org/wiki/Topological_sorting) for the habits to tell me which one(s) I should pick up first.

Results for this idea are pending, but I reckon I can hack something together in an afternoon.

###### Update 2024-09-15
It's dawning on me that this not such a great idea for the following reasons:
1. The setup I had in my mind for this would mean that people are able to input cyclic relationships into the graphs. This is fine, except removing cycles from a directed graph is an NP-hard problem.
2. It may actually be better if the habits are linearly ordered using some kind of rating system instead
3. This idea might be interesting to more generally apply to tasks instead of just habits.