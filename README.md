# Network-Flow-Analysis

This project demonstrates the implementation and analysis of various algorithms using Python. It showcases the use of NetworkX for graph-based algorithms, community detection using Girvan-Newman, and other algorithmic techniques related to social network analysis.

## Table of Contents
1. [Introduction]
2. [Features]
3. [Technologies Used]
4. [Setup Instructions]
5. [How to Use]
6. [Graph Visualizations]
7. [Recommendations System]
8. [Bar Graph Analysis]
9. [Community Detection]


## Introduction

This project focuses on the design and analysis of algorithms (DAA) using Python. The primary objective is to study and implement algorithms like community detection and recommendation systems within a network. The graph-based algorithms used are applied to a social network of individuals represented by Indian names.

## Features

- **Graph-based Algorithms**: Implementation of social networks using directed graphs (DiGraph).
- **Community Detection**: Using the Girvan-Newman algorithm to detect communities within the network.
- **Recommendation System**: Recommends users to follow based on their social connections.
- **Graph Visualizations**: Visualization of communities and network connections using Matplotlib.
- **Bar Graph Analysis**: Bar chart showing the number of followers each user has.

## Technologies Used

- **Python **
- **NetworkX**: For graph-based operations.
- **Matplotlib**: For graph and chart visualizations.
- **Random Module**: For random edge generation between nodes.

## Setup Instructions

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/NetworkFlowAnalysis.git
   cd NetworkFlowAnalysis
   ```

2. **Install Required Dependencies**:

   Install the dependencies using pip:

   ```bash
   pip install -r requirements.txt
   ```

  

3. **Run the Project**:

   You can run the project with:

   ```bash
   python main.py
   ```

## How to Use

1. **Graph Creation**: The program creates a directed graph of 50 nodes, where each node is a user represented by an Indian name. The nodes are connected randomly to simulate a following relationship.
2. **Community Detection**: The project uses the Girvan-Newman algorithm to detect and highlight communities in the social network.
3. **Recommendations**: The recommendation function suggests up to 5 users for each individual based on their followers and social connections.
4. **Visualizations**: The project generates multiple visualizations, including the social network graph with community highlights and a bar chart showing follower counts.

## Graph Visualizations

The project provides visual representations of the detected communities in the social network:

- **Community Graphs**: Each community detected by the Girvan-Newman algorithm is visualized separately with nodes colored by their respective community.
- **Combined Graph**: The entire social network is visualized, with all communities highlighted in different colors.

## Recommendations System

The recommendation system suggests users to follow based on their network connections. Each user is provided up to 5 recommendations, which are printed out in the console.

## Bar Graph Analysis

A bar chart is generated to show the number of followers each user has. This provides insight into the popularity of individuals within the social network.

## Community Detection

The Girvan-Newman algorithm is used to detect densely connected communities in the network. These communities are visualized in separate graphs to showcase the social connections.


