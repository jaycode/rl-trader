# RL Trader

## Overview

This project aims to open-source the development of a trading system for Quantopian. Ideally, we'd like to be able to do calculations and weights creations (can be loosely interpreted as "alphas") in one server, let's call this the Quant system, and use these weights in the Quantopian server.

To do this, a set of double-facing application needs to be build. So far I have built a very crude version of the Quant system. Feel free to hop in to build the Quantopian-facing system. The Quant system is now using a Reinforcement Learning and it exports Q.csv into an Amazon S3 server. This file at the time of writing this file would need to be updated a bit to follow the convention of the [fetcher](https://www.quantopian.com/posts/new-feature-fetcher) command.

Read the accompanying "RLTrading-UdacityMLCapstone.pdf" for more information about the Quant system.

Let me know if you wish to help or have any question.

## TODOs

- Work on Quantopian-facing system.
- Replace the back testing and commission parts with [zipline](https://github.com/quantopian/zipline).