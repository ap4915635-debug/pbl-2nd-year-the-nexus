# pbl-2nd-year-the-nexus
GEHU PBL Academic Project - Team The Nexus

KeyFlux – Mini Redis Cache System

GEHU PBL Academic Project – Team The Nexus

About the Project

KeyFlux is a mini Redis-inspired in-memory key-value cache system developed using C++. It stores data in RAM and supports basic cache operations such as SET, GET, DELETE and DISPLAY.

The project also implements cache replacement using an LFU (Least Frequently Used) policy with LRU (Least Recently Used) as a tie-breaker.

Features

- SET – Insert or update key-value pairs.
- GET – Retrieve values using keys.
- DELETE – Remove stored entries.
- DISPLAY – Display all cache entries.
- LFU with LRU tie-breaking – Select a cache entry for eviction.
- Cache Statistics – Track hits, misses and their ratios.
- Fixed Cache Capacity – Maximum 5 entries.

Data Structures and Concepts Used

- Classes and Objects
- Doubly Linked List
- Dynamic Memory Allocation
- Pointers
- Constructors and Destructors
- Linear Searching
- Cache Eviction
- Hit and Miss Statistics

Cache Replacement Policy

KeyFlux uses LFU (Least Frequently Used) as its primary eviction policy.

When multiple entries have the same frequency, the entry with the oldest last-used time is selected for eviction (LRU tie-breaking).

Project Implementation

The complete C++ source code is provided below.

How to Run

Compile the program using a C++ compiler:

g++ main.cpp -o keyflux

Run the program:

./keyflux

Team

Team Name: The Nexus

Project: KeyFlux – Mini Redis Cache System

Platform: C++.
        
