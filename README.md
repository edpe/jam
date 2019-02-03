# jam

A cellular social simulation


## Rules

* Single cell, stationary agents are randomly spawned on a grid

* Agents have two parameters: **Social Need** and **Social Energy**

* When Social Need becomes *too high*, the agent ventures out to look for **social interaction** and become attracted by other    agents

* The physically closer agents are, the stronger the fulfillment of **Social Need**

* Agents can see ahead *X* number of squares

* Agents **Social Need** and **Social Energy** deplete on **social interaction**

* Agents are repelled by other agents and seek isolation when **Social Need** is satisfied or when **Social Energy** is sufficiently depleted


* There is an *X%* chance of spawning a new agent on direct social contact

* Agent's ability to regenerate and drain the **Social Need** and **Social Energy** of others is unique to the agent

* Agent's have a unique pattern of movement when seeking **social interaction** but will venture further as **Social Need** increases

* If **Social Need** is at maximum for *too long*, the agent dies

* If **Social Energy** is at minimum for *too long*, the agent dies

