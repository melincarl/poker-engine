# poker-engine
A poker evaluater. Using statistical and probabilty tools making founded-decisions in poker. A tool for learning and analysis. Built from scratch in python.

## Goals

The aim of the projects is to create a usuable tool for poker while getting confident and experience in creating projects from scratch. Priorities lies with leaning: python project structure, Monte Carlo Simulation, statistics, probability etc.

## Milestones

- [ ] **1. Cards and deck**
  Card and Deck classes using dataclasses and enums, with the code split
  into modules.
- [ ] **2. Hand evaluator**
  Rank any 5-card hand and find the best 5 of 7 cards, with pytest tests
  for every hand category.
- [ ] **3. Equity calculator**
  Monte Carlo equity for a hand against one or more opponents, with or
  without board cards. Validated against known equities, using the
  standard error to choose the number of simulations.
- [ ] **4. Usable and fast**
  A command-line interface, exact enumeration compared against Monte
  Carlo, and a profiled and optimized evaluator.
- [ ] **5. Decisions**
  Pot odds and expected value of a call, equity against a range of
  hands, and a helper suggesting fold, call or raise.
- [ ] **6. Simulation**
  Bots with simple strategies play each other, profit and loss are
  tracked per bot, and statistical tests determine how many hands it
  takes to tell skill from luck.

**Stretch goals:** solve Kuhn poker with counterfactual regret
minimization; a simple web interface.

## Setup

For now: Clone repo, create virual environemnt, and install pytest (Updates comes with progression)