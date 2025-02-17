# Agents architecture

In this project we will go through the interesting blog post proposed by Anthropic - Building effective agents.<br>This blog post aim to answer the main question of the year: what are agents? How can we use them to do what?<br>
In addition to answering this important question we will go through building each proposed architectures proposed by Anthropic and explaining when we can use it.<br>

## What is an Agent?
In my life I really appreciate a lot of things, but nothing satisfies me as summerize difficult concepts in few words.<br>
So when people ask me about agents I propose this definition:<br><br> an Agent is nothing else than 'state machine' that loops through differents 'state' and 'tools' powered by an llm model that enables them to understand verbal requests.<br>
I know that is a very brief definition but it touches the main points.

In this blog post Anthropic address what is an Agent and also explain what is a workflow: so let's first define what is a workflow.

## Workflows

We can think of a workflow as a predefined code path - like a sort of scaffold - built around LLM calls. 
