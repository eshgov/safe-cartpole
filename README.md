# Safe Reinforcement Learning for Autonomous Racing: Training a Safety Filter From Scratch

This repository contains the code, figures, and final report for my Independent Work (IW) project at Princeton University, advised by Professor Jaime Fernández Fisac and Donggeon David Oh.

## Project Overview

This project implements a least-restrictive safety filter (LRSF) for reinforcement learning, inspired by Hamilton–Jacobi reachability theory. We integrate a learned safety critic into Soft Actor-Critic (SAC) and apply the method to a proof-of-concept environment: CartPole-v1. The results demonstrate that safety-aware agents can improve long-term performance by avoiding premature failures while satisfying safety constraints.

## Repository Contents

- `safe_cartpole.ipynb` — Jupyter Notebook for training and evaluating the SAC agent with a Least-Restrictive Safety Filter (LRSF) on CartPole-v1.
- `figures/` — Figures used in the final report, including performance comparisons, intervention breakdowns, and environment diagrams.
- `written_final_report.pdf` — Final Independent Work (IW) report submitted Spring 2025.

## Highlights

- Formulation and proof of a discounted safety Bellman operator for scalable safe RL.
- Implementation of a safety critic and action filtering mechanism in SAC.
- Experimental validation of the safety filter’s effectiveness in improving agent performance and stability.
- Motivation for scaling safe RL methods to high-speed autonomous racing domains.

## Code Footnote

The link to this repository is referenced via a footnote in the Introduction section of the final report.

## Citation

If you use or reference this project, please cite:

> Eshaan Govil, "Safe Reinforcement Learning for Autonomous Racing: Training a Safety Filter From Scratch," Princeton University Independent Work Report, Spring 2025.

## Acknowledgments

Special thanks to Professor Jaime Fernández Fisac, Donggeon David Oh, and the Safe Robotics Lab at Princeton University for their guidance and support. Thanks also to Princeton Autonomous Vehicle Engineering (PAVE) for inspiring the broader racing context behind this work.

---
