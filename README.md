## Social Network Analysis on Telegram Datasets

This repository contains a Telegram social network dataset that I created and enriched by merging multiple related datasets. The goal of this project is to analyze how users, groups, and channels are connected within Telegram and to apply important Social Network Analysis (SNA) algorithms to uncover hidden patterns, influence, and anomalies.

The dataset models Telegram as a graph, where:

Nodes represent users, channels, or groups

Edges represent interactions such as messages, replies, mentions, or shared links

By converting Telegram activity into a network, we can study how information flows and who plays key roles in the ecosystem.

Objectives of the Project

The main goals of this project are:

To understand how Telegram communities are structured

To identify influential users and hubs

To detect abnormal or suspicious behavior

To analyze how information spreads across the network

Algorithms & Techniques Used

This project applies several important Social Network Analysis (SNA) techniques, including:

1. Centrality Measures

Used to identify important nodes in the network:

Degree Centrality – Who has the most connections

Betweenness Centrality – Who acts as a bridge between communities

Closeness Centrality – Who can reach others the fastest

Eigenvector Centrality – Who is connected to other important nodes

2. PageRank

Used to find the most influential users or channels, similar to how Google ranks web pages.

3. Community Detection

Used to find tightly connected groups inside Telegram:

Louvain Algorithm

Modularity-based clustering

4. Anomaly Detection

Used to identify:

Bots

Spammers

Fake or abnormal users

Coordinated behavior

Why This Project Matters

Telegram is widely used for:

Social communication

News distribution

Activism

Marketing

(and sometimes misinformation)

Understanding its network structure helps in:

Tracking influence

Detecting fake accounts

Studying information diffusion

Cyber-security & digital forensics

Technologies Used

Python

NetworkX

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn
