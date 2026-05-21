---
title: DisSModel CA Explorer
emoji: 🗺️
colorFrom: green
colorTo: blue
sdk: docker
pinned: false
---

# DisSModel CA Explorer

Interactive explorer for cellular automaton models implemented with
[DisSModel](https://github.com/DisSModel/dissmodel), an open-source
Python framework for spatially explicit dynamic modelling.

## Models available
- Anneal, Fire, Game of Life, Growth, Snow, Parity, Excitable, Oscillator,
  Parasit, Wolfram, SolidDiffusion, InterspecificCompetition, and more.

## Running locally (with Docker)
docker build -t dissmodel-ca-demo .
docker run -p 7860:7860 dissmodel-ca-demo
