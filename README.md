# Soccer Performance Tracker

A C# console application for tracking soccer player performance, identifying areas for improvement, and generating position-specific training recommendations.

## Overview

Soccer Performance Tracker allows a user to create a player profile, record match statistics, review performance, identify weaknesses, and generate a training plan based on the player's position.

I built this project to practice object-oriented programming in C# and to apply concepts such as inheritance, polymorphism, encapsulation, collections, and reusable class design in a practical application.

## Features

- Create player profiles for:
  - Strikers
  - Midfielders
  - Defenders
- Record match statistics including:
  - Goals
  - Assists
  - Passes completed
  - Passes attempted
- Calculate average passing accuracy
- View accumulated player statistics
- Generate a player performance rating from 0–100
- Identify position-specific weaknesses
- Generate recommended training drills
- Menu-driven console interface

## Object-Oriented Design

The project uses an abstract `Player` base class to store common player information and behavior.

Position-specific classes inherit from `Player`:

- `Striker`
- `Midfielder`
- `Defender`

Each position overrides the weakness evaluation behavior, allowing the program to provide recommendations specific to the type of player.

The project also separates responsibilities across classes for matches, training drills, and training-plan generation.

## Technologies

- C#
- .NET
- Object-Oriented Programming
- Git
- GitHub

## Concepts Practiced

- Classes and objects
- Encapsulation
- Inheritance
- Polymorphism
- Abstract classes
- Method overriding
- Lists and collections
- Loops and conditional logic
- User input
- Basic calculations
- Separation of responsibilities across classes

## Example Workflow

When the program starts, the user creates a player and selects a position.

The main menu then allows the user to:

1. Add Match
2. View Stats
3. View Weaknesses
4. Generate Training Plan
5. View Player Rating
6. Exit

As match data is added, the application uses that information to calculate statistics and provide performance feedback.

## What I Learned

This project helped me strengthen my understanding of how multiple C# classes can work together in one application. It gave me practical experience using inheritance and polymorphism to create different player behaviors while keeping shared functionality in a common base class.

It also helped me practice breaking a larger program into smaller classes with separate responsibilities instead of putting all application logic into one file.
