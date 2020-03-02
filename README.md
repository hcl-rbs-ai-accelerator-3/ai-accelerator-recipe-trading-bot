# ai-accelerator-recipe-trading-bot
This work uses a Model-free Reinforcement Learning technique called Deep Q-Learning (neural variant of Q-Learning). At any given time (episode), an agent abserves it's current state (n-day window stock price representation), selects and performs an action (buy/sell/hold), observes a subsequent state, receives some reward signal (difference in portfolio position) and lastly adjusts it's parameters based on the gradient of the loss computed.
