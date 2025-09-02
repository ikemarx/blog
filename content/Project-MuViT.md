---
title: "Project MuViT"
date: 2025-08-15T12:33:07-03:00
draft: true
---

# Projeto MuViT

ideia: chess engine

fase 1:
    python
    pytorch
    numpy
    python-chess
    ChessEnvironment(wrapper, api):
        init
        get observation
        get legal actions
        step(action)
        is game over
        get game outcome

fase 2:
    ViT: input (21, 8, 8) minimum channels for everything, including draws
    64 patches
    linear projection
    positional encoding
    transformer encoder

    output: hidden state vector

fase 3:
    monte carlo tree search muzero

fase 4:
    self play
    replay buffer
    training
    loss function (value loss, policy loss)
