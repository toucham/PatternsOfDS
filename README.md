# PatternsOfDS

This repository contains all the C# projects that apply the patterns described in the "Patterns of Distributed System".
Each pattern will be implemented as .NET library that is used within the `example` folder. In order to see the application of the pattern, look in the `example` folder.

## Project Structures

All patterns are implemented inside the `src` folder. These are the patterns implemented:

- 2 Phase Commit
- Write Ahead Log
- Paxos Algorithm

All of these are used in a client-server architecture web server inside the `sample` folder. All sample applications use the same structure with one client and multiple servers. The client is a terminal client that user can send a cmd to simulate requests according to your choice. These includes:

- A single request with custom body
- `x` number of requests sent with `y` seconds interval
- Concurrent `x` requests sent with `y` seconds interval

All of these applications are implemented using C#.
