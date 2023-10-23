# Taxi-V3 Q-Learning Project

This project demonstrates Q-learning on the Taxi-v3 environment from OpenAI's Gym library. The Q-learning algorithm is used to train an agent to perform tasks in this environment.

## Features

- Q-learning agent trained on the Taxi-v3 environment.
- Ability to run the agent from specific locations (taxi, source, and destination).
- Customizable locations of the taxi, source, and destination.
### Training the Agent

Before running the Q-learning agent, you need to train it. Run the provided Jupyter Notebook or Python script to train the agent.

###Running the Agent
To run the Q-learning agent from specific locations (taxi, source, and destination), use the provided functions in the code. Here's an example of how to run the agent from a specific state:

encoded_state = env.encode(taxi_row, taxi_col, pass_idx, dest_idx)
run_q_learning_agent_on_encoded_state(q_table, encoded_state)

You can change the taxi_row, taxi_col, pass_idx, and dest_idx to specify the locations you want.

###Future Updates
In future updates, we plan to enhance the project by allowing for different environments to be used. This will provide more flexibility in experimenting with various reinforcement learning scenarios.

##Reference
OpenAI Gym: For the Taxi-v3 environment
