# Optimizing Human Traffic Flow in Istanbul’s Public Transportation System

This project focuses on improving the efficiency of human traffic flow within Istanbul’s public transportation network by applying intelligent optimization techniques. The key objective is to reduce overcrowding, shorten waiting times, and optimize boarding procedures by determining ideal operating hours and adjusting schedules in rail (RAYLI) and road (OTOYOL) transportation systems.

## 🎯 Objective

To develop and apply optimization algorithms that determine the least congested hours of public transport operation in Istanbul, thus improving commuter experience and urban mobility efficiency.

## 📊 Data

We used hourly public transportation data from Istanbul’s open dataset:
- 📁 Source: [Istanbul Public Transportation Dataset](https://ulasav.csb.gov.tr/dataset/34-hourly-public-transport-data-set/)
- Data was filtered to focus on relevant features and transformed to support weekday-based optimization.

## 🧮 Algorithms

- **Genetic Algorithm** simulates natural selection to evolve optimal schedules based on fitness.
- **Particle Swarm Optimization** uses swarm intelligence to discover the least congested hours.
- **Simulated Annealing** probabilistically explores the solution space to escape local optima.

All algorithms use a fitness function based on the inverse of the total number of passengers:
Fitness = 1 / (Total Passengers + 1)


## 📈 Results

Comparative plots demonstrate the performance of GA, PSO, and SA across:
- RAYLI and OTOYOL transportation systems
- All days of the week
- Best, medium, and worst congestion hours

## 🌍 Real-World Impact

The findings can support Istanbul Metropolitan Municipality (İBB) in:
- Dynamically optimizing metro/bus schedules
- Strategically allocating additional departures
- Reducing environmental impacts
- Enhancing commuter health and safety

### How to Run:
1. Clone this repository.
2. Open `project.ipynb` with Jupyter Notebook.
3. Run all cells to see results and visualizations.
---
