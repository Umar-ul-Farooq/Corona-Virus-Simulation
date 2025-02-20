# Disease Spread Simulation in NetLogo

## Overview
This project is a NetLogo-based agent-based simulation designed to model the spread of an infectious disease among a population of agents. The simulation evaluates the effects of different intervention strategies on disease transmission, including travel restrictions, social distancing, and self-isolation. The goal is to analyze the impact of these measures and assess which are most effective in controlling disease spread.
## Features
•	Two distinct populations (pink and gray) with different population sizes.
•	Infection spread modeling based on proximity, infection rate, and immunity.
•	Configurable interventions such as travel restrictions, social distancing, and self-isolation.
•	Real-time tracking of infection rates, deaths, and immunity levels.
•	Customizable parameters including initial infection levels, survival rates, and immunity duration.
## Setup
1.	Install NetLogo 6.1.0 or higher.
2.	Open the .nlogo file in NetLogo.
3.	Click the Setup button to initialize the environment.
4.	Click Run/Go Model to start the simulation.
## Key Model Components
### 1. World Setup
•	Initializes a 91x91 grid divided into two regions (pink and gray).
•	Populations are assigned to respective regions.
•	Default parameters are set, including infection rates and population sizes.
### 2. Agent Behavior
•	Agents move randomly within their regions unless travel restrictions are off.
•	Infection occurs when a susceptible agent is within 1 patch of an infected agent.
•	Social distancing enforces a 1-patch gap between agents.
•	Self-isolation stops movement and marks infected agents in blue.
•	Infected agents recover or die based on survival rate, and recovered agents gain temporary immunity.
### 3. Model Outputs
The simulation tracks:
•	Total infections, deaths, and recoveries.
•	Effectiveness of social distancing, self-isolation, and travel restrictions.
•	Impact of population density on infection spread.
## Results & Analysis
The model runs over a set number of ticks (e.g., 5,000 to 20,000) and calculates:
•	Most effective measure for reducing infection.
•	Least effective measure.
•	Population with the highest mortality rate.
•	Impact of population density on disease spread.
## Running the Analysis
1.	Run the model with different settings (e.g., toggling social distancing, self-isolation, or travel restrictions).
2.	Observe the infection rates, mortality, and immunity trends.
3.	Use collected data to determine the best strategies for controlling outbreaks.
## Acknowledgments
This project was developed as part of an Artificial Life with Robotics module, focusing on agent-based modeling for real-world problem-solving.

