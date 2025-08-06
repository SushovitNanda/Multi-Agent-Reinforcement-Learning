# Multi-Agent Reinforcement Learning (MARL) Course Project

This repository contains the complete coursework for the Multi-Agent Reinforcement Learning course, including assignments, mid-semester exam, and end-semester project. The course covers various reinforcement learning algorithms and their applications in multi-agent systems.

## Project Structure

### Assignment-1
**Date**: 28th August 2024

**Contents**:
- `Assignment_1.ipynb` - Jupyter notebook containing implementation and analysis
- `Assignment-1.pdf` - Assignment question paper
- `MARL - Assignment-1.pdf` - Assignment instructions
- `README.md` - Detailed analysis and insights

**Key Features**:
- Implementation of reinforcement learning algorithms
- Analysis of learning outcomes and insights
- Handwritten solutions for specific questions
- Compatible with Google Colab, Jupyter Notebook, and Visual Studio Code

---

### Assignment-2
**Contents**:
- `Q1_DP.ipynb` - Dynamic Programming solution for Travelling Salesman Problem (TSP)
- `Q1_MC.ipynb` - Monte Carlo solution for TSP
- `Q2_DP.ipynb` - Dynamic Programming solution for Sokoban Puzzle
- `Q2_MC.ipynb` - Monte Carlo solution for Sokoban Puzzle
- `MARL - Assignment-2.pdf` - Assignment instructions
- `README.md` - Comprehensive analysis of DP vs MC methods

**Key Insights**:
- **Dynamic Programming**: Provides consistent outputs using deterministic updates based on Bellman equation
- **Monte Carlo**: Produces varying results due to random sampling and exploration strategies
- **TSP Analysis**: DP works well for smaller-scale problems, MC struggles with large state spaces
- **Sokoban Analysis**: DP converges faster in deterministic environments, MC better for complex scenarios

---

### Assignment-3
**Contents**:
- `Q1.ipynb` - Implementation for Question 1
- `Q2.ipynb` - Implementation for Question 2
- `MARL - Assignment-3.pdf` - Assignment instructions
- `README.md` - Analysis and insights

---

### MidSem
**Contents**:
- `Mod_Tsp.ipynb` - Modified Travelling Salesman Problem implementation using Q-Learning
- `MARL - Midsem (1).pdf` - Mid-semester exam paper
- `README.md` - Detailed analysis of Q-Learning performance

**Key Features**:
- **Algorithm**: Q-Learning (off-policy, model-free)
- **Environment**: Modified TSP with 10 targets, max_area: 15
- **Hyperparameters**: 
  - Learning rate: 0.1
  - Discount factor: 0.99
  - Episodes: 999
- **Results**: Converges to optimal policy with reward ~159.56 which is very less compared to the theoretical maximum possible value of approx ~350 
- **Performance**: Consistent positive rewards after episode 600

---

### EndSem Project
**Project**: Multi-Agent Grid Coverage

**Contents**:
- `Grid_Environment.ipynb` - Main grid environment implementation
- `Q_Learning_With_Obstacles.ipynb` - Q-Learning with obstacle scenarios
- `Q_Learning_Without_Obstacles.ipynb` - Q-Learning without obstacles
- `Multi_Agent_Grid_Coverage_Report.pdf` - Project report
- `MARL Project.pptx` - Project presentation
- `README.md` - Comprehensive project documentation

**Project Overview**:
- **Problem**: Multi-agent reinforcement learning for complete grid coverage
- **Environment**: 10x10 grid with 3 agents and optional obstacles
- **Algorithm**: Q-Learning with epsilon-greedy exploration
- **Agents**: Starting positions at (0,0), (9,0), (9,9)
- **Objectives**: 
  - Visit every cell exactly once
  - Minimize overlaps and collisions
  - Optimize collaborative behavior

**Key Results**:
- Successful partial grid coverage in most episodes
- Effective learning with decreasing TD errors
- Dynamic adaptation to obstacle placement
- Visual coverage maps and reward trend analysis

---

## Technical Requirements

### Dependencies
- Python 3.x
- Jupyter Notebook
- gymnasium==0.29.1
- numpy==1.26
- Matplotlib
- Pandas
- (Additional dependencies may be required based on specific implementations)

### Running the Code
1. **Jupyter Notebooks**: All `.ipynb` files can be run in:
   - Google Colab
   - Jupyter Notebook
   - Visual Studio Code with Jupyter extension

2. **PDF Files**: Assignment papers and project reports for reference

3. **Analysis**: Each folder contains detailed README files with insights and observations

---

## Learning Outcomes

### Algorithm Comparisons
- **Dynamic Programming vs Monte Carlo**: Understanding deterministic vs stochastic approaches
- **Q-Learning**: Off-policy learning for complex environments
- **Multi-Agent Systems**: Collaborative learning and coordination

### Key Concepts Covered
- Markov Decision Processes (MDP)
- Bellman Equations
- Exploration vs Exploitation
- Temporal Difference Learning
- Policy Optimization
- Multi-Agent Coordination

---

## Performance Metrics

### Assignment-2 Results
- **DP Methods**: Consistent, deterministic convergence
- **MC Methods**: Variable results with exploration benefits
- **TSP**: DP superior for small problems, MC struggles with large state spaces
- **Sokoban**: DP faster convergence, MC better for complex scenarios

### MidSem Results
- **Convergence**: Episode 600+ with reward ~159.56
- **Learning**: Effective Q-Learning implementation
- **Exploration**: Balanced epsilon-greedy strategy

### EndSem Project Results
- **Grid Coverage**: Successful partial coverage
- **Multi-Agent Coordination**: Effective collaborative behavior
- **Obstacle Adaptation**: Dynamic policy adjustment

---

## Project Highlights

1. **Comprehensive Algorithm Coverage**: From basic DP to advanced multi-agent Q-Learning
2. **Practical Applications**: TSP, Sokoban, Grid Coverage problems
3. **Performance Analysis**: Detailed comparisons and insights
4. **Visualization**: Coverage maps, reward trends, and learning curves
5. **Real-world Scenarios**: Obstacle handling and multi-agent coordination

---

## Notes

- All implementations include detailed comments and analysis
- Performance metrics and insights are documented in respective README files
- Code is designed for educational purposes with clear explanations
- Results may vary due to the stochastic nature of some algorithms

---

