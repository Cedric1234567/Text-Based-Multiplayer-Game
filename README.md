# Server for a Text-Based-Multiplayer-Game

Description

This is a server-side C program that implements a text-based, Pokémon-like fighting game, showcasing the use of Unix sockets and inter-process communication (IPC) to facilitate real-time multiplayer interactions. The server efficiently handles connections, enabling multiple players to join and participate in battles.
When two compatible players connect, the program initiates a game session between them, managing the match rules and interactions seamlessly. If no suitable opponent is available, players are queued until a compatible match can be arranged. Importantly, the server is designed to support concurrency, allowing multiple game sessions to execute in parallel. This ensures that new players can connect and play without impacting ongoing matches, making it a robust and scalable system for multiplayer gameplay.
