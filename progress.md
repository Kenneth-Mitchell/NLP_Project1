# Current Progress
So far, we have been working on brainstorming ways in which we can get our system to generate a response to why sentences do not make sense. We have gone through many ideas, but one thing that we noticed is that each of the input sentences seem to have a similar input that has a subject, and then something that the subject does that does not make sense, which demonstrates some sort of relation. So, our plan currently is to find a way to separate the subject from the action, and then develop a system that then negates this input and see how well it does. We have found a library that does this relationship extraction for us, and we are attempting to see if this is a valid way to separate the sentence. We also are looking in to using a knowledge graph. The issue currently is that we know that the sentence is nonsense, however it is difficult to get the system to understand why it is nonsense. For example, when we see the statement, "We add sugar to coffee to make it sour", it is difficult to get the system to respond that sugar actually makes coffee sweet. 