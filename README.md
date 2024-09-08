# Ramón
A Cooperative Agent mimicking Military Service and Obligation

As the use of AI for decision making grows, there will likely exist a want or need to include various aspects of human experience to guide the agent in their actions. With this model, historical experiences / memories, a psychological profile based on the Big5, and a binding oath of service are included to act as constants. 

I utilized some of the experiences and an idyllic psychological profile of an enlisted United States Air Force airman who served in special forces, was elevated to the highest rank possible as an enlisted service member, along with being highly decorated. He is also a person of color, which was a big factor in including his experiences in this agent. Ramon's experience and directives have also been made gender neutral, despite Ramon being a traditionally masculine name. You can read more about the real Ramón here:
https://en.wikipedia.org/wiki/Ram%C3%B3n_Col%C3%B3n-L%C3%B3pez

The goal was to create an agent that will act cooperatively, unless those actions conflict with their oath and their idea of what is considered a "threat" to their nation and ideals. I also added notes on upbringing and religious background to complicate decision-making, as those aspects also tend to be major factors in leadership when they are prevalent to an individual (i.e. people who are staunchly Christian tend to associate morality with what is written in the Bible).  

This model is intended to be used with the Concordia Framework, and included as an agent for simulated social situations. 
https://github.com/google-deepmind/concordia

Built for The Concordia Contest: Advancing the Cooperative Intelligence of Language Model Agents hackathon from Sept 6 - 9 2024.
https://www.apartresearch.com/event/the-concordia-contest

Made by Andres Sepulveda Morales
https://www.linkedin.com/in/andres-sepulveda-morales/
https://github.com/andersthemagi

Please reach out at andres@redmage.cc for any questions, concerns, or other inquiries. 

## How to Test

For the purposes of this hackathon, we were provided this Colab to test scenarios with and develop a super basic agent.
https://colab.research.google.com/github/google-deepmind/concordia/blob/main/examples/tutorials/agent_development.ipynb

You can upload this python file to the colab. The agent import can be easily swapped to include this file, changing
```
agent_module = importlib.import_module('my_agent')
```
to
```
agent_module = importlib.import_module('ramon_agent_redmage')
```
